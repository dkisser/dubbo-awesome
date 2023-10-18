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
[INFO] benchmark-base ..................................... SUCCESS [  3.593 s]
[INFO] server-base ........................................ SUCCESS [  0.556 s]
[INFO] client-base ........................................ SUCCESS [  0.768 s]
[INFO] dubbo-hessianlite-client ........................... SUCCESS [  0.422 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  5.781 s
[INFO] Finished at: 2023-10-18T18:08:38Z
[INFO] ------------------------------------------------------------------------

RUN dubbo-hessianlite-client IN benchmark MODE
command is: java -server -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output= -jar dubbo-hessianlite-client/target/dubbo-hessianlite-client-1.0-SNAPSHOT.jar --warmupIterations=1 --warmupTime=1 --measurementIterations=1 --measurementTime=1

[Ljava.lang.String;@6d03e736
# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 18:08:39.198 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:39.227 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:39.312 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:39.314 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:39.335 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:39.336 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:39.359 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:39.363 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:39.429 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:39.602 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:39.602 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:39.610 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:39.611 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:39.617 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:39.619 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:39.637 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.174
18:08:39.638 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:39.641 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:39.644 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:39.645 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:39.646 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.174
18:08:39.647 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@435d391d, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:39.830 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:39.861 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:39.899 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:39.965 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:39.966 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:39.967 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:39.967 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:39.987 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:39.993 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:39.997 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:40.057 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:40.220 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:40.221 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:40.221 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:40.222 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:40.395 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:08:40.396 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:40.554 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.174:8080 from NettyClient 10.1.0.174 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0xc3faf5d7, L:/10.1.0.174:56354 - R:/10.1.0.174:8080]], dubbo version: 3.2.7, current host: 10.1.0.174
18:08:40.554 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.174 connect to the server /10.1.0.174:8080, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:40.556 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.174:56354 -> /10.1.0.174:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:40.591 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:40.592 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.174, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:08:40.612 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:40.613 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:40.617 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:40.618 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:40.669 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.174, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:08:40.724 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:08:40.724 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:40.726 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2101&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652520665&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:40.727 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2101&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652520665&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:40.747 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:08:40.747 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:40.755 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:40.762 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2101&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652520665&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.174
18:08:40.763 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:40.771 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.174
1.211 ops/ms
Iteration   1: 18:08:42.849 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:42.854 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xc3faf5d7, L:/10.1.0.174:56354 - R:/10.1.0.174:8080], dubbo version: 3.2.7, current host: 10.1.0.174
18:08:42.860 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:42.860 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:42.860 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.174:56354 -> /10.1.0.174:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:42.861 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:42.862 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:42.862 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:42.862 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:44.877 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2101&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652520665&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:44.877 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2101&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652520665&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:44.878 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:44.878 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:44.879 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.174
18:08:44.881 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:44.884 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:44.884 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.174
18:08:44.885 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:44.885 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:44.885 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:44.885 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:44.885 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.174
18:08:44.885 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:44.885 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:44.886 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:44.886 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:44.886 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:44.888 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:44.888 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:44.890 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-14] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@435d391d, dubbo version: 3.2.7, current host: 10.1.0.174
2.908 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.908 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:24
# Fork: 1 of 1
# Warmup Iteration   1: 18:08:46.767 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:46.793 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:46.860 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:46.862 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:46.888 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:46.890 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:46.909 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:46.911 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:46.955 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:47.153 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:47.154 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:47.158 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:47.158 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:47.161 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:47.162 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:47.170 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.174
18:08:47.170 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:47.172 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:47.174 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:47.175 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:47.177 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.174
18:08:47.177 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1cb93abc, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:47.386 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:47.420 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:47.467 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:47.523 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:47.527 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:47.527 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:47.529 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:47.551 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:47.557 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:47.568 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:47.612 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:47.767 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:47.768 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:47.770 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:47.770 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:47.941 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:08:47.942 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:48.112 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.174:8080 from NettyClient 10.1.0.174 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0xa10967c6, L:/10.1.0.174:56366 - R:/10.1.0.174:8080]], dubbo version: 3.2.7, current host: 10.1.0.174
18:08:48.112 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.174 connect to the server /10.1.0.174:8080, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:48.117 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.174:56366 -> /10.1.0.174:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:48.155 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:48.156 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.174, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:08:48.172 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:48.174 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:48.183 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:48.184 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:48.260 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.174, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:08:48.310 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:08:48.311 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:48.323 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2399&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652528246&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:48.324 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2399&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652528246&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:48.339 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:08:48.339 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:48.348 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:48.356 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2399&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652528246&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.174
18:08:48.357 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:48.362 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.174
4.593 ops/ms
Iteration   1: 18:08:50.403 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:50.406 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xa10967c6, L:/10.1.0.174:56366 - R:/10.1.0.174:8080], dubbo version: 3.2.7, current host: 10.1.0.174
18:08:50.418 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.174:56366 -> /10.1.0.174:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:50.418 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:50.419 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:50.419 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:50.419 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:50.420 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:50.420 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:52.441 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2399&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652528246&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:52.442 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2399&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652528246&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:52.442 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:52.443 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:52.443 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.174
18:08:52.444 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:52.445 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:52.447 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.174
18:08:52.447 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:52.448 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:52.448 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:52.448 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:52.448 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.174
18:08:52.448 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:52.448 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:52.449 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:52.449 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:52.449 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:52.452 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:52.452 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:52.456 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-20] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@1cb93abc, dubbo version: 3.2.7, current host: 10.1.0.174
9.089 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  9.089 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 18:08:54.352 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:54.389 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:54.455 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:54.456 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:54.475 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:54.476 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:54.496 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:54.501 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:54.544 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:54.732 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:54.733 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:54.741 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:54.742 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:54.747 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:54.748 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:54.764 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.174
18:08:54.764 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:54.767 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:54.768 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:54.769 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:54.770 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.174
18:08:54.771 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@ddd5c91, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:54.976 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:55.012 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:55.077 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:55.152 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:55.155 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:55.156 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:55.156 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:55.186 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:55.193 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:55.200 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:55.243 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:55.409 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:55.410 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:55.410 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:55.411 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:55.594 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:08:55.595 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:55.713 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.174:8080 from NettyClient 10.1.0.174 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0xacce2cf0, L:/10.1.0.174:59202 - R:/10.1.0.174:8080]], dubbo version: 3.2.7, current host: 10.1.0.174
18:08:55.713 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.174 connect to the server /10.1.0.174:8080, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:55.718 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.174:59202 -> /10.1.0.174:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:55.758 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:55.760 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.174, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:08:55.777 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:55.778 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:55.786 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:55.787 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:55.850 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.174, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:08:55.918 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:08:55.918 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:55.923 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2495&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652535841&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:55.924 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2495&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652535841&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:55.947 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:08:55.947 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:55.956 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:55.966 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2495&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652535841&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.174
18:08:55.967 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:55.973 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.174
2.509 ops/ms
Iteration   1: 18:08:58.028 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:58.033 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xacce2cf0, L:/10.1.0.174:59202 - R:/10.1.0.174:8080], dubbo version: 3.2.7, current host: 10.1.0.174
18:08:58.035 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.174:59202 -> /10.1.0.174:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:58.041 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:58.041 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:58.042 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:58.043 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:08:58.043 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:08:58.044 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:00.075 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2495&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652535841&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:00.075 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2495&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652535841&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:00.076 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:00.076 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:00.077 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:00.078 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:00.079 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:00.080 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:00.080 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:00.080 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:00.080 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:00.080 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:00.081 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:00.081 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:00.081 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:00.083 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:00.083 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:00.084 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:00.085 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:00.086 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:00.088 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-22] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@ddd5c91, dubbo version: 3.2.7, current host: 10.1.0.174
5.352 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.352 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 18:09:01.933 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:01.973 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.037 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.038 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.056 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.058 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.070 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.071 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.109 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.294 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.294 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.301 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.302 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.309 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.311 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.328 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.329 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.332 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.337 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.339 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.341 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.342 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@ddd5c91, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.558 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.587 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.627 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.697 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.699 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.699 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.700 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.727 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.736 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.745 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.805 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.959 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.961 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.962 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:02.962 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:03.133 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:09:03.149 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:03.288 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.174:8080 from NettyClient 10.1.0.174 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x092ae245, L:/10.1.0.174:42422 - R:/10.1.0.174:8080]], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:03.288 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.174 connect to the server /10.1.0.174:8080, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:03.292 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.174:42422 -> /10.1.0.174:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:03.325 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:03.327 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.174, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:09:03.341 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:03.342 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:03.353 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:03.357 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:03.411 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.174, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:09:03.475 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:09:03.476 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:03.480 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2591&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652543408&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:03.480 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2591&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652543408&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:03.503 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:09:03.504 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:03.513 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:03.531 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2591&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652543408&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:03.532 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:03.538 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.174
1.035 ops/ms
Iteration   1: 18:09:05.658 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:05.660 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x092ae245, L:/10.1.0.174:42422 - R:/10.1.0.174:8080], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:05.662 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.174:42422 -> /10.1.0.174:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:05.670 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:05.674 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:05.674 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:05.674 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:05.675 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:05.675 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:07.699 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2591&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652543408&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:07.699 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2591&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652543408&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:07.699 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:07.700 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:07.701 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:07.702 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:07.703 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:07.703 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:07.703 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:07.704 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:07.704 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:07.704 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:07.704 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:07.704 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:07.704 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:07.705 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:07.705 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:07.705 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:07.707 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:07.707 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:07.709 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@ddd5c91, dubbo version: 3.2.7, current host: 10.1.0.174
1.202 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.202 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:01:00
# Fork: 1 of 1
# Warmup Iteration   1: 18:09:09.728 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:09.760 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:09.820 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:09.822 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:09.842 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:09.844 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:09.859 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:09.860 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:09.897 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:10.095 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:10.096 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:10.105 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:10.105 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:10.108 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:10.109 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:10.130 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.174
18:09:10.130 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:10.133 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:10.138 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:10.140 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:10.143 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:10.143 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@32527548, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:10.339 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:10.365 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:10.419 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:10.485 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:10.488 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:10.489 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:10.490 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:10.521 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:10.532 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:10.536 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:10.586 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:10.743 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:10.744 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:10.744 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:10.744 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:10.906 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:09:10.907 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:11.050 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.174:8080 from NettyClient 10.1.0.174 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0xe0a36929, L:/10.1.0.174:46666 - R:/10.1.0.174:8080]], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:11.051 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.174 connect to the server /10.1.0.174:8080, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:11.052 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.174:46666 -> /10.1.0.174:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:11.085 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:11.087 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.174, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:09:11.100 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:11.101 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:11.105 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:11.106 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:11.175 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.174, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:09:11.227 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:09:11.227 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:11.248 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2690&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652551163&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:11.248 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2690&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652551163&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:11.263 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:09:11.263 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:11.275 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:11.285 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2690&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652551163&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:11.286 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:11.291 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.174
10.741 ±(99.9%) 0.256 ms/op
Iteration   1: 18:09:13.359 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:13.364 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xe0a36929, L:/10.1.0.174:46666 - R:/10.1.0.174:8080], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:13.374 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:13.375 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:13.375 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:13.375 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.174:46666 -> /10.1.0.174:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:13.376 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:13.376 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:13.376 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:15.398 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2690&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652551163&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:15.399 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2690&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652551163&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:15.399 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:15.400 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:15.400 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:15.401 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:15.402 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:15.403 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:15.403 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:15.403 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:15.403 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:15.403 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:15.404 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:15.404 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:15.404 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:15.404 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:15.405 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:15.405 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:15.406 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:15.407 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:15.408 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-17] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@32527548, dubbo version: 3.2.7, current host: 10.1.0.174
5.590 ±(99.9%) 0.178 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.590 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:53
# Fork: 1 of 1
# Warmup Iteration   1: 18:09:17.322 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:17.349 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:17.415 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:17.417 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:17.435 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:17.436 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:17.451 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:17.455 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:17.497 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:17.669 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:17.670 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:17.675 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:17.676 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:17.683 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:17.684 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:17.697 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.174
18:09:17.697 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:17.703 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:17.708 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:17.709 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:17.712 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:17.712 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@435d391d, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:17.916 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:17.953 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:18.002 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:18.082 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:18.086 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:18.087 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:18.089 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:18.114 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:18.119 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:18.122 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:18.172 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:18.350 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:18.351 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:18.351 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:18.352 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:18.514 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:09:18.515 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:18.670 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.174:8080 from NettyClient 10.1.0.174 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x39addbeb, L:/10.1.0.174:46676 - R:/10.1.0.174:8080]], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:18.671 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.174 connect to the server /10.1.0.174:8080, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:18.676 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.174:46676 -> /10.1.0.174:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:18.705 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:18.707 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.174, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:09:18.717 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:18.722 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:18.726 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:18.727 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:18.792 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.174, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:09:18.860 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:09:18.860 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:18.867 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2962&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652558781&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:18.867 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2962&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652558781&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:18.891 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:09:18.892 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:18.900 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:18.911 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2962&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652558781&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:18.912 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:18.918 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.174
8.336 ±(99.9%) 0.119 ms/op
Iteration   1: 18:09:20.961 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-28] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:20.963 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-28] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x39addbeb, L:/10.1.0.174:46676 - R:/10.1.0.174:8080], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:20.966 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.174:46676 -> /10.1.0.174:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:20.974 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-28] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:20.975 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-28] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:20.975 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-28] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:20.975 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-28] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:20.976 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-28] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:20.976 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-28] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:23.003 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-28] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2962&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652558781&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:23.004 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-28] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=2962&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652558781&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:23.004 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-28] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:23.005 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-28] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:23.005 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-28] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:23.006 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-28] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:23.007 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-28] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:23.010 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-28] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:23.010 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-28] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:23.010 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-28] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:23.010 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-28] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:23.011 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-28] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:23.011 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-28] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:23.011 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-28] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:23.011 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-28] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:23.012 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-28] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:23.013 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-28] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:23.013 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-28] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:23.014 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-28] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:23.014 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-28] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:23.016 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-28] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@435d391d, dubbo version: 3.2.7, current host: 10.1.0.174
2.765 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.765 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:45
# Fork: 1 of 1
# Warmup Iteration   1: 18:09:24.888 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:24.917 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:24.980 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:24.982 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.004 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.006 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.022 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.023 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.072 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.250 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.251 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.255 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.255 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.258 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.258 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.276 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.277 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.281 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.287 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.289 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.292 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.292 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@32527548, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.516 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.554 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.598 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.647 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.649 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.650 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.650 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.673 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.679 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.683 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.749 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.912 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.913 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.915 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:25.916 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:26.110 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:09:26.112 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:26.267 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.174:8080 from NettyClient 10.1.0.174 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0xeef35e06, L:/10.1.0.174:51298 - R:/10.1.0.174:8080]], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:26.267 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.174 connect to the server /10.1.0.174:8080, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:26.270 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.174:51298 -> /10.1.0.174:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:26.312 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:26.314 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.174, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:09:26.330 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:26.331 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:26.336 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:26.342 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:26.405 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.174, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:09:26.459 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:09:26.460 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:26.476 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3059&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652566399&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:26.477 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3059&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652566399&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:26.499 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:09:26.499 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:26.510 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:26.518 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3059&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652566399&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:26.519 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:26.524 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.174
11.028 ±(99.9%) 0.153 ms/op
Iteration   1: 18:09:28.588 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:28.592 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xeef35e06, L:/10.1.0.174:51298 - R:/10.1.0.174:8080], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:28.595 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.174:51298 -> /10.1.0.174:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:28.596 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:28.596 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:28.596 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:28.597 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:28.597 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:28.597 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:30.605 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3059&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652566399&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:30.607 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3059&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652566399&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:30.607 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:30.607 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:30.608 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:30.609 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:30.610 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:30.611 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:30.611 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:30.611 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:30.611 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:30.611 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:30.612 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:30.612 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:30.612 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:30.612 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:30.612 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:30.613 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:30.614 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:30.615 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:30.616 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-27] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@32527548, dubbo version: 3.2.7, current host: 10.1.0.174
4.471 ±(99.9%) 0.047 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.471 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:38
# Fork: 1 of 1
# Warmup Iteration   1: 18:09:32.517 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:32.557 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:32.626 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:32.628 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:32.646 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:32.647 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:32.661 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:32.662 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:32.706 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:32.879 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:32.879 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:32.885 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:32.885 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:32.892 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:32.893 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:32.912 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.174
18:09:32.912 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:32.916 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:32.922 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:32.924 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:32.926 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:32.927 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4f1fd805, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:33.125 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:33.162 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:33.192 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:33.262 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:33.263 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:33.264 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:33.264 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:33.300 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:33.316 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:33.325 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:33.370 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:33.538 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:33.539 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:33.539 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:33.539 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:33.720 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:09:33.721 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:33.876 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.174:37572 -> /10.1.0.174:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:33.880 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.174:8080 from NettyClient 10.1.0.174 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x10a56a8e, L:/10.1.0.174:37572 - R:/10.1.0.174:8080]], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:33.880 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.174 connect to the server /10.1.0.174:8080, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:33.918 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:33.920 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.174, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:09:33.939 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:33.940 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:33.949 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:33.950 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:34.013 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.174, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:09:34.082 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:09:34.083 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:34.085 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3154&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652574002&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:34.086 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3154&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652574002&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:34.103 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:09:34.103 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:34.113 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:34.123 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3154&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652574002&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:34.124 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:34.130 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.174
24.207 ±(99.9%) 0.753 ms/op
Iteration   1: 18:09:36.238 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:36.240 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-6] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x10a56a8e, L:/10.1.0.174:37572 - R:/10.1.0.174:8080], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:36.245 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:36.246 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:36.246 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:36.246 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-6] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:36.247 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-6] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:36.248 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-6] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:36.247 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.174:37572 -> /10.1.0.174:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:38.258 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-6] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3154&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652574002&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:38.258 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-6] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3154&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652574002&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:38.259 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:38.259 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:38.260 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-6] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:38.261 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-6] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:38.262 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:38.264 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:38.264 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:38.264 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:38.264 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:38.265 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:38.265 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-6] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:38.265 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-6] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:38.265 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:38.265 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:38.266 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:38.266 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-6] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:38.267 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-6] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:38.267 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-6] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:38.269 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-6] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4f1fd805, dubbo version: 3.2.7, current host: 10.1.0.174
17.012 ±(99.9%) 0.245 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.012 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:30
# Fork: 1 of 1
# Warmup Iteration   1: 18:09:40.167 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:40.199 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:40.263 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:40.264 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:40.286 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:40.287 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:40.312 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:40.313 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:40.353 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:40.527 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:40.528 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:40.538 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:40.538 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:40.547 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:40.561 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:40.580 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.174
18:09:40.580 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:40.584 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:40.586 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:40.587 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:40.589 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:40.589 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@6819b29b, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:40.781 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:40.810 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:40.848 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:40.923 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:40.927 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:40.929 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:40.930 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:40.962 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:40.969 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:40.975 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:41.031 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:41.196 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:41.197 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:41.199 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:41.200 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:41.368 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:09:41.368 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:41.534 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.174:8080 from NettyClient 10.1.0.174 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0xdae37309, L:/10.1.0.174:51260 - R:/10.1.0.174:8080]], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:41.534 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.174 connect to the server /10.1.0.174:8080, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:41.539 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.174:51260 -> /10.1.0.174:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:41.575 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:41.577 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.174, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:09:41.593 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:41.594 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:41.599 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:41.604 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:41.672 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.174, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:09:41.744 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:09:41.745 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:41.748 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3248&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652581661&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:41.748 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3248&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652581661&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:41.771 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:09:41.771 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:41.780 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:41.790 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3248&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652581661&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:41.791 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:41.797 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.174
10.316 ±(99.9%) 0.302 ms/op
Iteration   1: 18:09:44.035 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:44.040 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xdae37309, L:/10.1.0.174:51260 - R:/10.1.0.174:8080], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:44.041 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.174:51260 -> /10.1.0.174:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:44.047 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:44.047 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:44.047 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:44.048 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:44.048 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:44.049 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:46.058 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3248&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652581661&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:46.058 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3248&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652581661&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:46.058 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:46.059 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:46.060 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:46.061 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:46.062 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:46.064 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:46.065 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:46.065 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:46.065 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:46.065 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:46.065 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:46.065 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:46.065 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:46.066 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:46.066 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:46.066 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:46.068 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:46.068 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:46.074 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@6819b29b, dubbo version: 3.2.7, current host: 10.1.0.174
4.343 ±(99.9%) 0.104 ms/op
                 createUser·p0.00:   1.309 ms/op
                 createUser·p0.50:   3.568 ms/op
                 createUser·p0.90:   6.398 ms/op
                 createUser·p0.95:   9.978 ms/op
                 createUser·p0.99:   15.857 ms/op
                 createUser·p0.999:  26.049 ms/op
                 createUser·p0.9999: 29.426 ms/op
                 createUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 7516
  mean =      4.343 ±(99.9%) 0.104 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 537 
    [ 2.500,  5.000) = 5457 
    [ 5.000,  7.500) = 943 
    [ 7.500, 10.000) = 215 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.309 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      6.398 ms/op
     p(95.0000) =      9.978 ms/op
     p(99.0000) =     15.857 ms/op
     p(99.9000) =     26.049 ms/op
     p(99.9900) =     29.426 ms/op
     p(99.9990) =     29.426 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 18:09:48.094 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.117 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.182 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.184 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.210 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.212 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.226 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.227 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.277 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.450 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.450 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.454 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.455 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.459 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.460 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.477 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.478 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.481 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.487 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.487 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.489 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.489 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5253ce5c, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.693 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.726 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.787 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.845 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.847 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.848 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.848 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.868 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.874 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.878 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:48.921 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:49.086 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:49.086 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:49.088 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:49.088 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:49.267 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:09:49.268 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:49.436 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.174:8080 from NettyClient 10.1.0.174 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x8eb631d7, L:/10.1.0.174:45250 - R:/10.1.0.174:8080]], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:49.436 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.174 connect to the server /10.1.0.174:8080, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:49.441 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.174:45250 -> /10.1.0.174:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:49.477 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:49.479 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.174, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:09:49.495 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:49.495 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:49.500 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:49.502 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:49.570 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.174, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:09:49.618 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:09:49.619 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:49.644 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3343&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652589560&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:49.644 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3343&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652589560&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:49.659 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:09:49.659 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:49.671 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:49.681 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3343&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652589560&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:49.682 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:49.687 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.174
