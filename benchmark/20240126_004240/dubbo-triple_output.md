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
[INFO] benchmark-base ..................................... SUCCESS [  2.840 s]
[INFO] server-base ........................................ SUCCESS [  0.279 s]
[INFO] client-base ........................................ SUCCESS [  0.585 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.337 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  4.336 s
[INFO] Finished at: 2024-01-26T00:29:21Z
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
# Warmup Iteration   1: 5.056 ops/ms
# Warmup Iteration   2: 12.124 ops/ms
# Warmup Iteration   3: 12.295 ops/ms
Iteration   1: 12.567 ops/ms
Iteration   2: 12.670 ops/ms
Iteration   3: 12.742 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.660 ±(99.9%) 1.601 ops/ms [Average]
  (min, avg, max) = (12.567, 12.660, 12.742), stdev = 0.088
  CI (99.9%): [11.059, 14.260] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.540 ops/ms
# Warmup Iteration   2: 13.049 ops/ms
# Warmup Iteration   3: 13.149 ops/ms
Iteration   1: 13.104 ops/ms
Iteration   2: 13.142 ops/ms
Iteration   3: 13.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.132 ±(99.9%) 0.452 ops/ms [Average]
  (min, avg, max) = (13.104, 13.132, 13.150), stdev = 0.025
  CI (99.9%): [12.680, 13.584] (assumes normal distribution)


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
# Warmup Iteration   1: 7.654 ops/ms
# Warmup Iteration   2: 12.459 ops/ms
# Warmup Iteration   3: 12.734 ops/ms
Iteration   1: 12.734 ops/ms
Iteration   2: 12.744 ops/ms
Iteration   3: 12.647 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.708 ±(99.9%) 0.969 ops/ms [Average]
  (min, avg, max) = (12.647, 12.708, 12.744), stdev = 0.053
  CI (99.9%): [11.739, 13.677] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.693 ops/ms
# Warmup Iteration   2: 10.459 ops/ms
# Warmup Iteration   3: 10.623 ops/ms
Iteration   1: 10.706 ops/ms
Iteration   2: 10.735 ops/ms
Iteration   3: 10.656 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.699 ±(99.9%) 0.728 ops/ms [Average]
  (min, avg, max) = (10.656, 10.699, 10.735), stdev = 0.040
  CI (99.9%): [9.971, 11.427] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.105 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.555 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.546 ±(99.9%) 0.004 ms/op
Iteration   1: 2.563 ±(99.9%) 0.004 ms/op
Iteration   2: 2.539 ±(99.9%) 0.005 ms/op
Iteration   3: 2.522 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.541 ±(99.9%) 0.372 ms/op [Average]
  (min, avg, max) = (2.522, 2.541, 2.563), stdev = 0.020
  CI (99.9%): [2.169, 2.914] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.651 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.414 ±(99.9%) 0.003 ms/op
Iteration   1: 2.397 ±(99.9%) 0.004 ms/op
Iteration   2: 2.430 ±(99.9%) 0.004 ms/op
Iteration   3: 2.433 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.420 ±(99.9%) 0.366 ms/op [Average]
  (min, avg, max) = (2.397, 2.420, 2.433), stdev = 0.020
  CI (99.9%): [2.054, 2.786] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.766 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.540 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.004 ms/op
Iteration   1: 2.500 ±(99.9%) 0.004 ms/op
Iteration   2: 2.483 ±(99.9%) 0.004 ms/op
Iteration   3: 2.497 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.493 ±(99.9%) 0.160 ms/op [Average]
  (min, avg, max) = (2.483, 2.493, 2.500), stdev = 0.009
  CI (99.9%): [2.334, 2.653] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.519 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.004 ms/op
Iteration   1: 2.985 ±(99.9%) 0.006 ms/op
Iteration   2: 2.999 ±(99.9%) 0.006 ms/op
Iteration   3: 3.024 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.002 ±(99.9%) 0.364 ms/op [Average]
  (min, avg, max) = (2.985, 3.002, 3.024), stdev = 0.020
  CI (99.9%): [2.638, 3.367] (assumes normal distribution)


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
# Warmup Iteration   1: 4.161 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.671 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.005 ms/op
Iteration   1: 2.541 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.017 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.777 ms/op
                 createUser·p0.999:  11.043 ms/op
                 createUser·p0.9999: 13.525 ms/op
                 createUser·p1.00:   13.861 ms/op

Iteration   2: 2.519 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.013 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.854 ms/op
                 createUser·p0.999:  9.981 ms/op
                 createUser·p0.9999: 11.883 ms/op
                 createUser·p1.00:   12.452 ms/op

Iteration   3: 2.546 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   4.926 ms/op
                 createUser·p0.999:  8.709 ms/op
                 createUser·p0.9999: 10.688 ms/op
                 createUser·p1.00:   11.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378230
  mean =      2.535 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 181081 
    [ 2.500,  3.750) = 191486 
    [ 3.750,  5.000) = 3761 
    [ 5.000,  6.250) = 1269 
    [ 6.250,  7.500) = 141 
    [ 7.500,  8.750) = 71 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 150 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.994 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      4.123 ms/op
     p(99.9000) =      8.762 ms/op
     p(99.9900) =     12.780 ms/op
     p(99.9990) =     13.783 ms/op
     p(99.9999) =     13.861 ms/op
    p(100.0000) =     13.861 ms/op


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
# Warmup Iteration   1: 3.525 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.430 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.420 ±(99.9%) 0.005 ms/op
Iteration   1: 2.432 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.906 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  6.013 ms/op
                 existUser·p0.9999: 13.402 ms/op
                 existUser·p1.00:   13.844 ms/op

Iteration   2: 2.433 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.942 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.564 ms/op
                 existUser·p0.999:  7.182 ms/op
                 existUser·p0.9999: 13.334 ms/op
                 existUser·p1.00:   13.664 ms/op

Iteration   3: 2.427 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.889 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.469 ms/op
                 existUser·p0.999:  6.878 ms/op
                 existUser·p0.9999: 11.807 ms/op
                 existUser·p1.00:   12.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394602
  mean =      2.430 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 196166 
    [ 2.500,  3.750) = 195521 
    [ 3.750,  5.000) = 2055 
    [ 5.000,  6.250) = 398 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.889 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      3.531 ms/op
     p(99.9000) =      6.421 ms/op
     p(99.9900) =     13.287 ms/op
     p(99.9990) =     13.633 ms/op
     p(99.9999) =     13.844 ms/op
    p(100.0000) =     13.844 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.874 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.571 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
Iteration   1: 2.521 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.830 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  11.592 ms/op
                 getUser·p0.9999: 14.074 ms/op
                 getUser·p1.00:   14.729 ms/op

Iteration   2: 2.527 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.768 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.076 ms/op
                 getUser·p0.999:  9.561 ms/op
                 getUser·p0.9999: 13.245 ms/op
                 getUser·p1.00:   13.812 ms/op

Iteration   3: 2.527 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.888 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   4.006 ms/op
                 getUser·p0.999:  9.011 ms/op
                 getUser·p0.9999: 13.031 ms/op
                 getUser·p1.00:   13.320 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379803
  mean =      2.525 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 85 
    [ 1.250,  2.500) = 186697 
    [ 2.500,  3.750) = 187086 
    [ 3.750,  5.000) = 4688 
    [ 5.000,  6.250) = 808 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 115 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      4.125 ms/op
     p(99.9000) =      9.021 ms/op
     p(99.9900) =     13.616 ms/op
     p(99.9990) =     14.241 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


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
# Warmup Iteration   1: 4.682 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.009 ms/op
Iteration   1: 3.034 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.853 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.021 ms/op
                 listUser·p0.9999: 10.682 ms/op
                 listUser·p1.00:   11.059 ms/op

Iteration   2: 3.042 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.940 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.306 ms/op
                 listUser·p0.9999: 11.010 ms/op
                 listUser·p1.00:   11.436 ms/op

Iteration   3: 3.045 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.760 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.784 ms/op
                 listUser·p0.999:  9.585 ms/op
                 listUser·p0.9999: 12.616 ms/op
                 listUser·p1.00:   13.484 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315504
  mean =      3.040 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 109 
    [ 1.250,  2.500) = 86805 
    [ 2.500,  3.750) = 187794 
    [ 3.750,  5.000) = 32928 
    [ 5.000,  6.250) = 6456 
    [ 6.250,  7.500) = 763 
    [ 7.500,  8.750) = 227 
    [ 8.750, 10.000) = 250 
    [10.000, 11.250) = 131 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =      9.224 ms/op
     p(99.9900) =     11.786 ms/op
     p(99.9990) =     13.195 ms/op
     p(99.9999) =     13.484 ms/op
    p(100.0000) =     13.484 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.660 ± 1.601  ops/ms
ClientPb.existUser                       thrpt       3  13.132 ± 0.452  ops/ms
ClientPb.getUser                         thrpt       3  12.708 ± 0.969  ops/ms
ClientPb.listUser                        thrpt       3  10.699 ± 0.728  ops/ms
ClientPb.createUser                       avgt       3   2.541 ± 0.372   ms/op
ClientPb.existUser                        avgt       3   2.420 ± 0.366   ms/op
ClientPb.getUser                          avgt       3   2.493 ± 0.160   ms/op
ClientPb.listUser                         avgt       3   3.002 ± 0.364   ms/op
ClientPb.createUser                     sample  378230   2.535 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.994           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.123           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.762           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.780           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.861           ms/op
ClientPb.existUser                      sample  394602   2.430 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.889           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.953           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.531           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.421           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.287           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.844           ms/op
ClientPb.getUser                        sample  379803   2.525 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.768           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.228           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.125           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.021           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.616           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.729           ms/op
ClientPb.listUser                       sample  315504   3.040 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.760           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.644           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.224           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.786           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.484           ms/op
```
