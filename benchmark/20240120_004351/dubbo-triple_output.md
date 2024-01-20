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
[INFO] --- build-helper-maven-plugin:3.5.0:add-source (default) @ benchmark-base ---
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
[INFO] Copying logback-classic-1.3.12.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/logback-classic-1.3.12.jar
[INFO] Copying logback-core-1.3.12.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/logback-core-1.3.12.jar
[INFO] Copying commons-cli-1.4.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/libs/commons-cli-1.4.jar
[INFO] 
[INFO] --- maven-jar-plugin:3.1.0:jar (default-jar) @ dubbo-triple-client ---
[INFO] Building jar: /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-triple-client/target/dubbo-triple-client-1.0-SNAPSHOT.jar
[INFO] ------------------------------------------------------------------------
[INFO] Reactor Summary for benchmark-base 1.0-SNAPSHOT:
[INFO] 
[INFO] benchmark-base ..................................... SUCCESS [  2.868 s]
[INFO] server-base ........................................ SUCCESS [  0.336 s]
[INFO] client-base ........................................ SUCCESS [  0.610 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.493 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  4.618 s
[INFO] Finished at: 2024-01-20T00:30:24Z
[INFO] ------------------------------------------------------------------------

RUN dubbo-triple-client IN benchmark MODE
command is: java -server -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output= -jar dubbo-triple-client/target/dubbo-triple-client-1.0-SNAPSHOT.jar --warmupIterations=1 --warmupTime=1 --measurementIterations=1 --measurementTime=1

# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.432 ops/ms
# Warmup Iteration   2: 12.734 ops/ms
# Warmup Iteration   3: 12.826 ops/ms
Iteration   1: 13.166 ops/ms
Iteration   2: 13.169 ops/ms
Iteration   3: 13.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  13.146 ±(99.9%) 0.658 ops/ms [Average]
  (min, avg, max) = (13.105, 13.146, 13.169), stdev = 0.036
  CI (99.9%): [12.489, 13.804] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.202 ops/ms
# Warmup Iteration   2: 13.154 ops/ms
# Warmup Iteration   3: 13.339 ops/ms
Iteration   1: 13.231 ops/ms
Iteration   2: 13.456 ops/ms
Iteration   3: 13.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.371 ±(99.9%) 2.228 ops/ms [Average]
  (min, avg, max) = (13.231, 13.371, 13.456), stdev = 0.122
  CI (99.9%): [11.143, 15.599] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.563 ops/ms
# Warmup Iteration   2: 12.660 ops/ms
# Warmup Iteration   3: 13.244 ops/ms
Iteration   1: 13.175 ops/ms
Iteration   2: 13.127 ops/ms
Iteration   3: 13.130 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.144 ±(99.9%) 0.494 ops/ms [Average]
  (min, avg, max) = (13.127, 13.144, 13.175), stdev = 0.027
  CI (99.9%): [12.651, 13.638] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.970 ops/ms
# Warmup Iteration   2: 10.597 ops/ms
# Warmup Iteration   3: 10.671 ops/ms
Iteration   1: 10.740 ops/ms
Iteration   2: 10.818 ops/ms
Iteration   3: 10.823 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.794 ±(99.9%) 0.856 ops/ms [Average]
  (min, avg, max) = (10.740, 10.794, 10.823), stdev = 0.047
  CI (99.9%): [9.938, 11.649] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.724 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.522 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.436 ±(99.9%) 0.004 ms/op
Iteration   1: 2.467 ±(99.9%) 0.005 ms/op
Iteration   2: 2.449 ±(99.9%) 0.004 ms/op
Iteration   3: 2.446 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.454 ±(99.9%) 0.207 ms/op [Average]
  (min, avg, max) = (2.446, 2.454, 2.467), stdev = 0.011
  CI (99.9%): [2.247, 2.661] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.548 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.408 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.388 ±(99.9%) 0.005 ms/op
Iteration   1: 2.386 ±(99.9%) 0.003 ms/op
Iteration   2: 2.408 ±(99.9%) 0.004 ms/op
Iteration   3: 2.399 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.397 ±(99.9%) 0.205 ms/op [Average]
  (min, avg, max) = (2.386, 2.397, 2.408), stdev = 0.011
  CI (99.9%): [2.193, 2.602] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.842 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.485 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.433 ±(99.9%) 0.004 ms/op
Iteration   1: 2.452 ±(99.9%) 0.004 ms/op
Iteration   2: 2.479 ±(99.9%) 0.005 ms/op
Iteration   3: 2.470 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.467 ±(99.9%) 0.248 ms/op [Average]
  (min, avg, max) = (2.452, 2.467, 2.479), stdev = 0.014
  CI (99.9%): [2.219, 2.715] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.548 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.002 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.005 ms/op
Iteration   1: 2.948 ±(99.9%) 0.005 ms/op
Iteration   2: 2.977 ±(99.9%) 0.005 ms/op
Iteration   3: 2.954 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.960 ±(99.9%) 0.282 ms/op [Average]
  (min, avg, max) = (2.948, 2.960, 2.977), stdev = 0.015
  CI (99.9%): [2.678, 3.242] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.067 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.566 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
Iteration   1: 2.437 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.026 ms/op
                 createUser·p0.50:   2.494 ms/op
                 createUser·p0.90:   2.961 ms/op
                 createUser·p0.95:   3.072 ms/op
                 createUser·p0.99:   3.572 ms/op
                 createUser·p0.999:  5.799 ms/op
                 createUser·p0.9999: 13.005 ms/op
                 createUser·p1.00:   13.550 ms/op

Iteration   2: 2.465 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.911 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.789 ms/op
                 createUser·p0.999:  9.885 ms/op
                 createUser·p0.9999: 11.619 ms/op
                 createUser·p1.00:   12.386 ms/op

Iteration   3: 2.453 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.862 ms/op
                 createUser·p0.50:   2.490 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   4.080 ms/op
                 createUser·p0.999:  7.606 ms/op
                 createUser·p0.9999: 10.076 ms/op
                 createUser·p1.00:   10.551 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 391185
  mean =      2.452 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 194973 
    [ 2.500,  3.750) = 191982 
    [ 3.750,  5.000) = 3425 
    [ 5.000,  6.250) = 289 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 110 
    [10.000, 11.250) = 124 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.793 ms/op
     p(99.9000) =      8.713 ms/op
     p(99.9900) =     12.354 ms/op
     p(99.9990) =     13.189 ms/op
     p(99.9999) =     13.550 ms/op
    p(100.0000) =     13.550 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.674 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.462 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.402 ±(99.9%) 0.005 ms/op
Iteration   1: 2.413 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.882 ms/op
                 existUser·p0.50:   2.437 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.555 ms/op
                 existUser·p0.999:  5.026 ms/op
                 existUser·p0.9999: 14.262 ms/op
                 existUser·p1.00:   14.647 ms/op

Iteration   2: 2.435 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.022 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.744 ms/op
                 existUser·p0.999:  6.885 ms/op
                 existUser·p0.9999: 14.264 ms/op
                 existUser·p1.00:   15.090 ms/op

Iteration   3: 2.435 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.400 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   4.251 ms/op
                 existUser·p0.999:  8.662 ms/op
                 existUser·p0.9999: 11.565 ms/op
                 existUser·p1.00:   11.928 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395094
  mean =      2.428 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 98 
    [ 1.250,  2.500) = 199835 
    [ 2.500,  3.750) = 190718 
    [ 3.750,  5.000) = 3503 
    [ 5.000,  6.250) = 481 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 59 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.400 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      3.842 ms/op
     p(99.9000) =      7.431 ms/op
     p(99.9900) =     14.156 ms/op
     p(99.9990) =     14.910 ms/op
     p(99.9999) =     15.090 ms/op
    p(100.0000) =     15.090 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.746 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.450 ±(99.9%) 0.006 ms/op
Iteration   1: 2.474 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.731 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  6.917 ms/op
                 getUser·p0.9999: 15.763 ms/op
                 getUser·p1.00:   16.007 ms/op

Iteration   2: 2.470 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.478 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  7.132 ms/op
                 getUser·p0.9999: 11.961 ms/op
                 getUser·p1.00:   12.517 ms/op

Iteration   3: 2.422 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.802 ms/op
                 getUser·p0.50:   2.421 ms/op
                 getUser·p0.90:   2.961 ms/op
                 getUser·p0.95:   3.084 ms/op
                 getUser·p0.99:   3.666 ms/op
                 getUser·p0.999:  6.038 ms/op
                 getUser·p0.9999: 10.712 ms/op
                 getUser·p1.00:   10.928 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 390671
  mean =      2.455 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 99 
    [ 1.250,  2.500) = 199621 
    [ 2.500,  3.750) = 183801 
    [ 3.750,  5.000) = 5893 
    [ 5.000,  6.250) = 825 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.478 ms/op
     p(50.0000) =      2.466 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      7.102 ms/op
     p(99.9900) =     14.876 ms/op
     p(99.9990) =     15.861 ms/op
     p(99.9999) =     16.007 ms/op
    p(100.0000) =     16.007 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.569 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 2.994 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.008 ms/op
Iteration   1: 2.991 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.913 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  8.266 ms/op
                 listUser·p0.9999: 11.026 ms/op
                 listUser·p1.00:   11.289 ms/op

Iteration   2: 2.960 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.886 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.126 ms/op
                 listUser·p0.9999: 11.947 ms/op
                 listUser·p1.00:   12.419 ms/op

Iteration   3: 2.952 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.884 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  8.503 ms/op
                 listUser·p0.9999: 9.915 ms/op
                 listUser·p1.00:   10.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323173
  mean =      2.968 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 151 
    [ 1.250,  2.500) = 97305 
    [ 2.500,  3.750) = 188512 
    [ 3.750,  5.000) = 30405 
    [ 5.000,  6.250) = 5693 
    [ 6.250,  7.500) = 521 
    [ 7.500,  8.750) = 289 
    [ 8.750, 10.000) = 180 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.474 ms/op
     p(99.9000) =      8.618 ms/op
     p(99.9900) =     11.289 ms/op
     p(99.9990) =     12.232 ms/op
     p(99.9999) =     12.419 ms/op
    p(100.0000) =     12.419 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  13.146 ± 0.658  ops/ms
ClientPb.existUser                       thrpt       3  13.371 ± 2.228  ops/ms
ClientPb.getUser                         thrpt       3  13.144 ± 0.494  ops/ms
ClientPb.listUser                        thrpt       3  10.794 ± 0.856  ops/ms
ClientPb.createUser                       avgt       3   2.454 ± 0.207   ms/op
ClientPb.existUser                        avgt       3   2.397 ± 0.205   ms/op
ClientPb.getUser                          avgt       3   2.467 ± 0.248   ms/op
ClientPb.listUser                         avgt       3   2.960 ± 0.282   ms/op
ClientPb.createUser                     sample  391185   2.452 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.862           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.507           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.978           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.713           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.354           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.550           ms/op
ClientPb.existUser                      sample  395094   2.428 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.400           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.478           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.953           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.842           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.431           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.156           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.090           ms/op
ClientPb.getUser                        sample  390671   2.455 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.478           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.466           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.252           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.102           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.876           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.007           ms/op
ClientPb.listUser                       sample  323173   2.968 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.884           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.904           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.474           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.618           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.289           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.419           ms/op
```