6.586 ±(99.9%) 0.205 ms/op
Iteration   1: 18:09:52.029 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:52.032 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-10] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x8eb631d7, L:/10.1.0.174:45250 - R:/10.1.0.174:8080], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:52.039 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:52.039 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:52.039 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:52.041 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-10] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:52.041 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.174:45250 -> /10.1.0.174:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:52.041 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-10] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:52.042 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-10] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:54.049 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-10] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3343&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652589560&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:54.050 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-10] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3343&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652589560&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:54.050 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:54.051 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:54.052 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-10] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:54.053 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-10] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:54.056 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:54.057 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:54.057 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:54.057 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:54.057 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:54.058 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:54.058 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-10] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:54.059 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-10] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:54.061 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:54.062 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:54.062 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:54.063 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-10] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:54.065 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-10] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:54.065 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-10] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:54.068 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-10] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5253ce5c, dubbo version: 3.2.7, current host: 10.1.0.174
2.571 ±(99.9%) 0.055 ms/op
                 existUser·p0.00:   0.674 ms/op
                 existUser·p0.50:   2.076 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   5.083 ms/op
                 existUser·p0.99:   10.142 ms/op
                 existUser·p0.999:  22.363 ms/op
                 existUser·p0.9999: 34.279 ms/op
                 existUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 12604
  mean =      2.571 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9263 
    [ 2.500,  5.000) = 2700 
    [ 5.000,  7.500) = 420 
    [ 7.500, 10.000) = 85 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      2.076 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      5.083 ms/op
     p(99.0000) =     10.142 ms/op
     p(99.9000) =     22.363 ms/op
     p(99.9900) =     34.279 ms/op
     p(99.9990) =     34.603 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 18:09:56.070 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.094 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.157 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.159 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.178 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.179 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.191 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.192 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.243 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.431 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.431 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.438 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.439 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.447 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.449 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.464 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.464 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.469 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.474 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.476 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.478 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.478 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@ddd5c91, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.684 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.728 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.762 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.823 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.825 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.825 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.826 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.845 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.853 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.863 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:56.918 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:57.062 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:57.063 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:57.063 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:57.064 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:57.253 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:09:57.253 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:57.396 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.174:8080 from NettyClient 10.1.0.174 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0x0f1282d2, L:/10.1.0.174:45256 - R:/10.1.0.174:8080]], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:57.396 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.174 connect to the server /10.1.0.174:8080, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:57.398 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.174:45256 -> /10.1.0.174:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:57.434 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:57.436 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.174, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:09:57.451 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:57.451 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:57.458 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:57.460 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:57.523 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.174, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:09:57.595 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:09:57.596 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:57.603 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3440&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652597517&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:57.603 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3440&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652597517&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:57.627 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:09:57.627 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:57.635 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:57.644 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3440&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652597517&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:57.645 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:57.650 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.174
