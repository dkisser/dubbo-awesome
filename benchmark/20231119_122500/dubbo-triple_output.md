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
[INFO] benchmark-base ..................................... SUCCESS [  2.883 s]
[INFO] server-base ........................................ SUCCESS [  0.291 s]
[INFO] client-base ........................................ SUCCESS [  0.623 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.514 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  4.614 s
[INFO] Finished at: 2023-11-19T12:11:23Z
[INFO] ------------------------------------------------------------------------

RUN dubbo-triple-client IN benchmark MODE
command is: java -server -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output= -jar dubbo-triple-client/target/dubbo-triple-client-1.0-SNAPSHOT.jar --warmupIterations=1 --warmupTime=1 --measurementIterations=1 --measurementTime=1

# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 12:11:24.876 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.71
12:11:24.879 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:11:24.925 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:11:24.926 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:11:24.941 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:11:24.942 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:11:24.981 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.71
12:11:24.981 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:11:24.981 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:11:24.988 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:11:24.988 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:11:24.996 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.71
12:11:24.997 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:11:25.000 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:11:25.002 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.71
12:11:25.003 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@2e93a229, dubbo version: 3.1.0, current host: 10.1.0.71
12:11:25.152 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:11:25.185 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:11:25.203 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:11:25.289 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:11:25.297 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:11:25.298 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:11:25.451 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:11:25.466 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:11:25.466 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:11:25.466 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:11:25.467 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.71
12:11:25.483 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.71
12:11:25.552 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:11:25.690 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.71
12:11:25.691 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.71
12:11:25.698 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.71
12:11:25.702 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.71
12:11:25.704 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.71
12:11:25.746 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.71
12:11:25.780 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:11:25.782 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2285&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700395885737&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:11:25.782 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2285&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700395885737&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:11:25.783 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:11:25.841 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:11:25.843 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2285&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700395885737&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.71
12:11:25.843 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.71
12:11:25.848 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.71
4.467 ops/ms
# Warmup Iteration   2: 11.848 ops/ms
# Warmup Iteration   3: 12.132 ops/ms
Iteration   1: 12.348 ops/ms
Iteration   2: 12.467 ops/ms
Iteration   3: 12:12:25.923 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:12:25.927 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:12:25.928 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.71
12:12:25.929 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:12:25.929 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.71
12:12:25.930 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:12:25.931 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:12:25.932 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:12:27.937 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2285&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700395885737&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:12:27.938 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:12:27.938 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2285&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700395885737&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:12:27.938 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:12:27.938 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:12:27.939 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:12:27.939 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:12:27.939 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:12:27.940 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:12:27.943 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:12:27.944 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.71
12:12:27.944 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:12:27.945 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:12:27.945 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.71
12:12:27.945 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:12:27.945 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:12:27.946 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:12:27.946 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:12:27.947 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.71
12:12:27.947 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.71
12:12:27.947 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:12:27.950 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.71
12:12:27.951 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:12:27.955 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-5] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@2e93a229, dubbo version: 3.1.0, current host: 10.1.0.71
12.547 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.454 ±(99.9%) 1.832 ops/ms [Average]
  (min, avg, max) = (12.348, 12.454, 12.547), stdev = 0.100
  CI (99.9%): [10.622, 14.286] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 12:12:29.660 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.71
