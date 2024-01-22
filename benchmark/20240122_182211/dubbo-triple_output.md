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
[INFO] benchmark-base ..................................... SUCCESS [  3.014 s]
[INFO] server-base ........................................ SUCCESS [  0.357 s]
[INFO] client-base ........................................ SUCCESS [  0.630 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.484 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  4.821 s
[INFO] Finished at: 2024-01-22T18:08:40Z
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
# Warmup Iteration   1: 4.667 ops/ms
# Warmup Iteration   2: 11.997 ops/ms
# Warmup Iteration   3: 12.526 ops/ms
Iteration   1: 12.735 ops/ms
Iteration   2: 12.524 ops/ms
Iteration   3: 12.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.614 ±(99.9%) 1.988 ops/ms [Average]
  (min, avg, max) = (12.524, 12.614, 12.735), stdev = 0.109
  CI (99.9%): [10.626, 14.602] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.836 ops/ms
# Warmup Iteration   2: 12.925 ops/ms
# Warmup Iteration   3: 12.960 ops/ms
Iteration   1: 13.028 ops/ms
Iteration   2: 12.970 ops/ms
Iteration   3: 12.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.995 ±(99.9%) 0.544 ops/ms [Average]
  (min, avg, max) = (12.970, 12.995, 13.028), stdev = 0.030
  CI (99.9%): [12.451, 13.540] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.265 ops/ms
# Warmup Iteration   2: 12.646 ops/ms
# Warmup Iteration   3: 12.763 ops/ms
Iteration   1: 12.883 ops/ms
Iteration   2: 12.851 ops/ms
Iteration   3: 12.850 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.861 ±(99.9%) 0.339 ops/ms [Average]
  (min, avg, max) = (12.850, 12.861, 12.883), stdev = 0.019
  CI (99.9%): [12.522, 13.201] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.470 ops/ms
# Warmup Iteration   2: 10.475 ops/ms
# Warmup Iteration   3: 10.566 ops/ms
Iteration   1: 10.595 ops/ms
Iteration   2: 10.533 ops/ms
Iteration   3: 10.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.541 ±(99.9%) 0.909 ops/ms [Average]
  (min, avg, max) = (10.496, 10.541, 10.595), stdev = 0.050
  CI (99.9%): [9.632, 11.451] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.213 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.683 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.005 ms/op
Iteration   1: 2.588 ±(99.9%) 0.004 ms/op
Iteration   2: 2.590 ±(99.9%) 0.003 ms/op
Iteration   3: 2.582 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.587 ±(99.9%) 0.074 ms/op [Average]
  (min, avg, max) = (2.582, 2.587, 2.590), stdev = 0.004
  CI (99.9%): [2.513, 2.660] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.744 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.503 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.003 ms/op
Iteration   1: 2.493 ±(99.9%) 0.003 ms/op
Iteration   2: 2.504 ±(99.9%) 0.005 ms/op
Iteration   3: 2.532 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.510 ±(99.9%) 0.369 ms/op [Average]
  (min, avg, max) = (2.493, 2.510, 2.532), stdev = 0.020
  CI (99.9%): [2.141, 2.879] (assumes normal distribution)


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
# Warmup Iteration   1: 4.092 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.571 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.004 ms/op
Iteration   1: 2.499 ±(99.9%) 0.003 ms/op
Iteration   2: 2.509 ±(99.9%) 0.004 ms/op
Iteration   3: 2.499 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.503 ±(99.9%) 0.103 ms/op [Average]
  (min, avg, max) = (2.499, 2.503, 2.509), stdev = 0.006
  CI (99.9%): [2.400, 2.605] (assumes normal distribution)


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
# Warmup Iteration   1: 4.660 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.005 ms/op
Iteration   1: 3.042 ±(99.9%) 0.005 ms/op
Iteration   2: 3.057 ±(99.9%) 0.006 ms/op
Iteration   3: 3.034 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.044 ±(99.9%) 0.213 ms/op [Average]
  (min, avg, max) = (3.034, 3.044, 3.057), stdev = 0.012
  CI (99.9%): [2.831, 3.257] (assumes normal distribution)


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
# Warmup Iteration   1: 4.488 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 2.738 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.562 ±(99.9%) 0.006 ms/op
Iteration   1: 2.558 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.948 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.883 ms/op
                 createUser·p0.999:  11.814 ms/op
                 createUser·p0.9999: 13.566 ms/op
                 createUser·p1.00:   14.287 ms/op

Iteration   2: 2.546 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.889 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.633 ms/op
                 createUser·p0.999:  9.631 ms/op
                 createUser·p0.9999: 14.376 ms/op
                 createUser·p1.00:   15.385 ms/op

Iteration   3: 2.561 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.732 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   3.908 ms/op
                 createUser·p0.999:  9.561 ms/op
                 createUser·p0.9999: 13.349 ms/op
                 createUser·p1.00:   13.894 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375346
  mean =      2.555 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 178484 
    [ 2.500,  3.750) = 192667 
    [ 3.750,  5.000) = 3445 
    [ 5.000,  6.250) = 280 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 119 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      3.813 ms/op
     p(99.9000) =      9.644 ms/op
     p(99.9900) =     13.779 ms/op
     p(99.9990) =     14.707 ms/op
     p(99.9999) =     15.385 ms/op
    p(100.0000) =     15.385 ms/op


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
# Warmup Iteration   1: 3.748 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
Iteration   1: 2.507 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.861 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.064 ms/op
                 existUser·p0.95:   3.191 ms/op
                 existUser·p0.99:   3.748 ms/op
                 existUser·p0.999:  11.387 ms/op
                 existUser·p0.9999: 13.943 ms/op
                 existUser·p1.00:   14.631 ms/op

Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  9.544 ms/op
                 existUser·p0.9999: 14.369 ms/op
                 existUser·p1.00:   14.893 ms/op

Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.986 ms/op
                 existUser·p0.50:   2.597 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   3.608 ms/op
                 existUser·p0.999:  5.488 ms/op
                 existUser·p0.9999: 12.029 ms/op
                 existUser·p1.00:   12.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 383260
  mean =      2.503 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 185418 
    [ 2.500,  3.750) = 194473 
    [ 3.750,  5.000) = 2586 
    [ 5.000,  6.250) = 330 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 94 
    [13.750, 15.000) = 59 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.682 ms/op
     p(99.9000) =      6.678 ms/op
     p(99.9900) =     13.921 ms/op
     p(99.9990) =     14.590 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


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
# Warmup Iteration   1: 4.310 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 2.580 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.006 ms/op
Iteration   1: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.707 ms/op
                 getUser·p0.999:  7.991 ms/op
                 getUser·p0.9999: 14.567 ms/op
                 getUser·p1.00:   15.057 ms/op

Iteration   2: 2.529 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.051 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.645 ms/op
                 getUser·p0.999:  10.128 ms/op
                 getUser·p0.9999: 13.468 ms/op
                 getUser·p1.00:   13.877 ms/op

Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.775 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.768 ms/op
                 getUser·p0.999:  8.176 ms/op
                 getUser·p0.9999: 12.029 ms/op
                 getUser·p1.00:   13.058 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383280
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 189597 
    [ 2.500,  3.750) = 188522 
    [ 3.750,  5.000) = 3777 
    [ 5.000,  6.250) = 877 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.949 ms/op
     p(99.9000) =      8.176 ms/op
     p(99.9900) =     13.686 ms/op
     p(99.9990) =     14.748 ms/op
     p(99.9999) =     15.057 ms/op
    p(100.0000) =     15.057 ms/op


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
# Warmup Iteration   1: 5.029 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.009 ms/op
Iteration   1: 3.007 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.830 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  10.251 ms/op
                 listUser·p0.9999: 12.488 ms/op
                 listUser·p1.00:   13.304 ms/op

Iteration   2: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.920 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.617 ms/op
                 listUser·p0.9999: 12.304 ms/op
                 listUser·p1.00:   14.598 ms/op

Iteration   3: 3.019 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.857 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.308 ms/op
                 listUser·p0.9999: 11.246 ms/op
                 listUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318589
  mean =      3.011 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 105 
    [ 1.250,  2.500) = 90305 
    [ 2.500,  3.750) = 189859 
    [ 3.750,  5.000) = 31325 
    [ 5.000,  6.250) = 5567 
    [ 6.250,  7.500) = 698 
    [ 7.500,  8.750) = 197 
    [ 8.750, 10.000) = 279 
    [10.000, 11.250) = 169 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.830 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.617 ms/op
     p(99.9900) =     12.222 ms/op
     p(99.9990) =     13.317 ms/op
     p(99.9999) =     14.598 ms/op
    p(100.0000) =     14.598 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.614 ± 1.988  ops/ms
ClientPb.existUser                       thrpt       3  12.995 ± 0.544  ops/ms
ClientPb.getUser                         thrpt       3  12.861 ± 0.339  ops/ms
ClientPb.listUser                        thrpt       3  10.541 ± 0.909  ops/ms
ClientPb.createUser                       avgt       3   2.587 ± 0.074   ms/op
ClientPb.existUser                        avgt       3   2.510 ± 0.369   ms/op
ClientPb.getUser                          avgt       3   2.503 ± 0.103   ms/op
ClientPb.listUser                         avgt       3   3.044 ± 0.213   ms/op
ClientPb.createUser                     sample  375346   2.555 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.732           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.630           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.813           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.644           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.779           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.385           ms/op
ClientPb.existUser                      sample  383260   2.503 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.861           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.572           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.162           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.678           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.921           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.893           ms/op
ClientPb.getUser                        sample  383280   2.502 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.775           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.176           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.686           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.057           ms/op
ClientPb.listUser                       sample  318589   3.011 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.830           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.617           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.222           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.598           ms/op
```
