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
[INFO] benchmark-base ..................................... SUCCESS [  3.078 s]
[INFO] server-base ........................................ SUCCESS [  0.346 s]
[INFO] client-base ........................................ SUCCESS [  0.655 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.480 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  4.887 s
[INFO] Finished at: 2024-01-14T06:08:21Z
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
# Warmup Iteration   1: 4.733 ops/ms
# Warmup Iteration   2: 12.011 ops/ms
# Warmup Iteration   3: 12.247 ops/ms
Iteration   1: 12.470 ops/ms
Iteration   2: 12.509 ops/ms
Iteration   3: 12.492 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.490 ±(99.9%) 0.362 ops/ms [Average]
  (min, avg, max) = (12.470, 12.490, 12.509), stdev = 0.020
  CI (99.9%): [12.128, 12.853] (assumes normal distribution)


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
# Warmup Iteration   1: 7.978 ops/ms
# Warmup Iteration   2: 13.157 ops/ms
# Warmup Iteration   3: 13.121 ops/ms
Iteration   1: 13.122 ops/ms
Iteration   2: 12.935 ops/ms
Iteration   3: 13.081 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.046 ±(99.9%) 1.792 ops/ms [Average]
  (min, avg, max) = (12.935, 13.046, 13.122), stdev = 0.098
  CI (99.9%): [11.254, 14.838] (assumes normal distribution)


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
# Warmup Iteration   1: 8.228 ops/ms
# Warmup Iteration   2: 12.582 ops/ms
# Warmup Iteration   3: 12.793 ops/ms
Iteration   1: 12.960 ops/ms
Iteration   2: 12.988 ops/ms
Iteration   3: 12.950 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.966 ±(99.9%) 0.362 ops/ms [Average]
  (min, avg, max) = (12.950, 12.966, 12.988), stdev = 0.020
  CI (99.9%): [12.604, 13.328] (assumes normal distribution)


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
# Warmup Iteration   1: 6.792 ops/ms
# Warmup Iteration   2: 10.688 ops/ms
# Warmup Iteration   3: 10.734 ops/ms
Iteration   1: 10.693 ops/ms
Iteration   2: 10.748 ops/ms
Iteration   3: 10.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.750 ±(99.9%) 1.043 ops/ms [Average]
  (min, avg, max) = (10.693, 10.750, 10.807), stdev = 0.057
  CI (99.9%): [9.707, 11.793] (assumes normal distribution)


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
# Warmup Iteration   1: 3.851 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.520 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.004 ms/op
Iteration   1: 2.505 ±(99.9%) 0.004 ms/op
Iteration   2: 2.520 ±(99.9%) 0.004 ms/op
Iteration   3: 2.486 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.504 ±(99.9%) 0.316 ms/op [Average]
  (min, avg, max) = (2.486, 2.504, 2.520), stdev = 0.017
  CI (99.9%): [2.188, 2.819] (assumes normal distribution)


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
# Warmup Iteration   1: 3.741 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.461 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.004 ms/op
Iteration   1: 2.444 ±(99.9%) 0.005 ms/op
Iteration   2: 2.416 ±(99.9%) 0.004 ms/op
Iteration   3: 2.416 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.426 ±(99.9%) 0.298 ms/op [Average]
  (min, avg, max) = (2.416, 2.426, 2.444), stdev = 0.016
  CI (99.9%): [2.127, 2.724] (assumes normal distribution)


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
# Warmup Iteration   1: 3.733 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.488 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.004 ms/op
Iteration   1: 2.448 ±(99.9%) 0.003 ms/op
Iteration   2: 2.460 ±(99.9%) 0.003 ms/op
Iteration   3: 2.467 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.458 ±(99.9%) 0.180 ms/op [Average]
  (min, avg, max) = (2.448, 2.458, 2.467), stdev = 0.010
  CI (99.9%): [2.279, 2.638] (assumes normal distribution)


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
# Warmup Iteration   1: 4.788 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.994 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.006 ms/op
Iteration   1: 2.982 ±(99.9%) 0.006 ms/op
Iteration   2: 2.954 ±(99.9%) 0.005 ms/op
Iteration   3: 2.968 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.968 ±(99.9%) 0.256 ms/op [Average]
  (min, avg, max) = (2.954, 2.968, 2.982), stdev = 0.014
  CI (99.9%): [2.712, 3.224] (assumes normal distribution)


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
# Warmup Iteration   1: 4.044 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.005 ms/op
Iteration   1: 2.465 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.843 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   3.700 ms/op
                 createUser·p0.999:  6.954 ms/op
                 createUser·p0.9999: 14.009 ms/op
                 createUser·p1.00:   14.631 ms/op

Iteration   2: 2.475 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.004 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.592 ms/op
                 createUser·p0.999:  7.626 ms/op
                 createUser·p0.9999: 11.944 ms/op
                 createUser·p1.00:   12.845 ms/op

Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.980 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.833 ms/op
                 createUser·p0.999:  9.093 ms/op
                 createUser·p0.9999: 10.794 ms/op
                 createUser·p1.00:   11.338 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387251
  mean =      2.477 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 188914 
    [ 2.500,  3.750) = 194716 
    [ 3.750,  5.000) = 2833 
    [ 5.000,  6.250) = 265 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 150 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.711 ms/op
     p(99.9000) =      9.056 ms/op
     p(99.9900) =     13.337 ms/op
     p(99.9990) =     14.486 ms/op
     p(99.9999) =     14.631 ms/op
    p(100.0000) =     14.631 ms/op


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
# Warmup Iteration   1: 3.662 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.481 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.426 ±(99.9%) 0.005 ms/op
Iteration   1: 2.412 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.822 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.523 ms/op
                 existUser·p0.999:  5.753 ms/op
                 existUser·p0.9999: 14.025 ms/op
                 existUser·p1.00:   14.942 ms/op

Iteration   2: 2.422 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.958 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.633 ms/op
                 existUser·p0.999:  6.619 ms/op
                 existUser·p0.9999: 13.281 ms/op
                 existUser·p1.00:   13.877 ms/op

Iteration   3: 2.430 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.795 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  8.233 ms/op
                 existUser·p0.9999: 11.906 ms/op
                 existUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396094
  mean =      2.421 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 201366 
    [ 2.500,  3.750) = 190800 
    [ 3.750,  5.000) = 3067 
    [ 5.000,  6.250) = 266 
    [ 6.250,  7.500) = 118 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      2.945 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      7.716 ms/op
     p(99.9900) =     13.435 ms/op
     p(99.9990) =     14.894 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


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
# Warmup Iteration   1: 3.854 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.503 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.006 ms/op
Iteration   1: 2.426 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.625 ms/op
                 getUser·p0.50:   2.384 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.854 ms/op
                 getUser·p0.999:  6.179 ms/op
                 getUser·p0.9999: 14.132 ms/op
                 getUser·p1.00:   14.778 ms/op

Iteration   2: 2.480 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.004 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   4.100 ms/op
                 getUser·p0.999:  9.213 ms/op
                 getUser·p0.9999: 12.062 ms/op
                 getUser·p1.00:   12.386 ms/op

Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.977 ms/op
                 getUser·p0.999:  8.798 ms/op
                 getUser·p0.9999: 11.919 ms/op
                 getUser·p1.00:   13.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389095
  mean =      2.465 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 161 
    [ 1.250,  2.500) = 203916 
    [ 2.500,  3.750) = 179485 
    [ 3.750,  5.000) = 4610 
    [ 5.000,  6.250) = 469 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      2.433 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.969 ms/op
     p(99.9000) =      7.644 ms/op
     p(99.9900) =     13.484 ms/op
     p(99.9990) =     14.618 ms/op
     p(99.9999) =     14.778 ms/op
    p(100.0000) =     14.778 ms/op


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
# Warmup Iteration   1: 4.572 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.032 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.008 ms/op
Iteration   1: 2.961 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.763 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.306 ms/op
                 listUser·p0.9999: 10.804 ms/op
                 listUser·p1.00:   13.042 ms/op

Iteration   2: 2.954 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.002 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.781 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   5.415 ms/op
                 listUser·p0.999:  9.716 ms/op
                 listUser·p0.9999: 10.552 ms/op
                 listUser·p1.00:   11.239 ms/op

Iteration   3: 2.962 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.782 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.568 ms/op
                 listUser·p0.9999: 11.063 ms/op
                 listUser·p1.00:   11.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 324155
  mean =      2.959 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 101241 
    [ 2.500,  3.750) = 187647 
    [ 3.750,  5.000) = 28524 
    [ 5.000,  6.250) = 5352 
    [ 6.250,  7.500) = 559 
    [ 7.500,  8.750) = 189 
    [ 8.750, 10.000) = 351 
    [10.000, 11.250) = 165 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =      9.535 ms/op
     p(99.9900) =     10.938 ms/op
     p(99.9990) =     11.950 ms/op
     p(99.9999) =     13.042 ms/op
    p(100.0000) =     13.042 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.490 ± 0.362  ops/ms
ClientPb.existUser                       thrpt       3  13.046 ± 1.792  ops/ms
ClientPb.getUser                         thrpt       3  12.966 ± 0.362  ops/ms
ClientPb.listUser                        thrpt       3  10.750 ± 1.043  ops/ms
ClientPb.createUser                       avgt       3   2.504 ± 0.316   ms/op
ClientPb.existUser                        avgt       3   2.426 ± 0.298   ms/op
ClientPb.getUser                          avgt       3   2.458 ± 0.180   ms/op
ClientPb.listUser                         avgt       3   2.968 ± 0.256   ms/op
ClientPb.createUser                     sample  387251   2.477 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.843           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.544           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.011           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.711           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.056           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.337           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.631           ms/op
ClientPb.existUser                      sample  396094   2.421 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.795           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.470           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.945           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.716           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.435           ms/op
ClientPb.existUser:existUser·p1.00      sample          19.759           ms/op
ClientPb.getUser                        sample  389095   2.465 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.625           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.433           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.969           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.644           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.484           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.778           ms/op
ClientPb.listUser                       sample  324155   2.959 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.763           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.892           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.805           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.535           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.938           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.042           ms/op
```