12:12:29.664 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:12:29.706 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:12:29.707 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:12:29.722 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:12:29.723 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:12:29.759 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.71
12:12:29.760 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:12:29.760 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:12:29.764 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:12:29.764 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:12:29.772 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.71
12:12:29.773 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:12:29.776 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:12:29.778 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.71
12:12:29.779 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5b84cd9e, dubbo version: 3.1.0, current host: 10.1.0.71
12:12:29.924 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:12:29.958 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:12:29.976 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:12:30.061 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:12:30.068 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:12:30.068 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:12:30.225 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:12:30.241 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:12:30.241 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:12:30.241 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:12:30.242 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.71
12:12:30.258 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.71
12:12:30.325 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:12:30.441 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.71
12:12:30.442 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.71
12:12:30.449 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.71
12:12:30.453 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.71
12:12:30.455 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.71
12:12:30.492 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.71
12:12:30.526 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:12:30.528 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2800&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700395950485&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:12:30.529 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2800&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700395950485&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:12:30.529 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:12:30.599 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:12:30.600 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2800&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700395950485&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.71
12:12:30.601 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.71
12:12:30.607 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-3] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.71
7.733 ops/ms
# Warmup Iteration   2: 12.887 ops/ms
# Warmup Iteration   3: 12.949 ops/ms
Iteration   1: 12.897 ops/ms
Iteration   2: 12.868 ops/ms
Iteration   3: 12:13:30.672 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:13:30.675 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:13:30.676 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.71
12:13:30.676 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:13:30.676 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.71
12:13:30.678 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:13:30.678 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:13:30.679 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:13:32.685 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2800&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700395950485&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:13:32.686 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:13:32.686 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2800&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700395950485&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:13:32.686 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:13:32.686 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:13:32.687 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:13:32.687 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:13:32.687 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:13:32.688 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:13:32.692 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:13:32.692 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.71
12:13:32.692 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:13:32.693 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:13:32.693 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.71
12:13:32.693 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:13:32.693 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:13:32.694 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:13:32.694 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:13:32.698 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.71
12:13:32.698 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.71
12:13:32.698 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:13:32.703 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.71
12:13:32.703 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:13:32.705 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-30] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5b84cd9e, dubbo version: 3.1.0, current host: 10.1.0.71
13.016 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.927 ±(99.9%) 1.424 ops/ms [Average]
  (min, avg, max) = (12.868, 12.927, 13.016), stdev = 0.078
  CI (99.9%): [11.503, 14.352] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 12:13:34.383 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.71
12:13:34.386 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:13:34.425 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:13:34.426 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:13:34.442 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:13:34.443 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:13:34.480 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.71
12:13:34.481 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:13:34.481 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:13:34.486 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:13:34.486 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:13:34.495 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.71
12:13:34.495 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:13:34.498 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:13:34.500 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.71
12:13:34.501 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@18522276, dubbo version: 3.1.0, current host: 10.1.0.71
12:13:34.650 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:13:34.682 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:13:34.699 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:13:34.792 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:13:34.800 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:13:34.800 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:13:34.952 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:13:34.967 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:13:34.967 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:13:34.967 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:13:34.968 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.71
12:13:34.986 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.71
12:13:35.059 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:13:35.179 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.71
12:13:35.181 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.71
12:13:35.195 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.71
12:13:35.200 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.71
12:13:35.202 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.71
12:13:35.231 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.71
12:13:35.268 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:13:35.270 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3103&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396015225&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:13:35.270 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3103&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396015225&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:13:35.271 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:13:35.341 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:13:35.343 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3103&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396015225&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.71
12:13:35.344 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.71
12:13:35.349 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.71
7.652 ops/ms
# Warmup Iteration   2: 12.214 ops/ms
# Warmup Iteration   3: 12.471 ops/ms
Iteration   1: 12.617 ops/ms
Iteration   2: 12.636 ops/ms
Iteration   3: 12:14:35.425 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:14:35.428 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:14:35.429 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.71
12:14:35.430 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:14:35.430 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.71
12:14:35.432 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:14:35.432 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:14:35.433 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:14:37.440 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3103&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396015225&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:14:37.441 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:14:37.441 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3103&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396015225&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:14:37.441 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:14:37.441 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:14:37.442 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:14:37.442 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:14:37.442 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:14:37.443 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:14:37.447 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:14:37.448 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.71
12:14:37.448 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:14:37.449 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:14:37.449 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.71
12:14:37.449 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:14:37.449 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:14:37.450 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:14:37.450 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:14:37.450 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.71
12:14:37.451 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.71
12:14:37.451 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:14:37.455 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.71
12:14:37.455 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:14:37.456 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-26] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@18522276, dubbo version: 3.1.0, current host: 10.1.0.71
12.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.582 ±(99.9%) 1.402 ops/ms [Average]
  (min, avg, max) = (12.494, 12.582, 12.636), stdev = 0.077
  CI (99.9%): [11.180, 13.985] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 12:14:40.084 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.087 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.126 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.127 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.143 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.144 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.183 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.183 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.183 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.188 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.188 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.196 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.197 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.200 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.203 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.203 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@7da3060f, dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.353 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:14:40.386 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:14:40.404 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:14:40.490 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.498 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.498 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.647 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:14:40.662 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.662 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.663 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.663 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.680 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.752 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.873 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.874 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.883 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.889 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.892 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.933 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.966 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.970 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3413&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396080925&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.970 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3413&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396080925&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:14:40.971 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:14:41.039 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:14:41.040 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3413&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396080925&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.71
