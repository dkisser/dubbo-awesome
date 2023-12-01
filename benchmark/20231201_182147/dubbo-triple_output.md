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
[INFO] benchmark-base ..................................... SUCCESS [  2.914 s]
[INFO] server-base ........................................ SUCCESS [  0.344 s]
[INFO] client-base ........................................ SUCCESS [  0.598 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.516 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  4.682 s
[INFO] Finished at: 2023-12-01T18:08:22Z
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
# Warmup Iteration   1: 4.969 ops/ms
# Warmup Iteration   2: 11.821 ops/ms
# Warmup Iteration   3: 12.043 ops/ms
Iteration   1: 12.171 ops/ms
Iteration   2: 12.356 ops/ms
Iteration   3: 12.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.323 ±(99.9%) 2.527 ops/ms [Average]
  (min, avg, max) = (12.171, 12.323, 12.442), stdev = 0.138
  CI (99.9%): [9.796, 14.849] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.854 ops/ms
# Warmup Iteration   2: 12.571 ops/ms
# Warmup Iteration   3: 12.703 ops/ms
Iteration   1: 12.639 ops/ms
Iteration   2: 12.850 ops/ms
Iteration   3: 12.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.765 ±(99.9%) 2.034 ops/ms [Average]
  (min, avg, max) = (12.639, 12.765, 12.850), stdev = 0.111
  CI (99.9%): [10.731, 14.798] (assumes normal distribution)


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
# Warmup Iteration   1: 7.774 ops/ms
# Warmup Iteration   2: 12.145 ops/ms
# Warmup Iteration   3: 12.369 ops/ms
Iteration   1: 12.456 ops/ms
Iteration   2: 12.427 ops/ms
Iteration   3: 12.367 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.417 ±(99.9%) 0.827 ops/ms [Average]
  (min, avg, max) = (12.367, 12.417, 12.456), stdev = 0.045
  CI (99.9%): [11.590, 13.243] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.649 ops/ms
# Warmup Iteration   2: 10.392 ops/ms
# Warmup Iteration   3: 10.279 ops/ms
Iteration   1: 10.360 ops/ms
Iteration   2: 10.397 ops/ms
Iteration   3: 10.451 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.403 ±(99.9%) 0.832 ops/ms [Average]
  (min, avg, max) = (10.360, 10.403, 10.451), stdev = 0.046
  CI (99.9%): [9.570, 11.235] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.981 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.670 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.600 ±(99.9%) 0.005 ms/op
Iteration   1: 2.573 ±(99.9%) 0.003 ms/op
Iteration   2: 2.615 ±(99.9%) 0.004 ms/op
Iteration   3: 2.558 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.582 ±(99.9%) 0.538 ms/op [Average]
  (min, avg, max) = (2.558, 2.582, 2.615), stdev = 0.029
  CI (99.9%): [2.044, 3.120] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.687 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.004 ms/op
Iteration   1: 2.535 ±(99.9%) 0.004 ms/op
Iteration   2: 2.509 ±(99.9%) 0.004 ms/op
Iteration   3: 2.535 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.526 ±(99.9%) 0.268 ms/op [Average]
  (min, avg, max) = (2.509, 2.526, 2.535), stdev = 0.015
  CI (99.9%): [2.258, 2.795] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.106 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.005 ms/op
Iteration   1: 2.558 ±(99.9%) 0.005 ms/op
Iteration   2: 2.577 ±(99.9%) 0.004 ms/op
Iteration   3: 2.544 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.559 ±(99.9%) 0.301 ms/op [Average]
  (min, avg, max) = (2.544, 2.559, 2.577), stdev = 0.016
  CI (99.9%): [2.259, 2.860] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 5.026 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.173 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.005 ms/op
Iteration   1: 3.068 ±(99.9%) 0.005 ms/op
Iteration   2: 3.088 ±(99.9%) 0.006 ms/op
Iteration   3: 3.095 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.084 ±(99.9%) 0.258 ms/op [Average]
  (min, avg, max) = (3.068, 3.084, 3.095), stdev = 0.014
  CI (99.9%): [2.825, 3.342] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.160 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.789 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.628 ±(99.9%) 0.006 ms/op
Iteration   1: 2.622 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   2.675 ms/op
                 createUser·p0.90:   3.187 ms/op
                 createUser·p0.95:   3.322 ms/op
                 createUser·p0.99:   4.010 ms/op
                 createUser·p0.999:  13.779 ms/op
                 createUser·p0.9999: 15.683 ms/op
                 createUser·p1.00:   16.777 ms/op

Iteration   2: 2.600 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.162 ms/op
                 createUser·p0.95:   3.285 ms/op
                 createUser·p0.99:   3.813 ms/op
                 createUser·p0.999:  10.257 ms/op
                 createUser·p0.9999: 14.736 ms/op
                 createUser·p1.00:   16.089 ms/op

Iteration   3: 2.600 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.154 ms/op
                 createUser·p0.95:   3.301 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  10.650 ms/op
                 createUser·p0.9999: 17.184 ms/op
                 createUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 367816
  mean =      2.607 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 173794 
    [ 2.500,  3.750) = 188404 
    [ 3.750,  5.000) = 4468 
    [ 5.000,  6.250) = 593 
    [ 6.250,  7.500) = 87 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 141 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      2.650 ms/op
     p(90.0000) =      3.170 ms/op
     p(95.0000) =      3.301 ms/op
     p(99.0000) =      3.994 ms/op
     p(99.9000) =     10.682 ms/op
     p(99.9900) =     16.044 ms/op
     p(99.9990) =     17.869 ms/op
     p(99.9999) =     17.891 ms/op
    p(100.0000) =     17.891 ms/op


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
# Warmup Iteration   1: 3.767 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.561 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.006 ms/op
Iteration   1: 2.506 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.992 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.068 ms/op
                 existUser·p0.95:   3.199 ms/op
                 existUser·p0.99:   3.777 ms/op
                 existUser·p0.999:  5.480 ms/op
                 existUser·p0.9999: 17.965 ms/op
                 existUser·p1.00:   18.317 ms/op

Iteration   2: 2.503 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.900 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   3.813 ms/op
                 existUser·p0.999:  11.199 ms/op
                 existUser·p0.9999: 16.368 ms/op
                 existUser·p1.00:   17.269 ms/op

Iteration   3: 2.536 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.929 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.088 ms/op
                 existUser·p0.95:   3.215 ms/op
                 existUser·p0.99:   3.939 ms/op
                 existUser·p0.999:  9.698 ms/op
                 existUser·p0.9999: 15.532 ms/op
                 existUser·p1.00:   16.269 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 381336
  mean =      2.515 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 186359 
    [ 2.500,  3.750) = 190555 
    [ 3.750,  5.000) = 3464 
    [ 5.000,  6.250) = 477 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 68 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =      7.356 ms/op
     p(99.9900) =     16.459 ms/op
     p(99.9990) =     18.160 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.168 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.686 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.584 ±(99.9%) 0.006 ms/op
Iteration   1: 2.547 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.943 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   3.973 ms/op
                 getUser·p0.999:  13.681 ms/op
                 getUser·p0.9999: 17.265 ms/op
                 getUser·p1.00:   17.433 ms/op

Iteration   2: 2.532 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.962 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   4.002 ms/op
                 getUser·p0.999:  11.284 ms/op
                 getUser·p0.9999: 15.059 ms/op
                 getUser·p1.00:   16.531 ms/op

Iteration   3: 2.563 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.921 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.285 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  11.403 ms/op
                 getUser·p0.9999: 15.311 ms/op
                 getUser·p1.00:   15.778 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376537
  mean =      2.547 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 182961 
    [ 2.500,  3.750) = 187284 
    [ 3.750,  5.000) = 5098 
    [ 5.000,  6.250) = 632 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 140 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 117 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.921 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.256 ms/op
     p(99.0000) =      4.043 ms/op
     p(99.9000) =     11.378 ms/op
     p(99.9900) =     15.778 ms/op
     p(99.9990) =     17.400 ms/op
     p(99.9999) =     17.433 ms/op
    p(100.0000) =     17.433 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.001 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.195 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.152 ±(99.9%) 0.010 ms/op
Iteration   1: 3.102 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.657 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.792 ms/op
                 listUser·p0.999:  10.518 ms/op
                 listUser·p0.9999: 12.070 ms/op
                 listUser·p1.00:   12.550 ms/op

Iteration   2: 3.103 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.815 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.767 ms/op
                 listUser·p0.999:  10.387 ms/op
                 listUser·p0.9999: 12.465 ms/op
                 listUser·p1.00:   12.616 ms/op

Iteration   3: 3.126 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.978 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   6.054 ms/op
                 listUser·p0.999:  11.959 ms/op
                 listUser·p0.9999: 18.645 ms/op
                 listUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 308313
  mean =      3.110 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 74590 
    [ 2.500,  5.000) = 224281 
    [ 5.000,  7.500) = 8619 
    [ 7.500, 10.000) = 314 
    [10.000, 12.500) = 415 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     11.005 ms/op
     p(99.9900) =     18.033 ms/op
     p(99.9990) =     24.970 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.323 ± 2.527  ops/ms
ClientPb.existUser                       thrpt       3  12.765 ± 2.034  ops/ms
ClientPb.getUser                         thrpt       3  12.417 ± 0.827  ops/ms
ClientPb.listUser                        thrpt       3  10.403 ± 0.832  ops/ms
ClientPb.createUser                       avgt       3   2.582 ± 0.538   ms/op
ClientPb.existUser                        avgt       3   2.526 ± 0.268   ms/op
ClientPb.getUser                          avgt       3   2.559 ± 0.301   ms/op
ClientPb.listUser                         avgt       3   3.084 ± 0.258   ms/op
ClientPb.createUser                     sample  367816   2.607 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.855           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.650           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.301           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.994           ms/op
ClientPb.createUser:createUser·p0.999   sample          10.682           ms/op
ClientPb.createUser:createUser·p0.9999  sample          16.044           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.891           ms/op
ClientPb.existUser                      sample  381336   2.515 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.900           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.195           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.834           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.356           ms/op
ClientPb.existUser:existUser·p0.9999    sample          16.459           ms/op
ClientPb.existUser:existUser·p1.00      sample          18.317           ms/op
ClientPb.getUser                        sample  376537   2.547 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.921           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.256           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.043           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.378           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.778           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.433           ms/op
ClientPb.listUser                       sample  308313   3.110 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.657           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.031           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.018           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.874           ms/op
ClientPb.listUser:listUser·p0.999       sample          11.005           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.033           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.625           ms/op
```