8.891 ±(99.9%) 0.264 ms/op
Iteration   1: 18:09:59.933 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:59.935 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x0f1282d2, L:/10.1.0.174:45256 - R:/10.1.0.174:8080], dubbo version: 3.2.7, current host: 10.1.0.174
18:09:59.943 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:59.944 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:59.944 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:59.945 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:09:59.945 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:59.946 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:09:59.945 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.174:45256 -> /10.1.0.174:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:01.966 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3440&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652597517&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:01.966 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3440&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652597517&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:01.967 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:01.967 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:01.968 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.174
18:10:01.969 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:01.971 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:01.972 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.174
18:10:01.972 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:01.972 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:01.972 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:01.972 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:01.973 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.174
18:10:01.973 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:01.973 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:01.974 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:01.974 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:01.974 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:01.975 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:01.976 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:01.980 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-20] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@ddd5c91, dubbo version: 3.2.7, current host: 10.1.0.174
3.586 ±(99.9%) 0.060 ms/op
                 getUser·p0.00:   0.808 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   5.362 ms/op
                 getUser·p0.99:   11.649 ms/op
                 getUser·p0.999:  24.478 ms/op
                 getUser·p0.9999: 39.715 ms/op
                 getUser·p1.00:   39.715 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 8909
  mean =      3.586 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 960 
    [ 2.500,  5.000) = 7316 
    [ 5.000,  7.500) = 433 
    [ 7.500, 10.000) = 95 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      5.362 ms/op
     p(99.0000) =     11.649 ms/op
     p(99.9000) =     24.478 ms/op
     p(99.9900) =     39.715 ms/op
     p(99.9990) =     39.715 ms/op
     p(99.9999) =     39.715 ms/op
    p(100.0000) =     39.715 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 18:10:03.977 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.005 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Creating global shared handler ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.077 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.079 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.099 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.100 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.127 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityManager -  [DUBBO] Serialize check serializable: true, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.128 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.192 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.384 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.385 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.390 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.391 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.394 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.394 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.402 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.402 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.404 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.406 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize allow list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.allowlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.407 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.u.SerializeSecurityConfigurator -  [DUBBO] Read serialize blocked list from jar:file:/home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.2.7.jar!/security/serialize.blockedlist, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.422 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.423 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@32527548, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.605 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor -  [DUBBO] class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.641 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] loading dubbo config beans ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.695 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer -  [DUBBO] dubbo config beans are loaded., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.769 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] The current configurations or effective configurations are as follows:, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.770 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:application enableFileCache="true" executorManagementMode="isolation" parameters="{}" name="dubbo-hessianlite-client" protocol="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.771 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:protocol preferSerialization="fastjson2,hessian2" name="dubbo" />, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.774 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.config.context.ConfigManager -  [DUBBO] <dubbo:ssl />, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.805 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.811 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.819 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:04.862 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator -  [DUBBO] The configBean[type:ReferenceConfig<org.apache.dubbo.benchmark.service.UserService>] has been built., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:05.035 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:05.035 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:05.037 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:05.038 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:05.204 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:10:05.205 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:05.386 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.174:8080 from NettyClient 10.1.0.174 using dubbo version 3.2.7, channel is NettyChannel [channel=[id: 0xad976361, L:/10.1.0.174:51134 - R:/10.1.0.174:8080]], dubbo version: 3.2.7, current host: 10.1.0.174