12:14:41.041 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.71
12:14:41.046 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-4] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.71
6.780 ops/ms
# Warmup Iteration   2: 10.406 ops/ms
# Warmup Iteration   3: 10.395 ops/ms
Iteration   1: 10.434 ops/ms
Iteration   2: 10.619 ops/ms
Iteration   3: 12:15:41.116 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:15:41.119 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:15:41.120 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.71
12:15:41.120 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:15:41.120 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.71
12:15:41.122 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:15:41.122 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:15:41.123 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:15:43.129 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3413&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396080925&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:15:43.130 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:15:43.130 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3413&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396080925&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:15:43.130 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:15:43.130 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:15:43.131 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:15:43.131 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:15:43.131 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:15:43.132 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:15:43.140 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:15:43.141 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.71
12:15:43.142 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:15:43.142 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:15:43.142 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.71
12:15:43.142 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:15:43.142 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:15:43.143 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:15:43.143 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:15:43.144 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.71
12:15:43.144 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.71
12:15:43.144 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:15:43.148 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.71
12:15:43.148 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:15:43.150 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-16] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@7da3060f, dubbo version: 3.1.0, current host: 10.1.0.71
10.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.529 ±(99.9%) 1.687 ops/ms [Average]
  (min, avg, max) = (10.434, 10.529, 10.619), stdev = 0.092
  CI (99.9%): [8.842, 12.215] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 12:15:45.769 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.71
12:15:45.772 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:15:45.814 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:15:45.816 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:15:45.831 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:15:45.832 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:15:45.868 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.71
12:15:45.868 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:15:45.868 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:15:45.873 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:15:45.873 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:15:45.881 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.71
12:15:45.881 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:15:45.884 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:15:45.887 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.71
12:15:45.887 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@2e93a229, dubbo version: 3.1.0, current host: 10.1.0.71
12:15:46.035 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:15:46.071 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:15:46.089 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:15:46.179 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:15:46.187 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:15:46.187 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:15:46.337 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:15:46.352 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:15:46.353 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:15:46.353 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:15:46.354 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.71
12:15:46.373 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.71
12:15:46.452 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:15:46.576 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.71
12:15:46.577 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.71
12:15:46.586 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.71
12:15:46.590 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.71
12:15:46.592 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.71
12:15:46.621 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.71
12:15:46.654 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:15:46.656 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3730&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396146614&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:15:46.656 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3730&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396146614&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:15:46.657 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:15:46.716 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:15:46.717 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3730&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396146614&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.71
12:15:46.718 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.71
12:15:46.722 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.71
4.129 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.636 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.552 ±(99.9%) 0.005 ms/op
Iteration   1: 2.572 ±(99.9%) 0.004 ms/op
Iteration   2: 2.570 ±(99.9%) 0.005 ms/op
Iteration   3: 12:16:46.791 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:16:46.795 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:16:46.795 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.71
12:16:46.796 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:16:46.796 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.71
12:16:46.797 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:16:46.797 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:16:46.798 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:16:48.804 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3730&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396146614&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:16:48.804 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:16:48.804 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3730&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396146614&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:16:48.805 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:16:48.805 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:16:48.805 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:16:48.805 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:16:48.806 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:16:48.806 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:16:48.810 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:16:48.812 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.71
12:16:48.812 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:16:48.812 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:16:48.813 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.71
12:16:48.813 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:16:48.813 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:16:48.814 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:16:48.814 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:16:48.815 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.71
12:16:48.815 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.71
12:16:48.815 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:16:48.821 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.71
12:16:48.821 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:16:48.824 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-6] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@2e93a229, dubbo version: 3.1.0, current host: 10.1.0.71
2.515 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.552 ±(99.9%) 0.585 ms/op [Average]
  (min, avg, max) = (2.515, 2.552, 2.572), stdev = 0.032
  CI (99.9%): [1.967, 3.138] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 12:16:50.526 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.71
