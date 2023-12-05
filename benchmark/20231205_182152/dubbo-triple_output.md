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
[INFO] benchmark-base ..................................... SUCCESS [  2.797 s]
[INFO] server-base ........................................ SUCCESS [  0.276 s]
[INFO] client-base ........................................ SUCCESS [  0.640 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.394 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  4.413 s
[INFO] Finished at: 2023-12-05T18:08:30Z
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
# Warmup Iteration   1: 4.915 ops/ms
# Warmup Iteration   2: 11.668 ops/ms
# Warmup Iteration   3: 12.211 ops/ms
Iteration   1: 12.290 ops/ms
Iteration   2: 12.371 ops/ms
Iteration   3: 12.474 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.379 ±(99.9%) 1.681 ops/ms [Average]
  (min, avg, max) = (12.290, 12.379, 12.474), stdev = 0.092
  CI (99.9%): [10.698, 14.059] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.102 ops/ms
# Warmup Iteration   2: 13.102 ops/ms
# Warmup Iteration   3: 13.240 ops/ms
Iteration   1: 13.134 ops/ms
Iteration   2: 13.064 ops/ms
Iteration   3: 13.059 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.086 ±(99.9%) 0.760 ops/ms [Average]
  (min, avg, max) = (13.059, 13.086, 13.134), stdev = 0.042
  CI (99.9%): [12.326, 13.845] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.050 ops/ms
# Warmup Iteration   2: 12.707 ops/ms
# Warmup Iteration   3: 12.895 ops/ms
Iteration   1: 12.647 ops/ms
Iteration   2: 12.889 ops/ms
Iteration   3: 12.824 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.787 ±(99.9%) 2.288 ops/ms [Average]
  (min, avg, max) = (12.647, 12.787, 12.889), stdev = 0.125
  CI (99.9%): [10.499, 15.074] (assumes normal distribution)


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
# Warmup Iteration   1: 6.431 ops/ms
# Warmup Iteration   2: 10.252 ops/ms
# Warmup Iteration   3: 10.434 ops/ms
Iteration   1: 10.484 ops/ms
Iteration   2: 10.593 ops/ms
Iteration   3: 10.455 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.511 ±(99.9%) 1.322 ops/ms [Average]
  (min, avg, max) = (10.455, 10.511, 10.593), stdev = 0.072
  CI (99.9%): [9.189, 11.833] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.816 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.540 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.003 ms/op
Iteration   1: 2.498 ±(99.9%) 0.004 ms/op
Iteration   2: 2.528 ±(99.9%) 0.004 ms/op
Iteration   3: 2.486 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.504 ±(99.9%) 0.399 ms/op [Average]
  (min, avg, max) = (2.486, 2.504, 2.528), stdev = 0.022
  CI (99.9%): [2.105, 2.903] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.699 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.448 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.444 ±(99.9%) 0.004 ms/op
Iteration   1: 2.401 ±(99.9%) 0.004 ms/op
Iteration   2: 2.425 ±(99.9%) 0.004 ms/op
Iteration   3: 2.419 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.415 ±(99.9%) 0.231 ms/op [Average]
  (min, avg, max) = (2.401, 2.415, 2.425), stdev = 0.013
  CI (99.9%): [2.184, 2.646] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.971 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.004 ms/op
Iteration   1: 2.441 ±(99.9%) 0.004 ms/op
Iteration   2: 2.433 ±(99.9%) 0.003 ms/op
Iteration   3: 2.439 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.438 ±(99.9%) 0.076 ms/op [Average]
  (min, avg, max) = (2.433, 2.438, 2.441), stdev = 0.004
  CI (99.9%): [2.362, 2.513] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.745 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.005 ms/op
Iteration   1: 3.033 ±(99.9%) 0.005 ms/op
Iteration   2: 3.040 ±(99.9%) 0.006 ms/op
Iteration   3: 3.026 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.033 ±(99.9%) 0.125 ms/op [Average]
  (min, avg, max) = (3.026, 3.033, 3.040), stdev = 0.007
  CI (99.9%): [2.908, 3.158] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.014 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.634 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
Iteration   1: 2.504 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.820 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.641 ms/op
                 createUser·p0.999:  11.769 ms/op
                 createUser·p0.9999: 13.111 ms/op
                 createUser·p1.00:   13.910 ms/op

Iteration   2: 2.495 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.863 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.740 ms/op
                 createUser·p0.999:  8.940 ms/op
                 createUser·p0.9999: 12.354 ms/op
                 createUser·p1.00:   12.501 ms/op

Iteration   3: 2.506 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.640 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   4.059 ms/op
                 createUser·p0.999:  8.857 ms/op
                 createUser·p0.9999: 10.732 ms/op
                 createUser·p1.00:   11.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383418
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 185322 
    [ 2.500,  3.750) = 193903 
    [ 3.750,  5.000) = 3133 
    [ 5.000,  6.250) = 534 
    [ 6.250,  7.500) = 79 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 124 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.801 ms/op
     p(99.9000) =      8.907 ms/op
     p(99.9900) =     12.894 ms/op
     p(99.9990) =     13.787 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


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
# Warmup Iteration   1: 3.725 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.006 ms/op
Iteration   1: 2.476 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.028 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.940 ms/op
                 existUser·p0.999:  6.274 ms/op
                 existUser·p0.9999: 16.531 ms/op
                 existUser·p1.00:   16.712 ms/op

Iteration   2: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.748 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.473 ms/op
                 existUser·p0.999:  8.552 ms/op
                 existUser·p0.9999: 14.434 ms/op
                 existUser·p1.00:   15.139 ms/op

Iteration   3: 2.446 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.861 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.711 ms/op
                 existUser·p0.999:  6.070 ms/op
                 existUser·p0.9999: 11.108 ms/op
                 existUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390202
  mean =      2.458 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 193913 
    [ 2.500,  3.750) = 192448 
    [ 3.750,  5.000) = 2980 
    [ 5.000,  6.250) = 382 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 71 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      7.831 ms/op
     p(99.9900) =     15.499 ms/op
     p(99.9990) =     16.666 ms/op
     p(99.9999) =     16.712 ms/op
    p(100.0000) =     16.712 ms/op


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
# Warmup Iteration   1: 3.860 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.528 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.006 ms/op
Iteration   1: 2.458 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.687 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.875 ms/op
                 getUser·p0.999:  6.930 ms/op
                 getUser·p0.9999: 14.287 ms/op
                 getUser·p1.00:   16.171 ms/op

Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.756 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   4.166 ms/op
                 getUser·p0.999:  8.404 ms/op
                 getUser·p0.9999: 11.684 ms/op
                 getUser·p1.00:   12.206 ms/op

Iteration   3: 2.453 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.029 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   2.978 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   3.863 ms/op
                 getUser·p0.999:  7.078 ms/op
                 getUser·p0.9999: 11.055 ms/op
                 getUser·p1.00:   11.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389211
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 99 
    [ 1.250,  2.500) = 195015 
    [ 2.500,  3.750) = 188841 
    [ 3.750,  5.000) = 3993 
    [ 5.000,  6.250) = 831 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 142 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.969 ms/op
     p(99.9000) =      7.839 ms/op
     p(99.9900) =     13.044 ms/op
     p(99.9990) =     15.287 ms/op
     p(99.9999) =     16.171 ms/op
    p(100.0000) =     16.171 ms/op


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
# Warmup Iteration   1: 4.677 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.009 ms/op
Iteration   1: 3.027 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.894 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  8.984 ms/op
                 listUser·p0.9999: 11.722 ms/op
                 listUser·p1.00:   13.353 ms/op

Iteration   2: 3.063 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.880 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  8.841 ms/op
                 listUser·p0.9999: 11.693 ms/op
                 listUser·p1.00:   11.911 ms/op

Iteration   3: 3.049 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.935 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.784 ms/op
                 listUser·p0.999:  9.863 ms/op
                 listUser·p0.9999: 11.641 ms/op
                 listUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314872
  mean =      3.046 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 143 
    [ 1.250,  2.500) = 86105 
    [ 2.500,  3.750) = 187037 
    [ 3.750,  5.000) = 33554 
    [ 5.000,  6.250) = 6503 
    [ 6.250,  7.500) = 841 
    [ 7.500,  8.750) = 269 
    [ 8.750, 10.000) = 182 
    [10.000, 11.250) = 170 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =      9.275 ms/op
     p(99.9900) =     11.665 ms/op
     p(99.9990) =     12.704 ms/op
     p(99.9999) =     13.353 ms/op
    p(100.0000) =     13.353 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.379 ± 1.681  ops/ms
ClientPb.existUser                       thrpt       3  13.086 ± 0.760  ops/ms
ClientPb.getUser                         thrpt       3  12.787 ± 2.288  ops/ms
ClientPb.listUser                        thrpt       3  10.511 ± 1.322  ops/ms
ClientPb.createUser                       avgt       3   2.504 ± 0.399   ms/op
ClientPb.existUser                        avgt       3   2.415 ± 0.231   ms/op
ClientPb.getUser                          avgt       3   2.438 ± 0.076   ms/op
ClientPb.listUser                         avgt       3   3.033 ± 0.125   ms/op
ClientPb.createUser                     sample  383418   2.502 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.640           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.801           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.907           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.894           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.910           ms/op
ClientPb.existUser                      sample  390202   2.458 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.748           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.831           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.499           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.712           ms/op
ClientPb.getUser                        sample  389211   2.464 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.687           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.494           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.998           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.969           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.839           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.044           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.171           ms/op
ClientPb.listUser                       sample  314872   3.046 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.880           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.982           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.944           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.693           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.275           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.665           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.353           ms/op
```
