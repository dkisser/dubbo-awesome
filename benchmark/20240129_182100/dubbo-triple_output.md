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
[INFO] benchmark-base ..................................... SUCCESS [  2.933 s]
[INFO] server-base ........................................ SUCCESS [  0.356 s]
[INFO] client-base ........................................ SUCCESS [  0.624 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.479 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  4.695 s
[INFO] Finished at: 2024-01-29T18:07:37Z
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
# Warmup Iteration   1: 4.767 ops/ms
# Warmup Iteration   2: 12.218 ops/ms
# Warmup Iteration   3: 12.484 ops/ms
Iteration   1: 12.922 ops/ms
Iteration   2: 12.830 ops/ms
Iteration   3: 12.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.894 ±(99.9%) 1.023 ops/ms [Average]
  (min, avg, max) = (12.830, 12.894, 12.931), stdev = 0.056
  CI (99.9%): [11.872, 13.917] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.655 ops/ms
# Warmup Iteration   2: 13.117 ops/ms
# Warmup Iteration   3: 13.316 ops/ms
Iteration   1: 13.392 ops/ms
Iteration   2: 13.350 ops/ms
Iteration   3: 13.362 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.368 ±(99.9%) 0.391 ops/ms [Average]
  (min, avg, max) = (13.350, 13.368, 13.392), stdev = 0.021
  CI (99.9%): [12.977, 13.759] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.086 ops/ms
# Warmup Iteration   2: 12.913 ops/ms
# Warmup Iteration   3: 12.910 ops/ms
Iteration   1: 13.124 ops/ms
Iteration   2: 13.135 ops/ms
Iteration   3: 13.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.120 ±(99.9%) 0.307 ops/ms [Average]
  (min, avg, max) = (13.102, 13.120, 13.135), stdev = 0.017
  CI (99.9%): [12.813, 13.427] (assumes normal distribution)


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
# Warmup Iteration   1: 7.023 ops/ms
# Warmup Iteration   2: 10.726 ops/ms
# Warmup Iteration   3: 10.803 ops/ms
Iteration   1: 10.942 ops/ms
Iteration   2: 10.834 ops/ms
Iteration   3: 10.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.882 ±(99.9%) 1.007 ops/ms [Average]
  (min, avg, max) = (10.834, 10.882, 10.942), stdev = 0.055
  CI (99.9%): [9.874, 11.889] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.869 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.493 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.004 ms/op
Iteration   1: 2.456 ±(99.9%) 0.004 ms/op
Iteration   2: 2.507 ±(99.9%) 0.004 ms/op
Iteration   3: 2.468 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.477 ±(99.9%) 0.484 ms/op [Average]
  (min, avg, max) = (2.456, 2.477, 2.507), stdev = 0.027
  CI (99.9%): [1.993, 2.961] (assumes normal distribution)


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
# Warmup Iteration   1: 3.698 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.435 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.380 ±(99.9%) 0.003 ms/op
Iteration   1: 2.381 ±(99.9%) 0.004 ms/op
Iteration   2: 2.412 ±(99.9%) 0.004 ms/op
Iteration   3: 2.416 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.403 ±(99.9%) 0.356 ms/op [Average]
  (min, avg, max) = (2.381, 2.403, 2.416), stdev = 0.020
  CI (99.9%): [2.047, 2.759] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.744 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.504 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.459 ±(99.9%) 0.004 ms/op
Iteration   1: 2.447 ±(99.9%) 0.004 ms/op
Iteration   2: 2.469 ±(99.9%) 0.004 ms/op
Iteration   3: 2.490 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.469 ±(99.9%) 0.390 ms/op [Average]
  (min, avg, max) = (2.447, 2.469, 2.490), stdev = 0.021
  CI (99.9%): [2.078, 2.859] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.884 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.992 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.006 ms/op
Iteration   1: 2.989 ±(99.9%) 0.006 ms/op
Iteration   2: 2.957 ±(99.9%) 0.006 ms/op
Iteration   3: 2.951 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.966 ±(99.9%) 0.367 ms/op [Average]
  (min, avg, max) = (2.951, 2.966, 2.989), stdev = 0.020
  CI (99.9%): [2.599, 3.333] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.814 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.006 ms/op
Iteration   1: 2.455 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.028 ms/op
                 createUser·p0.50:   2.523 ms/op
                 createUser·p0.90:   2.974 ms/op
                 createUser·p0.95:   3.076 ms/op
                 createUser·p0.99:   3.650 ms/op
                 createUser·p0.999:  10.276 ms/op
                 createUser·p0.9999: 13.286 ms/op
                 createUser·p1.00:   14.238 ms/op

Iteration   2: 2.451 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.958 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   2.974 ms/op
                 createUser·p0.95:   3.064 ms/op
                 createUser·p0.99:   3.387 ms/op
                 createUser·p0.999:  6.138 ms/op
                 createUser·p0.9999: 12.500 ms/op
                 createUser·p1.00:   13.353 ms/op

Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.958 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.994 ms/op
                 createUser·p0.999:  7.918 ms/op
                 createUser·p0.9999: 11.126 ms/op
                 createUser·p1.00:   12.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 389116
  mean =      2.465 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 191565 
    [ 2.500,  3.750) = 194066 
    [ 3.750,  5.000) = 2672 
    [ 5.000,  6.250) = 324 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.958 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.674 ms/op
     p(99.9000) =      8.651 ms/op
     p(99.9900) =     12.948 ms/op
     p(99.9990) =     14.114 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.725 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.435 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.422 ±(99.9%) 0.005 ms/op
Iteration   1: 2.405 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.081 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.916 ms/op
                 existUser·p0.95:   3.002 ms/op
                 existUser·p0.99:   3.318 ms/op
                 existUser·p0.999:  5.801 ms/op
                 existUser·p0.9999: 13.578 ms/op
                 existUser·p1.00:   14.238 ms/op

Iteration   2: 2.422 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.039 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.740 ms/op
                 existUser·p0.999:  7.037 ms/op
                 existUser·p0.9999: 11.960 ms/op
                 existUser·p1.00:   12.583 ms/op

Iteration   3: 2.439 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.714 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.784 ms/op
                 existUser·p0.999:  7.826 ms/op
                 existUser·p0.9999: 11.924 ms/op
                 existUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395914
  mean =      2.422 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 197074 
    [ 2.500,  3.750) = 195421 
    [ 3.750,  5.000) = 2395 
    [ 5.000,  6.250) = 495 
    [ 6.250,  7.500) = 102 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 126 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.933 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      3.625 ms/op
     p(99.9000) =      7.029 ms/op
     p(99.9900) =     13.124 ms/op
     p(99.9990) =     14.042 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


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
# Warmup Iteration   1: 3.961 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.504 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
Iteration   1: 2.447 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.994 ms/op
                 getUser·p0.50:   2.458 ms/op
                 getUser·p0.90:   2.978 ms/op
                 getUser·p0.95:   3.076 ms/op
                 getUser·p0.99:   3.490 ms/op
                 getUser·p0.999:  6.464 ms/op
                 getUser·p0.9999: 14.171 ms/op
                 getUser·p1.00:   14.336 ms/op

Iteration   2: 2.484 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.848 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.854 ms/op
                 getUser·p0.999:  7.516 ms/op
                 getUser·p0.9999: 11.389 ms/op
                 getUser·p1.00:   12.403 ms/op

Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.877 ms/op
                 getUser·p0.50:   2.429 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.965 ms/op
                 getUser·p0.999:  6.700 ms/op
                 getUser·p0.9999: 11.354 ms/op
                 getUser·p1.00:   12.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389489
  mean =      2.463 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 198688 
    [ 2.500,  3.750) = 186509 
    [ 3.750,  5.000) = 3480 
    [ 5.000,  6.250) = 292 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      2.454 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.793 ms/op
     p(99.9000) =      6.701 ms/op
     p(99.9900) =     13.124 ms/op
     p(99.9990) =     14.289 ms/op
     p(99.9999) =     14.336 ms/op
    p(100.0000) =     14.336 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.360 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.998 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.950 ±(99.9%) 0.008 ms/op
Iteration   1: 2.955 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.908 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.372 ms/op
                 listUser·p0.9999: 11.079 ms/op
                 listUser·p1.00:   12.829 ms/op

Iteration   2: 2.956 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.757 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.797 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  10.336 ms/op
                 listUser·p0.9999: 18.547 ms/op
                 listUser·p1.00:   18.743 ms/op

Iteration   3: 2.951 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.757 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.768 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   5.276 ms/op
                 listUser·p0.999:  9.612 ms/op
                 listUser·p0.9999: 11.772 ms/op
                 listUser·p1.00:   12.796 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324668
  mean =      2.954 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 166 
    [ 1.250,  2.500) = 103604 
    [ 2.500,  3.750) = 186339 
    [ 3.750,  5.000) = 28607 
    [ 5.000,  6.250) = 4813 
    [ 6.250,  7.500) = 449 
    [ 7.500,  8.750) = 153 
    [ 8.750, 10.000) = 280 
    [10.000, 11.250) = 156 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =      9.639 ms/op
     p(99.9900) =     14.987 ms/op
     p(99.9990) =     18.645 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.894 ± 1.023  ops/ms
ClientPb.existUser                       thrpt       3  13.368 ± 0.391  ops/ms
ClientPb.getUser                         thrpt       3  13.120 ± 0.307  ops/ms
ClientPb.listUser                        thrpt       3  10.882 ± 1.007  ops/ms
ClientPb.createUser                       avgt       3   2.477 ± 0.484   ms/op
ClientPb.existUser                        avgt       3   2.403 ± 0.356   ms/op
ClientPb.getUser                          avgt       3   2.469 ± 0.390   ms/op
ClientPb.listUser                         avgt       3   2.966 ± 0.367   ms/op
ClientPb.createUser                     sample  389116   2.465 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.958           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.535           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.990           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.674           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.651           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.948           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.238           ms/op
ClientPb.existUser                      sample  395914   2.422 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.714           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.933           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.029           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.124           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.238           ms/op
ClientPb.getUser                        sample  389489   2.463 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.848           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.454           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.011           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.701           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.124           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.336           ms/op
ClientPb.listUser                       sample  324668   2.954 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.757           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.896           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.789           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.415           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.639           ms/op
ClientPb.listUser:listUser·p0.9999      sample          14.987           ms/op
ClientPb.listUser:listUser·p1.00        sample          18.743           ms/op
```