12:16:50.529 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:16:50.572 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:16:50.573 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:16:50.588 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:16:50.588 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:16:50.624 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.71
12:16:50.625 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:16:50.625 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:16:50.629 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:16:50.630 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:16:50.638 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.71
12:16:50.638 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:16:50.640 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:16:50.643 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.71
12:16:50.644 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@967fed3, dubbo version: 3.1.0, current host: 10.1.0.71
12:16:50.802 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:16:50.836 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:16:50.854 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:16:50.948 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:16:50.956 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:16:50.956 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:16:51.102 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:16:51.117 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:16:51.118 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:16:51.118 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:16:51.118 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.71
12:16:51.136 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.71
12:16:51.208 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:16:51.324 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.71
12:16:51.325 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.71
12:16:51.340 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.71
12:16:51.345 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.71
12:16:51.348 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.71
12:16:51.379 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.71
12:16:51.413 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:16:51.415 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4028&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396211371&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:16:51.416 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4028&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396211371&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:16:51.416 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:16:51.486 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:16:51.488 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4028&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396211371&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.71
12:16:51.488 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.71
12:16:51.494 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.71
3.689 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.515 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.004 ms/op
Iteration   1: 2.488 ±(99.9%) 0.004 ms/op
Iteration   2: 2.489 ±(99.9%) 0.003 ms/op
Iteration   3: 12:17:51.565 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:17:51.568 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:17:51.569 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.71
12:17:51.570 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:17:51.570 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.71
12:17:51.571 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:17:51.571 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:17:51.572 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:17:53.578 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4028&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396211371&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:17:53.578 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:17:53.578 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4028&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396211371&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:17:53.579 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:17:53.579 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:17:53.579 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:17:53.579 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:17:53.580 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:17:53.580 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:17:53.589 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:17:53.591 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.71
12:17:53.592 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:17:53.592 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:17:53.592 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.71
12:17:53.592 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:17:53.592 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:17:53.593 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:17:53.593 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:17:53.594 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.71
12:17:53.594 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.71
12:17:53.594 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:17:53.597 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.71
12:17:53.597 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:17:53.599 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-20] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@967fed3, dubbo version: 3.1.0, current host: 10.1.0.71
2.502 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.493 ±(99.9%) 0.142 ms/op [Average]
  (min, avg, max) = (2.488, 2.493, 2.502), stdev = 0.008
  CI (99.9%): [2.351, 2.635] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 12:17:55.286 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.71
12:17:55.289 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:17:55.328 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:17:55.329 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:17:55.344 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:17:55.344 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:17:55.380 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.71
12:17:55.380 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:17:55.380 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:17:55.384 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:17:55.384 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:17:55.392 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.71
12:17:55.392 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:17:55.395 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:17:55.400 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.71
12:17:55.400 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@18522276, dubbo version: 3.1.0, current host: 10.1.0.71
12:17:55.553 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:17:55.587 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:17:55.604 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:17:55.691 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:17:55.698 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:17:55.698 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:17:55.845 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:17:55.860 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:17:55.860 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:17:55.860 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:17:55.861 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.71
12:17:55.878 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.71
12:17:55.950 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:17:56.084 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.71
12:17:56.086 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.71
12:17:56.094 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.71
12:17:56.099 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.71
12:17:56.102 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.71
12:17:56.140 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.71
12:17:56.174 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:17:56.176 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4330&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396276133&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:17:56.176 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4330&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396276133&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:17:56.177 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:17:56.239 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:17:56.241 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4330&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396276133&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.71
12:17:56.242 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.71
12:17:56.247 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.71
4.006 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.580 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.557 ±(99.9%) 0.003 ms/op
Iteration   1: 2.534 ±(99.9%) 0.004 ms/op
Iteration   2: 2.518 ±(99.9%) 0.003 ms/op
Iteration   3: 12:18:56.311 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:18:56.315 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:18:56.316 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.71
12:18:56.316 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:18:56.316 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.71
12:18:56.317 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:18:56.317 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:18:56.318 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:18:58.324 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4330&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396276133&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:18:58.325 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:18:58.325 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4330&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396276133&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:18:58.325 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:18:58.325 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:18:58.326 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:18:58.326 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:18:58.326 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:18:58.327 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:18:58.336 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:18:58.337 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.71
12:18:58.338 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:18:58.338 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:18:58.338 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.71
12:18:58.338 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:18:58.338 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:18:58.339 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:18:58.339 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:18:58.340 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.71
12:18:58.340 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.71
12:18:58.340 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:18:58.342 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.71
12:18:58.342 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:18:58.344 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-5] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@18522276, dubbo version: 3.1.0, current host: 10.1.0.71
2.545 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.532 ±(99.9%) 0.245 ms/op [Average]
  (min, avg, max) = (2.518, 2.532, 2.545), stdev = 0.013
  CI (99.9%): [2.287, 2.777] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 12:19:00.057 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.060 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.103 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.104 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.120 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.121 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.162 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.162 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.162 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.167 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.168 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.176 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.176 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.179 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.182 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.182 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@7dcaef4e, dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.328 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:19:00.361 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:19:00.379 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:19:00.466 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.473 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.474 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.625 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:19:00.641 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.641 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.641 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.641 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.660 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.729 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.844 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.845 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.860 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.864 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.866 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.896 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.931 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.933 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4627&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396340888&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.933 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4627&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396340888&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:19:00.934 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:19:01.005 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:19:01.007 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4627&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396340888&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.71