18:10:05.386 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.174 connect to the server /10.1.0.174:8080, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:05.390 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.174:51134 -> /10.1.0.174:8080 is established., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:05.421 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:05.423 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.2.7, current host: 10.1.0.174, error code: 1-39. This may be caused by , go to https://dubbo.apache.org/faq/1/39 to find instructions. 
18:10:05.432 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:05.433 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultMetricsServiceExporter -  [DUBBO] The MetricsConfig not exist, will not export metrics service., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:05.439 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] org.apache.dubbo.metadata.MetadataServiceService Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:05.441 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.b.b.InternalServiceConfigBuilder -  [DUBBO] Using dubbo protocol to export org.apache.dubbo.metadata.MetadataService service on port -1, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:05.515 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.2.7, current host: 10.1.0.174, error code: 5-8. This may be caused by , go to https://dubbo.apache.org/faq/5/8 to find instructions. 
18:10:05.561 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:10:05.562 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:05.575 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3534&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652605498&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:05.575 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3534&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652605498&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:05.595 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.2.7, current host: 10.1.0.174, error code: 7-4. This may be caused by , go to https://dubbo.apache.org/faq/7/4 to find instructions. 
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
18:10:05.595 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:05.608 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:05.618 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3534&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652605498&version=1.0.0], dubbo version: 3.2.7, current host: 10.1.0.174
18:10:05.618 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:05.624 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.2.7, current host: 10.1.0.174
26.671 ±(99.9%) 1.310 ms/op
Iteration   1: 18:10:07.808 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:07.811 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xad976361, L:/10.1.0.174:51134 - R:/10.1.0.174:8080], dubbo version: 3.2.7, current host: 10.1.0.174
18:10:07.813 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.174:51134 -> /10.1.0.174:8080 is disconnected., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:07.819 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:07.819 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:07.819 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:07.820 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:07.820 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:07.821 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.174:20880, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:09.832 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.174:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3534&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652605498&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:09.832 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.174&bind.port=20880&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executor-management-mode=isolation&exporter.listener=injvm&file-cache=true&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=exportInstanceMetadata,getAndListenInstanceMetadata,getExportedServiceURLs,getExportedURLs,getInstanceMetadataChangedListenerMap,getMetadataInfo,getMetadataInfos,getMetadataURL,getServiceDefinition,getSubscribedURLs,isMetadataService,serviceName,toSortedStrings,version&pid=3534&prefer.serialization=fastjson2,hessian2&register=false&release=3.2.7&revision=3.2.7&service.filter=-default&side=provider&timestamp=1697652605498&version=1.0.0, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:09.832 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:09.833 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:09.834 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.174
18:10:09.835 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:09.836 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:09.836 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.2.7, current host: 10.1.0.174
18:10:09.836 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:09.837 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:09.837 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:09.837 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:09.837 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.2.7, current host: 10.1.0.174
18:10:09.837 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:09.837 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:09.838 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:09.838 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:09.838 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:09.840 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.2.7, current host: 10.1.0.174
18:10:09.841 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.2.7, current host: 10.1.0.174
18:10:09.843 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-5] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@32527548, dubbo version: 3.2.7, current host: 10.1.0.174
13.883 ±(99.9%) 0.344 ms/op
                 listUser·p0.00:   3.924 ms/op
                 listUser·p0.50:   13.238 ms/op
                 listUser·p0.90:   19.497 ms/op
                 listUser·p0.95:   21.868 ms/op
                 listUser·p0.99:   28.183 ms/op
                 listUser·p0.999:  64.513 ms/op
                 listUser·p0.9999: 117.047 ms/op
                 listUser·p1.00:   117.047 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2292
  mean =     13.883 ±(99.9%) 0.344 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 952 
    [ 12.500,  25.000) = 1289 
    [ 25.000,  37.500) = 48 
    [ 37.500,  50.000) = 0 
    [ 50.000,  62.500) = 1 
    [ 62.500,  75.000) = 1 
    [ 75.000,  87.500) = 0 
    [ 87.500, 100.000) = 0 
    [100.000, 112.500) = 0 
    [112.500, 125.000) = 1 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.924 ms/op
     p(50.0000) =     13.238 ms/op
     p(90.0000) =     19.497 ms/op
     p(95.0000) =     21.868 ms/op
     p(99.0000) =     28.183 ms/op
     p(99.9000) =     64.513 ms/op
     p(99.9900) =    117.047 ms/op
     p(99.9990) =    117.047 ms/op
     p(99.9999) =    117.047 ms/op
    p(100.0000) =    117.047 ms/op


