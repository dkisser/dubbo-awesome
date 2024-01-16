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
[INFO] benchmark-base ..................................... SUCCESS [  2.805 s]
[INFO] server-base ........................................ SUCCESS [  0.279 s]
[INFO] client-base ........................................ SUCCESS [  0.594 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.409 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  4.398 s
[INFO] Finished at: 2024-01-16T12:11:56Z
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
# Warmup Iteration   1: 5.469 ops/ms
# Warmup Iteration   2: 12.278 ops/ms
# Warmup Iteration   3: 12.533 ops/ms
Iteration   1: 12.652 ops/ms
Iteration   2: 12.903 ops/ms
Iteration   3: 12.791 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.782 ±(99.9%) 2.300 ops/ms [Average]
  (min, avg, max) = (12.652, 12.782, 12.903), stdev = 0.126
  CI (99.9%): [10.482, 15.082] (assumes normal distribution)


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
# Warmup Iteration   1: 8.525 ops/ms
# Warmup Iteration   2: 13.117 ops/ms
# Warmup Iteration   3: 13.360 ops/ms
Iteration   1: 13.541 ops/ms
Iteration   2: 13.556 ops/ms
Iteration   3: 13.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.528 ±(99.9%) 0.666 ops/ms [Average]
  (min, avg, max) = (13.487, 13.528, 13.556), stdev = 0.036
  CI (99.9%): [12.862, 14.194] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.114 ops/ms
# Warmup Iteration   2: 12.727 ops/ms
# Warmup Iteration   3: 12.761 ops/ms
Iteration   1: 12.816 ops/ms
Iteration   2: 12.661 ops/ms
Iteration   3: 12.908 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.795 ±(99.9%) 2.275 ops/ms [Average]
  (min, avg, max) = (12.661, 12.795, 12.908), stdev = 0.125
  CI (99.9%): [10.520, 15.070] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.947 ops/ms
# Warmup Iteration   2: 10.564 ops/ms
# Warmup Iteration   3: 10.891 ops/ms
Iteration   1: 11.035 ops/ms
Iteration   2: 10.942 ops/ms
Iteration   3: 10.979 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.985 ±(99.9%) 0.860 ops/ms [Average]
  (min, avg, max) = (10.942, 10.985, 11.035), stdev = 0.047
  CI (99.9%): [10.125, 11.845] (assumes normal distribution)


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
# Warmup Iteration   1: 3.996 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.626 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.005 ms/op
Iteration   1: 2.610 ±(99.9%) 0.005 ms/op
Iteration   2: 2.441 ±(99.9%) 0.004 ms/op
Iteration   3: 2.586 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.546 ±(99.9%) 1.673 ms/op [Average]
  (min, avg, max) = (2.441, 2.546, 2.610), stdev = 0.092
  CI (99.9%): [0.873, 4.218] (assumes normal distribution)


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
# Warmup Iteration   1: 4.280 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.818 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.781 ±(99.9%) 0.007 ms/op
Iteration   1: 2.707 ±(99.9%) 0.007 ms/op
Iteration   2: 2.797 ±(99.9%) 0.008 ms/op
Iteration   3: 2.757 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.754 ±(99.9%) 0.829 ms/op [Average]
  (min, avg, max) = (2.707, 2.754, 2.797), stdev = 0.045
  CI (99.9%): [1.925, 3.583] (assumes normal distribution)


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
# Warmup Iteration   1: 5.143 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.942 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.936 ±(99.9%) 0.009 ms/op
Iteration   1: 2.985 ±(99.9%) 0.008 ms/op
Iteration   2: 2.956 ±(99.9%) 0.011 ms/op
Iteration   3: 2.875 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.939 ±(99.9%) 1.039 ms/op [Average]
  (min, avg, max) = (2.875, 2.939, 2.985), stdev = 0.057
  CI (99.9%): [1.900, 3.977] (assumes normal distribution)


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
# Warmup Iteration   1: 5.947 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.525 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.404 ±(99.9%) 0.010 ms/op
Iteration   1: 3.296 ±(99.9%) 0.011 ms/op
Iteration   2: 3.413 ±(99.9%) 0.014 ms/op
Iteration   3: 3.449 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.386 ±(99.9%) 1.454 ms/op [Average]
  (min, avg, max) = (3.296, 3.386, 3.449), stdev = 0.080
  CI (99.9%): [1.932, 4.840] (assumes normal distribution)


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
# Warmup Iteration   1: 4.848 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 2.977 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 2.912 ±(99.9%) 0.011 ms/op
Iteration   1: 2.838 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.415 ms/op
                 createUser·p0.50:   2.687 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   6.966 ms/op
                 createUser·p0.999:  15.892 ms/op
                 createUser·p0.9999: 31.490 ms/op
                 createUser·p1.00:   32.965 ms/op

Iteration   2: 2.897 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.487 ms/op
                 createUser·p0.50:   2.736 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   8.006 ms/op
                 createUser·p0.999:  14.787 ms/op
                 createUser·p0.9999: 19.232 ms/op
                 createUser·p1.00:   22.151 ms/op

Iteration   3: 2.910 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.411 ms/op
                 createUser·p0.50:   2.736 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.489 ms/op
                 createUser·p0.99:   7.078 ms/op
                 createUser·p0.999:  13.697 ms/op
                 createUser·p0.9999: 20.808 ms/op
                 createUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 332847
  mean =      2.881 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 132937 
    [ 2.500,  5.000) = 189862 
    [ 5.000,  7.500) = 6930 
    [ 7.500, 10.000) = 2156 
    [10.000, 12.500) = 471 
    [12.500, 15.000) = 182 
    [15.000, 17.500) = 193 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.411 ms/op
     p(50.0000) =      2.720 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     14.538 ms/op
     p(99.9900) =     22.362 ms/op
     p(99.9990) =     32.211 ms/op
     p(99.9999) =     32.965 ms/op
    p(100.0000) =     32.965 ms/op


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
# Warmup Iteration   1: 4.762 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 2.870 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.891 ±(99.9%) 0.012 ms/op
Iteration   1: 2.833 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.452 ms/op
                 existUser·p0.50:   2.666 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   6.595 ms/op
                 existUser·p0.999:  12.604 ms/op
                 existUser·p0.9999: 36.551 ms/op
                 existUser·p1.00:   39.911 ms/op

Iteration   2: 2.814 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.406 ms/op
                 existUser·p0.50:   2.658 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   6.291 ms/op
                 existUser·p0.999:  11.837 ms/op
                 existUser·p0.9999: 33.313 ms/op
                 existUser·p1.00:   36.045 ms/op

Iteration   3: 2.852 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.524 ms/op
                 existUser·p0.50:   2.699 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   6.996 ms/op
                 existUser·p0.999:  13.007 ms/op
                 existUser·p0.9999: 19.588 ms/op
                 existUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 338425
  mean =      2.833 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 140221 
    [ 2.500,  5.000) = 188729 
    [ 5.000,  7.500) = 7382 
    [ 7.500, 10.000) = 1537 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.406 ms/op
     p(50.0000) =      2.675 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     12.854 ms/op
     p(99.9900) =     34.644 ms/op
     p(99.9990) =     37.502 ms/op
     p(99.9999) =     39.911 ms/op
    p(100.0000) =     39.911 ms/op


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
# Warmup Iteration   1: 4.878 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 2.966 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 2.824 ±(99.9%) 0.022 ms/op
Iteration   1: 2.833 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.534 ms/op
                 getUser·p0.50:   2.650 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   6.857 ms/op
                 getUser·p0.999:  15.165 ms/op
                 getUser·p0.9999: 25.264 ms/op
                 getUser·p1.00:   27.099 ms/op

Iteration   2: 2.940 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.742 ms/op
                 getUser·p0.50:   2.740 ms/op
                 getUser·p0.90:   4.059 ms/op
                 getUser·p0.95:   4.792 ms/op
                 getUser·p0.99:   7.184 ms/op
                 getUser·p0.999:  11.198 ms/op
                 getUser·p0.9999: 22.065 ms/op
                 getUser·p1.00:   23.298 ms/op

Iteration   3: 2.934 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.315 ms/op
                 getUser·p0.50:   2.683 ms/op
                 getUser·p0.90:   4.096 ms/op
                 getUser·p0.95:   4.997 ms/op
                 getUser·p0.99:   7.913 ms/op
                 getUser·p0.999:  13.288 ms/op
                 getUser·p0.9999: 23.658 ms/op
                 getUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 330562
  mean =      2.902 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 133021 
    [ 2.500,  5.000) = 183352 
    [ 5.000,  7.500) = 11176 
    [ 7.500, 10.000) = 2295 
    [10.000, 12.500) = 337 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.315 ms/op
     p(50.0000) =      2.691 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     13.920 ms/op
     p(99.9900) =     23.622 ms/op
     p(99.9990) =     26.578 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


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
# Warmup Iteration   1: 5.486 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 3.455 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.014 ms/op
Iteration   1: 3.305 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.542 ms/op
                 listUser·p0.50:   3.088 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   7.692 ms/op
                 listUser·p0.999:  13.959 ms/op
                 listUser·p0.9999: 16.272 ms/op
                 listUser·p1.00:   20.546 ms/op

Iteration   2: 3.354 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.373 ms/op
                 listUser·p0.50:   3.133 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   8.700 ms/op
                 listUser·p0.999:  14.287 ms/op
                 listUser·p0.9999: 17.415 ms/op
                 listUser·p1.00:   20.972 ms/op

Iteration   3: 3.415 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.428 ms/op
                 listUser·p0.50:   3.199 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   7.963 ms/op
                 listUser·p0.999:  15.211 ms/op
                 listUser·p0.9999: 20.206 ms/op
                 listUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 285722
  mean =      3.357 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 68613 
    [ 2.500,  5.000) = 196277 
    [ 5.000,  7.500) = 17125 
    [ 7.500, 10.000) = 2392 
    [10.000, 12.500) = 765 
    [12.500, 15.000) = 335 
    [15.000, 17.500) = 164 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.373 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      8.045 ms/op
     p(99.9000) =     14.418 ms/op
     p(99.9900) =     19.478 ms/op
     p(99.9990) =     20.803 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.782 ± 2.300  ops/ms
ClientPb.existUser                       thrpt       3  13.528 ± 0.666  ops/ms
ClientPb.getUser                         thrpt       3  12.795 ± 2.275  ops/ms
ClientPb.listUser                        thrpt       3  10.985 ± 0.860  ops/ms
ClientPb.createUser                       avgt       3   2.546 ± 1.673   ms/op
ClientPb.existUser                        avgt       3   2.754 ± 0.829   ms/op
ClientPb.getUser                          avgt       3   2.939 ± 1.039   ms/op
ClientPb.listUser                         avgt       3   3.386 ± 1.454   ms/op
ClientPb.createUser                     sample  332847   2.881 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.411           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.720           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.375           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.365           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.538           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.362           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.965           ms/op
ClientPb.existUser                      sample  338425   2.833 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.406           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.675           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.768           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.334           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.595           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.854           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.644           ms/op
ClientPb.existUser:existUser·p1.00      sample          39.911           ms/op
ClientPb.getUser                        sample  330562   2.902 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.315           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.691           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.022           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.801           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.365           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.920           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.622           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.099           ms/op
ClientPb.listUser                       sample  285722   3.357 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.373           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.142           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.678           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.423           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.045           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.418           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.478           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.168           ms/op
```