12:19:01.007 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.71
12:19:01.013 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-7] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.71
4.795 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.006 ms/op
Iteration   1: 3.028 ±(99.9%) 0.005 ms/op
Iteration   2: 3.032 ±(99.9%) 0.005 ms/op
Iteration   3: 12:20:01.087 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:20:01.090 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:20:01.092 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.71
12:20:01.092 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:20:01.092 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.71
12:20:01.093 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:20:01.093 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:20:01.094 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:20:03.100 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4627&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396340888&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:20:03.100 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:20:03.100 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4627&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396340888&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:20:03.100 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:20:03.100 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:20:03.101 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:20:03.101 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:20:03.101 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:20:03.102 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:20:03.111 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:20:03.111 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.71
12:20:03.112 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:20:03.112 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:20:03.112 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.71
12:20:03.112 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:20:03.112 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:20:03.113 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:20:03.113 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:20:03.114 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.71
12:20:03.114 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.71
12:20:03.114 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:20:03.119 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.71
12:20:03.119 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:20:03.121 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-17] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@7dcaef4e, dubbo version: 3.1.0, current host: 10.1.0.71
3.014 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.025 ±(99.9%) 0.181 ms/op [Average]
  (min, avg, max) = (3.014, 3.025, 3.032), stdev = 0.010
  CI (99.9%): [2.844, 3.205] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 12:20:04.794 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.71
12:20:04.797 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:20:04.839 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:20:04.841 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:20:04.856 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:20:04.857 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:20:04.895 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.71
12:20:04.895 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:20:04.895 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:20:04.900 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:20:04.900 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:20:04.908 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.71
12:20:04.908 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:20:04.911 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:20:04.914 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.71
12:20:04.914 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4b7aba56, dubbo version: 3.1.0, current host: 10.1.0.71
12:20:05.070 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:20:05.103 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:20:05.120 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:20:05.213 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:20:05.220 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:20:05.221 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:20:05.372 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:20:05.387 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:20:05.388 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:20:05.388 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:20:05.388 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.71
12:20:05.403 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.71
12:20:05.475 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:20:05.616 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.71
12:20:05.617 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.71
12:20:05.625 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.71
12:20:05.629 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.71
12:20:05.631 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.71
12:20:05.663 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.71
12:20:05.696 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:20:05.699 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4925&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396405656&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:20:05.699 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4925&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396405656&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:20:05.700 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:20:05.760 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:20:05.761 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4925&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396405656&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.71
12:20:05.762 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.71
12:20:05.767 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.71
4.134 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.651 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.551 ±(99.9%) 0.006 ms/op
Iteration   1: 2.543 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.929 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.789 ms/op
                 createUser·p0.999:  12.222 ms/op
                 createUser·p0.9999: 14.254 ms/op
                 createUser·p1.00:   16.630 ms/op

Iteration   2: 2.564 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.829 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.777 ms/op
                 createUser·p0.999:  9.752 ms/op
                 createUser·p0.9999: 12.567 ms/op
                 createUser·p1.00:   13.304 ms/op