# Run complete. Total time: 00:01:32

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt    Score   Error   Units
Client.createUser                      thrpt           2.908          ops/ms
Client.existUser                       thrpt           9.089          ops/ms
Client.getUser                         thrpt           5.352          ops/ms
Client.listUser                        thrpt           1.202          ops/ms
Client.createUser                       avgt           5.590           ms/op
Client.existUser                        avgt           2.765           ms/op
Client.getUser                          avgt           4.471           ms/op
Client.listUser                         avgt          17.012           ms/op
Client.createUser                     sample   7516    4.343 ± 0.104   ms/op
Client.createUser:createUser·p0.00    sample           1.309           ms/op
Client.createUser:createUser·p0.50    sample           3.568           ms/op
Client.createUser:createUser·p0.90    sample           6.398           ms/op
Client.createUser:createUser·p0.95    sample           9.978           ms/op
Client.createUser:createUser·p0.99    sample          15.857           ms/op
Client.createUser:createUser·p0.999   sample          26.049           ms/op
Client.createUser:createUser·p0.9999  sample          29.426           ms/op
Client.createUser:createUser·p1.00    sample          29.426           ms/op
Client.existUser                      sample  12604    2.571 ± 0.055   ms/op
Client.existUser:existUser·p0.00      sample           0.674           ms/op
Client.existUser:existUser·p0.50      sample           2.076           ms/op
Client.existUser:existUser·p0.90      sample           3.408           ms/op
Client.existUser:existUser·p0.95      sample           5.083           ms/op
Client.existUser:existUser·p0.99      sample          10.142           ms/op
Client.existUser:existUser·p0.999     sample          22.363           ms/op
Client.existUser:existUser·p0.9999    sample          34.279           ms/op
Client.existUser:existUser·p1.00      sample          34.603           ms/op
Client.getUser                        sample   8909    3.586 ± 0.060   ms/op
Client.getUser:getUser·p0.00          sample           0.808           ms/op
Client.getUser:getUser·p0.50          sample           3.363           ms/op
Client.getUser:getUser·p0.90          sample           4.522           ms/op
Client.getUser:getUser·p0.95          sample           5.362           ms/op
Client.getUser:getUser·p0.99          sample          11.649           ms/op
Client.getUser:getUser·p0.999         sample          24.478           ms/op
Client.getUser:getUser·p0.9999        sample          39.715           ms/op
Client.getUser:getUser·p1.00          sample          39.715           ms/op
Client.listUser                       sample   2292   13.883 ± 0.344   ms/op
Client.listUser:listUser·p0.00        sample           3.924           ms/op
Client.listUser:listUser·p0.50        sample          13.238           ms/op
Client.listUser:listUser·p0.90        sample          19.497           ms/op
Client.listUser:listUser·p0.95        sample          21.868           ms/op
Client.listUser:listUser·p0.99        sample          28.183           ms/op
Client.listUser:listUser·p0.999       sample          64.513           ms/op
Client.listUser:listUser·p0.9999      sample         117.047           ms/op
Client.listUser:listUser·p1.00        sample         117.047           ms/op
```
