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
[INFO] benchmark-base ..................................... SUCCESS [  2.994 s]
[INFO] server-base ........................................ SUCCESS [  0.303 s]
[INFO] client-base ........................................ SUCCESS [  0.606 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.457 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  4.682 s
[INFO] Finished at: 2024-01-25T00:31:20Z
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
# Warmup Iteration   1: 4.774 ops/ms
# Warmup Iteration   2: 11.870 ops/ms
# Warmup Iteration   3: 12.135 ops/ms
Iteration   1: 12.522 ops/ms
Iteration   2: 12.495 ops/ms
Iteration   3: 12.546 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.521 ±(99.9%) 0.468 ops/ms [Average]
  (min, avg, max) = (12.495, 12.521, 12.546), stdev = 0.026
  CI (99.9%): [12.053, 12.990] (assumes normal distribution)


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
# Warmup Iteration   1: 7.822 ops/ms
# Warmup Iteration   2: 13.086 ops/ms
# Warmup Iteration   3: 13.079 ops/ms
Iteration   1: 13.157 ops/ms
Iteration   2: 13.145 ops/ms
Iteration   3: 12.985 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.096 ±(99.9%) 1.747 ops/ms [Average]
  (min, avg, max) = (12.985, 13.096, 13.157), stdev = 0.096
  CI (99.9%): [11.348, 14.843] (assumes normal distribution)


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
# Warmup Iteration   1: 8.178 ops/ms
# Warmup Iteration   2: 12.596 ops/ms
# Warmup Iteration   3: 12.769 ops/ms
Iteration   1: 13.013 ops/ms
Iteration   2: 12.958 ops/ms
Iteration   3: 12.900 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.957 ±(99.9%) 1.033 ops/ms [Average]
  (min, avg, max) = (12.900, 12.957, 13.013), stdev = 0.057
  CI (99.9%): [11.924, 13.990] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.405 ops/ms
# Warmup Iteration   2: 10.369 ops/ms
# Warmup Iteration   3: 10.557 ops/ms
Iteration   1: 10.601 ops/ms
Iteration   2: 10.609 ops/ms
Iteration   3: 10.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.580 ±(99.9%) 0.788 ops/ms [Average]
  (min, avg, max) = (10.530, 10.580, 10.609), stdev = 0.043
  CI (99.9%): [9.792, 11.368] (assumes normal distribution)


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
# Warmup Iteration   1: 4.130 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.518 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.004 ms/op
Iteration   1: 2.525 ±(99.9%) 0.004 ms/op
Iteration   2: 2.546 ±(99.9%) 0.003 ms/op
Iteration   3: 2.502 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.524 ±(99.9%) 0.407 ms/op [Average]
  (min, avg, max) = (2.502, 2.524, 2.546), stdev = 0.022
  CI (99.9%): [2.117, 2.931] (assumes normal distribution)


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
# Warmup Iteration   1: 3.734 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.472 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.004 ms/op
Iteration   1: 2.467 ±(99.9%) 0.004 ms/op
Iteration   2: 2.441 ±(99.9%) 0.004 ms/op
Iteration   3: 2.457 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.455 ±(99.9%) 0.239 ms/op [Average]
  (min, avg, max) = (2.441, 2.455, 2.467), stdev = 0.013
  CI (99.9%): [2.216, 2.694] (assumes normal distribution)


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
# Warmup Iteration   1: 3.798 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.555 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.003 ms/op
Iteration   1: 2.482 ±(99.9%) 0.003 ms/op
Iteration   2: 2.477 ±(99.9%) 0.004 ms/op
Iteration   3: 2.495 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.485 ±(99.9%) 0.167 ms/op [Average]
  (min, avg, max) = (2.477, 2.485, 2.495), stdev = 0.009
  CI (99.9%): [2.317, 2.652] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.836 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.190 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.006 ms/op
Iteration   1: 3.047 ±(99.9%) 0.005 ms/op
Iteration   2: 3.023 ±(99.9%) 0.006 ms/op
Iteration   3: 3.031 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.034 ±(99.9%) 0.222 ms/op [Average]
  (min, avg, max) = (3.023, 3.034, 3.047), stdev = 0.012
  CI (99.9%): [2.811, 3.256] (assumes normal distribution)


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
# Warmup Iteration   1: 4.133 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.652 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
Iteration   1: 2.524 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.944 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.854 ms/op
                 createUser·p0.999:  11.698 ms/op
                 createUser·p0.9999: 20.316 ms/op
                 createUser·p1.00:   20.775 ms/op

Iteration   2: 2.548 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.914 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.731 ms/op
                 createUser·p0.999:  6.330 ms/op
                 createUser·p0.9999: 12.458 ms/op
                 createUser·p1.00:   12.878 ms/op

Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.534 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.756 ms/op
                 createUser·p0.999:  8.033 ms/op
                 createUser·p0.9999: 10.256 ms/op
                 createUser·p1.00:   14.352 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378564
  mean =      2.533 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 181447 
    [ 2.500,  5.000) = 196198 
    [ 5.000,  7.500) = 526 
    [ 7.500, 10.000) = 118 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.777 ms/op
     p(99.9000) =      8.094 ms/op
     p(99.9900) =     13.484 ms/op
     p(99.9990) =     20.716 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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
# Warmup Iteration   1: 3.802 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.492 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.006 ms/op
Iteration   1: 2.481 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.993 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.564 ms/op
                 existUser·p0.999:  6.953 ms/op
                 existUser·p0.9999: 16.517 ms/op
                 existUser·p1.00:   17.269 ms/op

Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.632 ms/op
                 existUser·p0.50:   2.597 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.719 ms/op
                 existUser·p0.999:  8.769 ms/op
                 existUser·p0.9999: 13.126 ms/op
                 existUser·p1.00:   14.205 ms/op

Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.925 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.854 ms/op
                 existUser·p0.999:  8.082 ms/op
                 existUser·p0.9999: 12.211 ms/op
                 existUser·p1.00:   12.943 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386157
  mean =      2.483 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 187757 
    [ 2.500,  3.750) = 194735 
    [ 3.750,  5.000) = 2846 
    [ 5.000,  6.250) = 269 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.711 ms/op
     p(99.9000) =      8.174 ms/op
     p(99.9900) =     15.679 ms/op
     p(99.9990) =     17.109 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


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
# Warmup Iteration   1: 3.885 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.006 ms/op
Iteration   1: 2.461 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.005 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.621 ms/op
                 getUser·p0.999:  8.087 ms/op
                 getUser·p0.9999: 14.156 ms/op
                 getUser·p1.00:   14.500 ms/op

Iteration   2: 2.500 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   4.743 ms/op
                 getUser·p0.999:  9.145 ms/op
                 getUser·p0.9999: 12.502 ms/op
                 getUser·p1.00:   13.877 ms/op

Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.736 ms/op
                 getUser·p0.999:  6.156 ms/op
                 getUser·p0.9999: 11.190 ms/op
                 getUser·p1.00:   11.829 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386946
  mean =      2.479 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 192926 
    [ 2.500,  3.750) = 189471 
    [ 3.750,  5.000) = 3225 
    [ 5.000,  6.250) = 765 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.846 ms/op
     p(99.9000) =      8.102 ms/op
     p(99.9900) =     13.134 ms/op
     p(99.9990) =     14.379 ms/op
     p(99.9999) =     14.500 ms/op
    p(100.0000) =     14.500 ms/op


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
# Warmup Iteration   1: 4.582 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.009 ms/op
Iteration   1: 2.999 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.871 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.690 ms/op
                 listUser·p0.9999: 10.859 ms/op
                 listUser·p1.00:   12.419 ms/op

Iteration   2: 3.002 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.831 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.423 ms/op
                 listUser·p0.999:  9.552 ms/op
                 listUser·p0.9999: 11.529 ms/op
                 listUser·p1.00:   12.632 ms/op

Iteration   3: 3.023 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.844 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.601 ms/op
                 listUser·p0.9999: 11.391 ms/op
                 listUser·p1.00:   11.895 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318975
  mean =      3.008 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 151 
    [ 1.250,  2.500) = 89367 
    [ 2.500,  3.750) = 191898 
    [ 3.750,  5.000) = 30841 
    [ 5.000,  6.250) = 5520 
    [ 6.250,  7.500) = 536 
    [ 7.500,  8.750) = 174 
    [ 8.750, 10.000) = 264 
    [10.000, 11.250) = 176 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =      9.617 ms/op
     p(99.9900) =     11.372 ms/op
     p(99.9990) =     12.410 ms/op
     p(99.9999) =     12.632 ms/op
    p(100.0000) =     12.632 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.521 ± 0.468  ops/ms
ClientPb.existUser                       thrpt       3  13.096 ± 1.747  ops/ms
ClientPb.getUser                         thrpt       3  12.957 ± 1.033  ops/ms
ClientPb.listUser                        thrpt       3  10.580 ± 0.788  ops/ms
ClientPb.createUser                       avgt       3   2.524 ± 0.407   ms/op
ClientPb.existUser                        avgt       3   2.455 ± 0.239   ms/op
ClientPb.getUser                          avgt       3   2.485 ± 0.167   ms/op
ClientPb.listUser                         avgt       3   3.034 ± 0.222   ms/op
ClientPb.createUser                     sample  378564   2.533 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.534           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.094           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.484           ms/op
ClientPb.createUser:createUser·p1.00    sample          20.775           ms/op
ClientPb.existUser                      sample  386157   2.483 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.632           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.556           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.138           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.711           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.174           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.679           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.269           ms/op
ClientPb.getUser                        sample  386946   2.479 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.741           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.011           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.102           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.134           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.500           ms/op
ClientPb.listUser                       sample  318975   3.008 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.831           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.617           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.372           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.632           ms/op
```