Iteration   3: 12:21:06.054 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:21:06.057 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:21:06.058 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.71
12:21:06.059 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:21:06.059 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.71
12:21:06.060 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:21:06.060 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:21:06.061 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:21:08.068 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4925&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396405656&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:21:08.068 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:21:08.069 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=4925&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396405656&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:21:08.069 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:21:08.069 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:21:08.070 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:21:08.070 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:21:08.070 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:21:08.071 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:21:08.082 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:21:08.083 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.71
12:21:08.084 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:21:08.084 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:21:08.084 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.71
12:21:08.084 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:21:08.084 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:21:08.085 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:21:08.085 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:21:08.085 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.71
12:21:08.085 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.71
12:21:08.086 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:21:08.088 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.71
12:21:08.089 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:21:08.090 [org.apache.dubbo.benchmark.ClientPb.createUser-jmh-worker-9] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4b7aba56, dubbo version: 3.1.0, current host: 10.1.0.71
2.568 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.876 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   4.080 ms/op
                 createUser·p0.999:  8.495 ms/op
                 createUser·p0.9999: 11.108 ms/op
                 createUser·p1.00:   11.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374909
  mean =      2.558 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 177122 
    [ 2.500,  3.750) = 193082 
    [ 3.750,  5.000) = 3744 
    [ 5.000,  6.250) = 451 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      3.875 ms/op
     p(99.9000) =      8.832 ms/op
     p(99.9900) =     13.779 ms/op
     p(99.9990) =     14.692 ms/op
     p(99.9999) =     16.630 ms/op
    p(100.0000) =     16.630 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 12:21:09.830 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.71
12:21:09.833 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:21:09.874 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:21:09.875 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:21:09.891 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:21:09.891 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:21:09.928 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.71
12:21:09.928 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:21:09.928 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:21:09.933 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:21:09.933 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:21:09.941 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.71
12:21:09.941 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:21:09.944 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:21:09.947 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.71
12:21:09.947 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@505421f5, dubbo version: 3.1.0, current host: 10.1.0.71
12:21:10.094 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:21:10.128 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:21:10.146 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:21:10.230 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:21:10.238 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:21:10.238 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:21:10.388 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:21:10.403 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:21:10.403 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:21:10.403 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:21:10.404 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.71
12:21:10.420 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.71
12:21:10.489 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:21:10.607 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.71
12:21:10.609 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.71
12:21:10.624 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.71
12:21:10.630 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.71
12:21:10.633 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.71
12:21:10.664 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.71
12:21:10.697 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:21:10.698 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5218&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396470657&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:21:10.699 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5218&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396470657&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:21:10.699 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:21:10.771 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:21:10.772 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5218&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396470657&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.71
12:21:10.773 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.71
12:21:10.779 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-6] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.71
3.692 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.485 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.431 ±(99.9%) 0.005 ms/op
Iteration   1: 2.461 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.118 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.936 ms/op
                 existUser·p0.999:  6.592 ms/op
                 existUser·p0.9999: 13.681 ms/op
                 existUser·p1.00:   14.090 ms/op

Iteration   2: 2.438 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.094 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.584 ms/op
                 existUser·p0.999:  6.636 ms/op
                 existUser·p0.9999: 14.596 ms/op
                 existUser·p1.00:   15.008 ms/op

Iteration   3: 12:22:11.095 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:22:11.098 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:22:11.099 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.71
12:22:11.100 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:22:11.100 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.71
12:22:11.101 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:22:11.102 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:22:11.103 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:22:13.109 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5218&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396470657&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:22:13.109 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:22:13.109 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5218&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396470657&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:22:13.110 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:22:13.110 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:22:13.110 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:22:13.110 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:22:13.111 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:22:13.111 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:22:13.122 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:22:13.123 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.71
12:22:13.123 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:22:13.124 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:22:13.124 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.71
12:22:13.124 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:22:13.124 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:22:13.124 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:22:13.125 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:22:13.125 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.71
12:22:13.125 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.71
12:22:13.125 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:22:13.129 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.71
12:22:13.129 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:22:13.130 [org.apache.dubbo.benchmark.ClientPb.existUser-jmh-worker-23] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@505421f5, dubbo version: 3.1.0, current host: 10.1.0.71
2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.889 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.875 ms/op
                 existUser·p0.999:  8.086 ms/op
                 existUser·p0.9999: 11.615 ms/op
                 existUser·p1.00:   12.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391326
  mean =      2.451 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 191784 
    [ 2.500,  3.750) = 195234 
    [ 3.750,  5.000) = 3314 
    [ 5.000,  6.250) = 517 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.889 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      7.067 ms/op
     p(99.9900) =     13.746 ms/op
     p(99.9990) =     14.778 ms/op
     p(99.9999) =     15.008 ms/op
    p(100.0000) =     15.008 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 12:22:14.863 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.71
