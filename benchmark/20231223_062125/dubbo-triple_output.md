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
[INFO] benchmark-base ..................................... SUCCESS [  2.863 s]
[INFO] server-base ........................................ SUCCESS [  0.292 s]
[INFO] client-base ........................................ SUCCESS [  0.566 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.488 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  4.511 s
[INFO] Finished at: 2023-12-23T06:07:59Z
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
# Warmup Iteration   1: 5.358 ops/ms
# Warmup Iteration   2: 11.908 ops/ms
# Warmup Iteration   3: 12.204 ops/ms
Iteration   1: 12.354 ops/ms
Iteration   2: 12.417 ops/ms
Iteration   3: 12.407 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.393 ±(99.9%) 0.617 ops/ms [Average]
  (min, avg, max) = (12.354, 12.393, 12.417), stdev = 0.034
  CI (99.9%): [11.776, 13.010] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.419 ops/ms
# Warmup Iteration   2: 13.039 ops/ms
# Warmup Iteration   3: 12.942 ops/ms
Iteration   1: 12.973 ops/ms
Iteration   2: 13.123 ops/ms
Iteration   3: 12.912 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.003 ±(99.9%) 1.982 ops/ms [Average]
  (min, avg, max) = (12.912, 13.003, 13.123), stdev = 0.109
  CI (99.9%): [11.020, 14.985] (assumes normal distribution)


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
# Warmup Iteration   1: 8.136 ops/ms
# Warmup Iteration   2: 12.423 ops/ms
# Warmup Iteration   3: 12.617 ops/ms
Iteration   1: 12.731 ops/ms
Iteration   2: 12.784 ops/ms
Iteration   3: 12.677 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.731 ±(99.9%) 0.981 ops/ms [Average]
  (min, avg, max) = (12.677, 12.731, 12.784), stdev = 0.054
  CI (99.9%): [11.750, 13.711] (assumes normal distribution)


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
# Warmup Iteration   1: 6.625 ops/ms
# Warmup Iteration   2: 10.337 ops/ms
# Warmup Iteration   3: 10.491 ops/ms
Iteration   1: 10.491 ops/ms
Iteration   2: 10.574 ops/ms
Iteration   3: 10.527 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.531 ±(99.9%) 0.760 ops/ms [Average]
  (min, avg, max) = (10.491, 10.531, 10.574), stdev = 0.042
  CI (99.9%): [9.771, 11.291] (assumes normal distribution)


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
# Warmup Iteration   1: 4.045 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.641 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.005 ms/op
Iteration   1: 2.547 ±(99.9%) 0.004 ms/op
Iteration   2: 2.561 ±(99.9%) 0.004 ms/op
Iteration   3: 2.556 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.555 ±(99.9%) 0.134 ms/op [Average]
  (min, avg, max) = (2.547, 2.555, 2.561), stdev = 0.007
  CI (99.9%): [2.421, 2.689] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.678 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.452 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
Iteration   1: 2.443 ±(99.9%) 0.004 ms/op
Iteration   2: 2.457 ±(99.9%) 0.004 ms/op
Iteration   3: 2.453 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.451 ±(99.9%) 0.124 ms/op [Average]
  (min, avg, max) = (2.443, 2.451, 2.457), stdev = 0.007
  CI (99.9%): [2.327, 2.575] (assumes normal distribution)


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
# Warmup Iteration   1: 3.984 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.003 ms/op
Iteration   1: 2.514 ±(99.9%) 0.004 ms/op
Iteration   2: 2.497 ±(99.9%) 0.004 ms/op
Iteration   3: 2.494 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.502 ±(99.9%) 0.201 ms/op [Average]
  (min, avg, max) = (2.494, 2.502, 2.514), stdev = 0.011
  CI (99.9%): [2.301, 2.703] (assumes normal distribution)


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
# Warmup Iteration   1: 4.635 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.006 ms/op
Iteration   1: 3.060 ±(99.9%) 0.005 ms/op
Iteration   2: 3.061 ±(99.9%) 0.007 ms/op
Iteration   3: 3.071 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.064 ±(99.9%) 0.106 ms/op [Average]
  (min, avg, max) = (3.060, 3.064, 3.071), stdev = 0.006
  CI (99.9%): [2.959, 3.170] (assumes normal distribution)


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
# Warmup Iteration   1: 3.973 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.682 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.005 ms/op
Iteration   1: 2.553 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.863 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.637 ms/op
                 createUser·p0.999:  11.181 ms/op
                 createUser·p0.9999: 13.402 ms/op
                 createUser·p1.00:   15.057 ms/op

Iteration   2: 2.549 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.925 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.715 ms/op
                 createUser·p0.999:  8.998 ms/op
                 createUser·p0.9999: 11.639 ms/op
                 createUser·p1.00:   12.354 ms/op

Iteration   3: 2.576 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.013 ms/op
                 createUser·p0.50:   2.671 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   4.014 ms/op
                 createUser·p0.999:  9.028 ms/op
                 createUser·p0.9999: 11.551 ms/op
                 createUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 374590
  mean =      2.560 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 31 
    [ 1.250,  2.500) = 178795 
    [ 2.500,  3.750) = 191643 
    [ 3.750,  5.000) = 3299 
    [ 5.000,  6.250) = 367 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 128 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      2.646 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      9.034 ms/op
     p(99.9900) =     12.937 ms/op
     p(99.9990) =     14.148 ms/op
     p(99.9999) =     15.057 ms/op
    p(100.0000) =     15.057 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.828 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.522 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
Iteration   1: 2.482 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.890 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.654 ms/op
                 existUser·p0.999:  5.466 ms/op
                 existUser·p0.9999: 14.027 ms/op
                 existUser·p1.00:   14.270 ms/op

Iteration   2: 2.500 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.896 ms/op
                 existUser·p0.50:   2.617 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.846 ms/op
                 existUser·p0.999:  9.146 ms/op
                 existUser·p0.9999: 13.029 ms/op
                 existUser·p1.00:   14.287 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.891 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.826 ms/op
                 existUser·p0.999:  7.686 ms/op
                 existUser·p0.9999: 11.962 ms/op
                 existUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385502
  mean =      2.488 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 187946 
    [ 2.500,  3.750) = 193592 
    [ 3.750,  5.000) = 3090 
    [ 5.000,  6.250) = 405 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =      6.971 ms/op
     p(99.9900) =     13.213 ms/op
     p(99.9990) =     14.212 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


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
# Warmup Iteration   1: 4.008 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.585 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.006 ms/op
Iteration   1: 2.526 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.772 ms/op
                 getUser·p0.999:  6.043 ms/op
                 getUser·p0.9999: 13.490 ms/op
                 getUser·p1.00:   13.746 ms/op

Iteration   2: 2.550 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.905 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  9.191 ms/op
                 getUser·p0.9999: 13.389 ms/op
                 getUser·p1.00:   13.976 ms/op

Iteration   3: 2.527 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.999 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.613 ms/op
                 getUser·p0.999:  7.967 ms/op
                 getUser·p0.9999: 11.589 ms/op
                 getUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378419
  mean =      2.535 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 186450 
    [ 2.500,  3.750) = 187548 
    [ 3.750,  5.000) = 3231 
    [ 5.000,  6.250) = 700 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 123 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.850 ms/op
     p(99.9000) =      6.673 ms/op
     p(99.9900) =     13.243 ms/op
     p(99.9990) =     13.864 ms/op
     p(99.9999) =     13.976 ms/op
    p(100.0000) =     13.976 ms/op


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
# Warmup Iteration   1: 4.911 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.009 ms/op
Iteration   1: 3.060 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.815 ms/op
                 listUser·p0.50:   2.994 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.110 ms/op
                 listUser·p0.9999: 10.945 ms/op
                 listUser·p1.00:   11.141 ms/op

Iteration   2: 3.056 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.690 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.486 ms/op
                 listUser·p0.9999: 11.005 ms/op
                 listUser·p1.00:   11.698 ms/op

Iteration   3: 3.034 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.923 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.251 ms/op
                 listUser·p0.9999: 11.125 ms/op
                 listUser·p1.00:   12.370 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314468
  mean =      3.050 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 134 
    [ 1.250,  2.500) = 84895 
    [ 2.500,  3.750) = 187399 
    [ 3.750,  5.000) = 34525 
    [ 5.000,  6.250) = 6357 
    [ 6.250,  7.500) = 494 
    [ 7.500,  8.750) = 229 
    [ 8.750, 10.000) = 261 
    [10.000, 11.250) = 161 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.224 ms/op
     p(99.9900) =     11.019 ms/op
     p(99.9990) =     11.768 ms/op
     p(99.9999) =     12.370 ms/op
    p(100.0000) =     12.370 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.393 ± 0.617  ops/ms
ClientPb.existUser                       thrpt       3  13.003 ± 1.982  ops/ms
ClientPb.getUser                         thrpt       3  12.731 ± 0.981  ops/ms
ClientPb.listUser                        thrpt       3  10.531 ± 0.760  ops/ms
ClientPb.createUser                       avgt       3   2.555 ± 0.134   ms/op
ClientPb.existUser                        avgt       3   2.451 ± 0.124   ms/op
ClientPb.getUser                          avgt       3   2.502 ± 0.201   ms/op
ClientPb.listUser                         avgt       3   3.064 ± 0.106   ms/op
ClientPb.createUser                     sample  374590   2.560 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.863           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.646           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.034           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.937           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.057           ms/op
ClientPb.existUser                      sample  385502   2.488 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.890           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.556           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.971           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.213           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.287           ms/op
ClientPb.getUser                        sample  378419   2.535 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.905           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.673           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.243           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.976           ms/op
ClientPb.listUser                       sample  314468   3.050 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.690           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.994           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.944           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.224           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.019           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.370           ms/op
```
