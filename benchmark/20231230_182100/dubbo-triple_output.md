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
[INFO] benchmark-base ..................................... SUCCESS [  2.807 s]
[INFO] server-base ........................................ SUCCESS [  0.347 s]
[INFO] client-base ........................................ SUCCESS [  0.578 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.349 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  4.377 s
[INFO] Finished at: 2023-12-30T18:07:30Z
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
# Warmup Iteration   1: 4.466 ops/ms
# Warmup Iteration   2: 11.753 ops/ms
# Warmup Iteration   3: 11.984 ops/ms
Iteration   1: 12.255 ops/ms
Iteration   2: 12.243 ops/ms
Iteration   3: 12.502 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.333 ±(99.9%) 2.663 ops/ms [Average]
  (min, avg, max) = (12.243, 12.333, 12.502), stdev = 0.146
  CI (99.9%): [9.670, 14.996] (assumes normal distribution)


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
# Warmup Iteration   1: 7.438 ops/ms
# Warmup Iteration   2: 12.690 ops/ms
# Warmup Iteration   3: 12.756 ops/ms
Iteration   1: 12.754 ops/ms
Iteration   2: 13.006 ops/ms
Iteration   3: 12.885 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.882 ±(99.9%) 2.306 ops/ms [Average]
  (min, avg, max) = (12.754, 12.882, 13.006), stdev = 0.126
  CI (99.9%): [10.575, 15.188] (assumes normal distribution)


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
# Warmup Iteration   1: 7.343 ops/ms
# Warmup Iteration   2: 12.567 ops/ms
# Warmup Iteration   3: 12.642 ops/ms
Iteration   1: 12.777 ops/ms
Iteration   2: 12.741 ops/ms
Iteration   3: 12.429 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.649 ±(99.9%) 3.495 ops/ms [Average]
  (min, avg, max) = (12.429, 12.649, 12.777), stdev = 0.192
  CI (99.9%): [9.154, 16.145] (assumes normal distribution)


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
# Warmup Iteration   1: 6.496 ops/ms
# Warmup Iteration   2: 10.327 ops/ms
# Warmup Iteration   3: 10.426 ops/ms
Iteration   1: 10.427 ops/ms
Iteration   2: 10.423 ops/ms
Iteration   3: 10.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.439 ±(99.9%) 0.437 ops/ms [Average]
  (min, avg, max) = (10.423, 10.439, 10.466), stdev = 0.024
  CI (99.9%): [10.002, 10.876] (assumes normal distribution)


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
# Warmup Iteration   1: 3.938 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.565 ±(99.9%) 0.004 ms/op
Iteration   1: 2.612 ±(99.9%) 0.004 ms/op
Iteration   2: 2.582 ±(99.9%) 0.004 ms/op
Iteration   3: 2.516 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.570 ±(99.9%) 0.898 ms/op [Average]
  (min, avg, max) = (2.516, 2.570, 2.612), stdev = 0.049
  CI (99.9%): [1.672, 3.467] (assumes normal distribution)


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
# Warmup Iteration   1: 3.785 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.520 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.004 ms/op
Iteration   1: 2.489 ±(99.9%) 0.004 ms/op
Iteration   2: 2.479 ±(99.9%) 0.005 ms/op
Iteration   3: 2.486 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.485 ±(99.9%) 0.094 ms/op [Average]
  (min, avg, max) = (2.479, 2.485, 2.489), stdev = 0.005
  CI (99.9%): [2.390, 2.579] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.912 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.563 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.004 ms/op
Iteration   1: 2.491 ±(99.9%) 0.004 ms/op
Iteration   2: 2.489 ±(99.9%) 0.004 ms/op
Iteration   3: 2.481 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.487 ±(99.9%) 0.094 ms/op [Average]
  (min, avg, max) = (2.481, 2.487, 2.491), stdev = 0.005
  CI (99.9%): [2.394, 2.581] (assumes normal distribution)


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
# Warmup Iteration   1: 4.729 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.006 ms/op
Iteration   1: 3.058 ±(99.9%) 0.005 ms/op
Iteration   2: 3.053 ±(99.9%) 0.005 ms/op
Iteration   3: 3.065 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.058 ±(99.9%) 0.114 ms/op [Average]
  (min, avg, max) = (3.053, 3.058, 3.065), stdev = 0.006
  CI (99.9%): [2.945, 3.172] (assumes normal distribution)


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
# Warmup Iteration   1: 4.378 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.759 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.622 ±(99.9%) 0.006 ms/op
Iteration   1: 2.599 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.900 ms/op
                 createUser·p0.50:   2.671 ms/op
                 createUser·p0.90:   3.154 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  11.649 ms/op
                 createUser·p0.9999: 14.197 ms/op
                 createUser·p1.00:   14.615 ms/op

Iteration   2: 2.588 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.940 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.150 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   3.670 ms/op
                 createUser·p0.999:  9.929 ms/op
                 createUser·p0.9999: 13.145 ms/op
                 createUser·p1.00:   13.484 ms/op

Iteration   3: 2.613 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.907 ms/op
                 createUser·p0.50:   2.666 ms/op
                 createUser·p0.90:   3.170 ms/op
                 createUser·p0.95:   3.293 ms/op
                 createUser·p0.99:   4.035 ms/op
                 createUser·p0.999:  8.618 ms/op
                 createUser·p0.9999: 14.349 ms/op
                 createUser·p1.00:   14.877 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 368869
  mean =      2.600 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 31 
    [ 1.250,  2.500) = 175231 
    [ 2.500,  3.750) = 189534 
    [ 3.750,  5.000) = 3194 
    [ 5.000,  6.250) = 348 
    [ 6.250,  7.500) = 110 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 105 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      2.662 ms/op
     p(90.0000) =      3.158 ms/op
     p(95.0000) =      3.265 ms/op
     p(99.0000) =      3.797 ms/op
     p(99.9000) =      8.733 ms/op
     p(99.9900) =     14.059 ms/op
     p(99.9990) =     14.761 ms/op
     p(99.9999) =     14.877 ms/op
    p(100.0000) =     14.877 ms/op


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
# Warmup Iteration   1: 3.817 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
Iteration   1: 2.504 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  10.626 ms/op
                 existUser·p0.9999: 17.139 ms/op
                 existUser·p1.00:   17.596 ms/op

Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.043 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  8.467 ms/op
                 existUser·p0.9999: 12.471 ms/op
                 existUser·p1.00:   13.484 ms/op

Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.777 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  8.259 ms/op
                 existUser·p0.9999: 11.682 ms/op
                 existUser·p1.00:   11.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384537
  mean =      2.494 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 188656 
    [ 2.500,  3.750) = 192152 
    [ 3.750,  5.000) = 2713 
    [ 5.000,  6.250) = 480 
    [ 6.250,  7.500) = 70 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.723 ms/op
     p(99.9000) =      8.286 ms/op
     p(99.9900) =     14.199 ms/op
     p(99.9990) =     17.569 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


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
# Warmup Iteration   1: 3.959 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.647 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.579 ±(99.9%) 0.007 ms/op
Iteration   1: 2.563 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.925 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.265 ms/op
                 getUser·p0.99:   3.797 ms/op
                 getUser·p0.999:  11.887 ms/op
                 getUser·p0.9999: 14.689 ms/op
                 getUser·p1.00:   15.057 ms/op

Iteration   2: 2.564 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.786 ms/op
                 getUser·p0.50:   2.609 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.310 ms/op
                 getUser·p0.99:   4.661 ms/op
                 getUser·p0.999:  9.617 ms/op
                 getUser·p0.9999: 13.615 ms/op
                 getUser·p1.00:   14.320 ms/op

Iteration   3: 2.551 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.012 ms/op
                 getUser·p0.50:   2.597 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  6.772 ms/op
                 getUser·p0.9999: 13.091 ms/op
                 getUser·p1.00:   13.287 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 374749
  mean =      2.559 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 179016 
    [ 2.500,  3.750) = 189161 
    [ 3.750,  5.000) = 4709 
    [ 5.000,  6.250) = 1302 
    [ 6.250,  7.500) = 144 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.269 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      7.234 ms/op
     p(99.9900) =     13.910 ms/op
     p(99.9990) =     14.914 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.918 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.009 ms/op
Iteration   1: 3.035 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.775 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.208 ms/op
                 listUser·p0.9999: 10.525 ms/op
                 listUser·p1.00:   10.928 ms/op

Iteration   2: 3.070 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.911 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  9.372 ms/op
                 listUser·p0.9999: 12.370 ms/op
                 listUser·p1.00:   13.828 ms/op

Iteration   3: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.030 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.198 ms/op
                 listUser·p0.9999: 10.535 ms/op
                 listUser·p1.00:   10.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315100
  mean =      3.044 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 108 
    [ 1.250,  2.500) = 86408 
    [ 2.500,  3.750) = 186689 
    [ 3.750,  5.000) = 34365 
    [ 5.000,  6.250) = 6027 
    [ 6.250,  7.500) = 835 
    [ 7.500,  8.750) = 233 
    [ 8.750, 10.000) = 294 
    [10.000, 11.250) = 109 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      9.224 ms/op
     p(99.9900) =     11.256 ms/op
     p(99.9990) =     13.612 ms/op
     p(99.9999) =     13.828 ms/op
    p(100.0000) =     13.828 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.333 ± 2.663  ops/ms
ClientPb.existUser                       thrpt       3  12.882 ± 2.306  ops/ms
ClientPb.getUser                         thrpt       3  12.649 ± 3.495  ops/ms
ClientPb.listUser                        thrpt       3  10.439 ± 0.437  ops/ms
ClientPb.createUser                       avgt       3   2.570 ± 0.898   ms/op
ClientPb.existUser                        avgt       3   2.485 ± 0.094   ms/op
ClientPb.getUser                          avgt       3   2.487 ± 0.094   ms/op
ClientPb.listUser                         avgt       3   3.058 ± 0.114   ms/op
ClientPb.createUser                     sample  368869   2.600 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.900           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.662           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.265           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.733           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.059           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.877           ms/op
ClientPb.existUser                      sample  384537   2.494 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.777           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.286           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.199           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.596           ms/op
ClientPb.getUser                        sample  374749   2.559 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.786           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.597           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.269           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.234           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.910           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.057           ms/op
ClientPb.listUser                       sample  315100   3.044 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.775           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.986           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.224           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.256           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.828           ms/op
```