12:22:14.866 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:22:14.909 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:22:14.910 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:22:14.924 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:22:14.925 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:22:14.964 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.71
12:22:14.964 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:22:14.964 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:22:14.969 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:22:14.969 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:22:14.977 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.71
12:22:14.977 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:22:14.980 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:22:14.983 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.71
12:22:14.983 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@2e93a229, dubbo version: 3.1.0, current host: 10.1.0.71
12:22:15.142 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:22:15.176 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:22:15.193 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:22:15.282 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:22:15.289 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:22:15.290 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:22:15.445 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:22:15.461 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:22:15.461 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:22:15.461 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:22:15.462 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.71
12:22:15.478 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.71
12:22:15.552 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:22:15.669 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.71
12:22:15.671 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.71
12:22:15.680 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.71
12:22:15.685 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.71
12:22:15.687 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.71
12:22:15.726 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.71
12:22:15.761 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:22:15.762 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5653&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396535719&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:22:15.763 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5653&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396535719&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:22:15.763 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:22:15.821 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:22:15.822 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5653&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396535719&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.71
12:22:15.823 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.71
12:22:15.828 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.71
4.020 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.616 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.006 ms/op
Iteration   1: 2.522 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.118 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.215 ms/op
                 getUser·p0.99:   3.920 ms/op
                 getUser·p0.999:  12.295 ms/op
                 getUser·p0.9999: 14.139 ms/op
                 getUser·p1.00:   15.204 ms/op

Iteration   2: 2.531 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.481 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.895 ms/op
                 getUser·p0.999:  9.989 ms/op
                 getUser·p0.9999: 13.584 ms/op
                 getUser·p1.00:   14.664 ms/op

Iteration   3: 12:23:16.113 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:23:16.116 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:23:16.117 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.71
12:23:16.117 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:23:16.117 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.71
12:23:16.118 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:23:16.118 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:23:16.119 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:23:18.125 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5653&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396535719&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:23:18.126 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:23:18.126 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5653&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396535719&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:23:18.126 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:23:18.126 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:23:18.133 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:23:18.134 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:23:18.134 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:23:18.135 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:23:18.152 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:23:18.153 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.71
12:23:18.153 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:23:18.153 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:23:18.153 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.71
12:23:18.153 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:23:18.153 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:23:18.153 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:23:18.154 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:23:18.154 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.71
12:23:18.154 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.71
12:23:18.154 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:23:18.156 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.71
12:23:18.156 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:23:18.157 [org.apache.dubbo.benchmark.ClientPb.getUser-jmh-worker-17] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@2e93a229, dubbo version: 3.1.0, current host: 10.1.0.71
2.562 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.023 ms/op
                 getUser·p0.50:   2.597 ms/op
                 getUser·p0.90:   3.129 ms/op
                 getUser·p0.95:   3.285 ms/op
                 getUser·p0.99:   4.157 ms/op
                 getUser·p0.999:  8.163 ms/op
                 getUser·p0.9999: 10.028 ms/op
                 getUser·p1.00:   10.273 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377901
  mean =      2.538 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 184376 
    [ 2.500,  3.750) = 188021 
    [ 3.750,  5.000) = 4315 
    [ 5.000,  6.250) = 727 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 130 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.481 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      4.006 ms/op
     p(99.9000) =      8.471 ms/op
     p(99.9900) =     13.724 ms/op
     p(99.9990) =     14.562 ms/op
     p(99.9999) =     15.204 ms/op
    p(100.0000) =     15.204 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12:23:19.865 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.71
