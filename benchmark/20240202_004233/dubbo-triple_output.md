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
[INFO] benchmark-base ..................................... SUCCESS [  2.931 s]
[INFO] server-base ........................................ SUCCESS [  0.333 s]
[INFO] client-base ........................................ SUCCESS [  0.644 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.529 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  4.750 s
[INFO] Finished at: 2024-02-02T00:29:03Z
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
# Warmup Iteration   1: 4.808 ops/ms
# Warmup Iteration   2: 11.884 ops/ms
# Warmup Iteration   3: 12.174 ops/ms
Iteration   1: 12.448 ops/ms
Iteration   2: 12.582 ops/ms
Iteration   3: 12.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.491 ±(99.9%) 1.438 ops/ms [Average]
  (min, avg, max) = (12.444, 12.491, 12.582), stdev = 0.079
  CI (99.9%): [11.053, 13.929] (assumes normal distribution)


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
# Warmup Iteration   1: 7.738 ops/ms
# Warmup Iteration   2: 12.775 ops/ms
# Warmup Iteration   3: 12.932 ops/ms
Iteration   1: 12.872 ops/ms
Iteration   2: 12.966 ops/ms
Iteration   3: 12.925 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.921 ±(99.9%) 0.858 ops/ms [Average]
  (min, avg, max) = (12.872, 12.921, 12.966), stdev = 0.047
  CI (99.9%): [12.063, 13.779] (assumes normal distribution)


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
# Warmup Iteration   1: 7.417 ops/ms
# Warmup Iteration   2: 12.427 ops/ms
# Warmup Iteration   3: 12.554 ops/ms
Iteration   1: 12.734 ops/ms
Iteration   2: 12.574 ops/ms
Iteration   3: 12.684 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.664 ±(99.9%) 1.493 ops/ms [Average]
  (min, avg, max) = (12.574, 12.664, 12.734), stdev = 0.082
  CI (99.9%): [11.172, 14.157] (assumes normal distribution)


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
# Warmup Iteration   1: 6.466 ops/ms
# Warmup Iteration   2: 10.452 ops/ms
# Warmup Iteration   3: 10.470 ops/ms
Iteration   1: 10.555 ops/ms
Iteration   2: 10.581 ops/ms
Iteration   3: 10.447 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.527 ±(99.9%) 1.297 ops/ms [Average]
  (min, avg, max) = (10.447, 10.527, 10.581), stdev = 0.071
  CI (99.9%): [9.231, 11.824] (assumes normal distribution)


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
# Warmup Iteration   1: 4.118 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.593 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.557 ±(99.9%) 0.004 ms/op
Iteration   1: 2.556 ±(99.9%) 0.003 ms/op
Iteration   2: 2.594 ±(99.9%) 0.005 ms/op
Iteration   3: 2.575 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.575 ±(99.9%) 0.350 ms/op [Average]
  (min, avg, max) = (2.556, 2.575, 2.594), stdev = 0.019
  CI (99.9%): [2.226, 2.925] (assumes normal distribution)


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
# Warmup Iteration   1: 3.553 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.470 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.004 ms/op
Iteration   1: 2.484 ±(99.9%) 0.004 ms/op
Iteration   2: 2.451 ±(99.9%) 0.004 ms/op
Iteration   3: 2.455 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.463 ±(99.9%) 0.327 ms/op [Average]
  (min, avg, max) = (2.451, 2.463, 2.484), stdev = 0.018
  CI (99.9%): [2.136, 2.790] (assumes normal distribution)


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
# Warmup Iteration   1: 4.038 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.004 ms/op
Iteration   1: 2.514 ±(99.9%) 0.004 ms/op
Iteration   2: 2.516 ±(99.9%) 0.003 ms/op
Iteration   3: 2.556 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.529 ±(99.9%) 0.439 ms/op [Average]
  (min, avg, max) = (2.514, 2.529, 2.556), stdev = 0.024
  CI (99.9%): [2.090, 2.968] (assumes normal distribution)


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
# Warmup Iteration   1: 4.897 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.007 ms/op
Iteration   1: 3.057 ±(99.9%) 0.007 ms/op
Iteration   2: 3.055 ±(99.9%) 0.006 ms/op
Iteration   3: 3.038 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.050 ±(99.9%) 0.189 ms/op [Average]
  (min, avg, max) = (3.038, 3.050, 3.057), stdev = 0.010
  CI (99.9%): [2.861, 3.239] (assumes normal distribution)


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
# Warmup Iteration   1: 4.112 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.712 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.567 ±(99.9%) 0.006 ms/op
Iteration   1: 2.575 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.025 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.273 ms/op
                 createUser·p0.99:   4.112 ms/op
                 createUser·p0.999:  11.727 ms/op
                 createUser·p0.9999: 15.958 ms/op
                 createUser·p1.00:   16.318 ms/op

Iteration   2: 2.556 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.961 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.797 ms/op
                 createUser·p0.999:  9.391 ms/op
                 createUser·p0.9999: 13.468 ms/op
                 createUser·p1.00:   14.647 ms/op

Iteration   3: 2.545 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.034 ms/op
                 createUser·p0.50:   2.595 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.690 ms/op
                 createUser·p0.999:  8.831 ms/op
                 createUser·p0.9999: 10.535 ms/op
                 createUser·p1.00:   12.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374804
  mean =      2.559 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 179629 
    [ 2.500,  3.750) = 190597 
    [ 3.750,  5.000) = 3602 
    [ 5.000,  6.250) = 479 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 134 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.961 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      3.863 ms/op
     p(99.9000) =      8.851 ms/op
     p(99.9900) =     14.608 ms/op
     p(99.9990) =     16.192 ms/op
     p(99.9999) =     16.318 ms/op
    p(100.0000) =     16.318 ms/op


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
# Warmup Iteration   1: 3.811 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
Iteration   1: 2.492 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.614 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.609 ms/op
                 existUser·p0.999:  11.193 ms/op
                 existUser·p0.9999: 13.615 ms/op
                 existUser·p1.00:   15.041 ms/op

Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.081 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  8.569 ms/op
                 existUser·p0.9999: 13.519 ms/op
                 existUser·p1.00:   13.795 ms/op

Iteration   3: 2.514 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.510 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.064 ms/op
                 existUser·p0.95:   3.178 ms/op
                 existUser·p0.99:   3.723 ms/op
                 existUser·p0.999:  8.036 ms/op
                 existUser·p0.9999: 11.665 ms/op
                 existUser·p1.00:   12.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384132
  mean =      2.496 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 188354 
    [ 2.500,  3.750) = 192524 
    [ 3.750,  5.000) = 2466 
    [ 5.000,  6.250) = 267 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 118 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 122 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.658 ms/op
     p(99.9000) =      8.338 ms/op
     p(99.9900) =     13.418 ms/op
     p(99.9990) =     14.167 ms/op
     p(99.9999) =     15.041 ms/op
    p(100.0000) =     15.041 ms/op


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
# Warmup Iteration   1: 3.956 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.611 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.006 ms/op
Iteration   1: 2.501 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.977 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.265 ms/op
                 getUser·p0.99:   4.162 ms/op
                 getUser·p0.999:  11.492 ms/op
                 getUser·p0.9999: 14.040 ms/op
                 getUser·p1.00:   15.155 ms/op

Iteration   2: 2.494 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.912 ms/op
                 getUser·p0.50:   2.449 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.371 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  9.050 ms/op
                 getUser·p0.9999: 13.634 ms/op
                 getUser·p1.00:   14.778 ms/op

Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.885 ms/op
                 getUser·p0.50:   2.458 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.908 ms/op
                 getUser·p0.999:  6.947 ms/op
                 getUser·p0.9999: 11.474 ms/op
                 getUser·p1.00:   12.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385329
  mean =      2.489 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 113 
    [ 1.250,  2.500) = 197699 
    [ 2.500,  3.750) = 180095 
    [ 3.750,  5.000) = 6012 
    [ 5.000,  6.250) = 944 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      2.462 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.260 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      8.359 ms/op
     p(99.9900) =     13.861 ms/op
     p(99.9990) =     14.987 ms/op
     p(99.9999) =     15.155 ms/op
    p(100.0000) =     15.155 ms/op


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
# Warmup Iteration   1: 4.795 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.009 ms/op
Iteration   1: 3.051 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.901 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.142 ms/op
                 listUser·p0.9999: 12.445 ms/op
                 listUser·p1.00:   14.238 ms/op

Iteration   2: 3.035 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.025 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  8.990 ms/op
                 listUser·p0.9999: 10.868 ms/op
                 listUser·p1.00:   11.436 ms/op

Iteration   3: 3.046 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.002 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.519 ms/op
                 listUser·p0.9999: 10.863 ms/op
                 listUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315079
  mean =      3.044 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 98 
    [ 1.250,  2.500) = 85371 
    [ 2.500,  3.750) = 187987 
    [ 3.750,  5.000) = 34869 
    [ 5.000,  6.250) = 5483 
    [ 6.250,  7.500) = 650 
    [ 7.500,  8.750) = 200 
    [ 8.750, 10.000) = 279 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.901 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     10.920 ms/op
     p(99.9990) =     12.838 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.491 ± 1.438  ops/ms
ClientPb.existUser                       thrpt       3  12.921 ± 0.858  ops/ms
ClientPb.getUser                         thrpt       3  12.664 ± 1.493  ops/ms
ClientPb.listUser                        thrpt       3  10.527 ± 1.297  ops/ms
ClientPb.createUser                       avgt       3   2.575 ± 0.350   ms/op
ClientPb.existUser                        avgt       3   2.463 ± 0.327   ms/op
ClientPb.getUser                          avgt       3   2.529 ± 0.439   ms/op
ClientPb.listUser                         avgt       3   3.050 ± 0.189   ms/op
ClientPb.createUser                     sample  374804   2.559 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.961           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.236           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.863           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.851           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.608           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.318           ms/op
ClientPb.existUser                      sample  384132   2.496 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.510           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.548           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.338           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.418           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.041           ms/op
ClientPb.getUser                        sample  385329   2.489 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.885           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.462           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.260           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.243           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.359           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.861           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.155           ms/op
ClientPb.listUser                       sample  315079   3.044 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.901           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.538           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.241           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.920           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.238           ms/op
```