12:23:19.868 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:23:19.911 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:23:19.912 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:23:19.927 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:23:19.927 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:23:19.965 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.71
12:23:19.965 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:23:19.965 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:23:19.971 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:23:19.972 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:23:19.980 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.71
12:23:19.980 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.71
12:23:19.983 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.71
12:23:19.986 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.71
12:23:19.986 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@18522276, dubbo version: 3.1.0, current host: 10.1.0.71
12:23:20.133 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
12:23:20.169 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
12:23:20.186 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
12:23:20.275 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:23:20.283 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:23:20.284 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.71
12:23:20.435 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
12:23:20.451 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:23:20.451 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:23:20.452 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.71
12:23:20.452 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.71
12:23:20.471 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-triple-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.71
12:23:20.540 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:23:20.654 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.bean.UserServiceDubbo$IUserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.71
12:23:20.656 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.71
12:23:20.663 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.71
12:23:20.667 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.71
12:23:20.676 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.71
12:23:20.707 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20881) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.71
12:23:20.744 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:23:20.746 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5944&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396600699&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:23:20.746 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5944&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396600699&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:23:20.747 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] qos won't be started because it is disabled. Please check dubbo.application.qos.enable is configured either in system property, dubbo.properties or XML/spring-boot configuration., dubbo version: 3.1.0, current host: 10.1.0.71
12:23:20.806 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20881, export /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:23:20.807 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5944&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396600699&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.71
12:23:20.808 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.71
12:23:20.813 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.71
4.802 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.008 ms/op
Iteration   1: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.888 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  8.743 ms/op
                 listUser·p0.9999: 11.331 ms/op
                 listUser·p1.00:   12.386 ms/op

Iteration   2: 2.980 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.792 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.133 ms/op
                 listUser·p0.9999: 11.330 ms/op
                 listUser·p1.00:   12.403 ms/op

Iteration   3: 12:24:21.230 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:24:21.234 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:24:21.234 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-triple-client) to null, dubbo version: 3.1.0, current host: 10.1.0.71
12:24:21.234 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:24:21.234 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.71
12:24:21.236 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:24:21.236 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:24:21.237 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20881, export /10.1.0.71:20881, dubbo version: 3.1.0, current host: 10.1.0.71
12:24:23.243 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.71:20881/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5944&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396600699&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:24:23.243 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:24:23.244 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-triple-client&background=false&bind.ip=10.1.0.71&bind.port=20881&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-triple-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=5944&qos.enable=false&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1700396600699&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.71
12:24:23.244 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:24:23.244 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.r.protocol.tri.TripleProtocol -  [DUBBO] Destroying protocol [TripleProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:24:23.244 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:24:23.245 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:24:23.245 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:24:23.245 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:24:23.256 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-triple-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:24:23.257 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.71
12:24:23.257 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:24:23.257 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:24:23.258 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.71
12:24:23.258 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.71
12:24:23.258 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:24:23.258 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:24:23.258 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.71
12:24:23.259 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.71
12:24:23.259 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.71
12:24:23.260 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.71
12:24:23.262 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.71
12:24:23.262 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.71
12:24:23.263 [org.apache.dubbo.benchmark.ClientPb.listUser-jmh-worker-25] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@18522276, dubbo version: 3.1.0, current host: 10.1.0.71
3.021 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.719 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.342 ms/op
                 listUser·p0.9999: 11.721 ms/op
                 listUser·p1.00:   12.403 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319961
  mean =      2.998 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 124 
    [ 1.250,  2.500) = 95188 
    [ 2.500,  3.750) = 185909 
    [ 3.750,  5.000) = 31241 
    [ 5.000,  6.250) = 6163 
    [ 6.250,  7.500) = 712 
    [ 7.500,  8.750) = 231 
    [ 8.750, 10.000) = 221 
    [10.000, 11.250) = 133 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.110 ms/op
     p(99.9900) =     11.420 ms/op
     p(99.9990) =     12.383 ms/op
     p(99.9999) =     12.403 ms/op
    p(100.0000) =     12.403 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.454 ± 1.832  ops/ms
ClientPb.existUser                       thrpt       3  12.927 ± 1.424  ops/ms
ClientPb.getUser                         thrpt       3  12.582 ± 1.402  ops/ms
ClientPb.listUser                        thrpt       3  10.529 ± 1.687  ops/ms
ClientPb.createUser                       avgt       3   2.552 ± 0.585   ms/op
ClientPb.existUser                        avgt       3   2.493 ± 0.142   ms/op
ClientPb.getUser                          avgt       3   2.532 ± 0.245   ms/op
ClientPb.listUser                         avgt       3   3.025 ± 0.181   ms/op
ClientPb.createUser                     sample  374909   2.558 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.829           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.630           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.236           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.875           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.832           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.779           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.630           ms/op
ClientPb.existUser                      sample  391326   2.451 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.889           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.805           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.067           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.746           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.008           ms/op
ClientPb.getUser                        sample  377901   2.538 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.481           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.564           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.232           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.006           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.471           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.724           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.204           ms/op
ClientPb.listUser                       sample  319961   2.998 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.719           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.110           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.420           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.403           ms/op
```
