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
[INFO] server-base ........................................ SUCCESS [  0.304 s]
[INFO] client-base ........................................ SUCCESS [  0.632 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.526 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  4.558 s
[INFO] Finished at: 2024-01-02T00:29:40Z
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
# Warmup Iteration   1: 4.577 ops/ms
# Warmup Iteration   2: 12.217 ops/ms
# Warmup Iteration   3: 12.449 ops/ms
Iteration   1: 12.642 ops/ms
Iteration   2: 12.734 ops/ms
Iteration   3: 12.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.701 ±(99.9%) 0.929 ops/ms [Average]
  (min, avg, max) = (12.642, 12.701, 12.734), stdev = 0.051
  CI (99.9%): [11.771, 13.630] (assumes normal distribution)


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
# Warmup Iteration   1: 8.194 ops/ms
# Warmup Iteration   2: 12.904 ops/ms
# Warmup Iteration   3: 13.029 ops/ms
Iteration   1: 13.049 ops/ms
Iteration   2: 13.259 ops/ms
Iteration   3: 13.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.166 ±(99.9%) 1.952 ops/ms [Average]
  (min, avg, max) = (13.049, 13.166, 13.259), stdev = 0.107
  CI (99.9%): [11.214, 15.118] (assumes normal distribution)


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
# Warmup Iteration   1: 8.008 ops/ms
# Warmup Iteration   2: 12.589 ops/ms
# Warmup Iteration   3: 12.845 ops/ms
Iteration   1: 12.919 ops/ms
Iteration   2: 12.914 ops/ms
Iteration   3: 12.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.910 ±(99.9%) 0.206 ops/ms [Average]
  (min, avg, max) = (12.897, 12.910, 12.919), stdev = 0.011
  CI (99.9%): [12.704, 13.116] (assumes normal distribution)


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
# Warmup Iteration   1: 6.934 ops/ms
# Warmup Iteration   2: 10.463 ops/ms
# Warmup Iteration   3: 10.636 ops/ms
Iteration   1: 10.631 ops/ms
Iteration   2: 10.591 ops/ms
Iteration   3: 10.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.635 ±(99.9%) 0.844 ops/ms [Average]
  (min, avg, max) = (10.591, 10.635, 10.683), stdev = 0.046
  CI (99.9%): [9.791, 11.480] (assumes normal distribution)


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
# Warmup Iteration   1: 3.926 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.554 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.004 ms/op
Iteration   1: 2.523 ±(99.9%) 0.005 ms/op
Iteration   2: 2.545 ±(99.9%) 0.004 ms/op
Iteration   3: 2.504 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.524 ±(99.9%) 0.372 ms/op [Average]
  (min, avg, max) = (2.504, 2.524, 2.545), stdev = 0.020
  CI (99.9%): [2.152, 2.896] (assumes normal distribution)


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
# Warmup Iteration   1: 3.631 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.456 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.391 ±(99.9%) 0.003 ms/op
Iteration   1: 2.409 ±(99.9%) 0.004 ms/op
Iteration   2: 2.373 ±(99.9%) 0.004 ms/op
Iteration   3: 2.430 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.404 ±(99.9%) 0.529 ms/op [Average]
  (min, avg, max) = (2.373, 2.404, 2.430), stdev = 0.029
  CI (99.9%): [1.876, 2.933] (assumes normal distribution)


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
# Warmup Iteration   1: 3.975 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.510 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.004 ms/op
Iteration   1: 2.452 ±(99.9%) 0.003 ms/op
Iteration   2: 2.455 ±(99.9%) 0.004 ms/op
Iteration   3: 2.460 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.456 ±(99.9%) 0.071 ms/op [Average]
  (min, avg, max) = (2.452, 2.456, 2.460), stdev = 0.004
  CI (99.9%): [2.384, 2.527] (assumes normal distribution)


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
# Warmup Iteration   1: 4.590 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.012 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.006 ms/op
Iteration   1: 2.981 ±(99.9%) 0.006 ms/op
Iteration   2: 2.993 ±(99.9%) 0.005 ms/op
Iteration   3: 2.976 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.983 ±(99.9%) 0.163 ms/op [Average]
  (min, avg, max) = (2.976, 2.983, 2.993), stdev = 0.009
  CI (99.9%): [2.820, 3.147] (assumes normal distribution)


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
# Warmup Iteration   1: 4.398 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.690 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.607 ±(99.9%) 0.006 ms/op
Iteration   1: 2.617 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.844 ms/op
                 createUser·p0.50:   2.666 ms/op
                 createUser·p0.90:   3.183 ms/op
                 createUser·p0.95:   3.305 ms/op
                 createUser·p0.99:   3.981 ms/op
                 createUser·p0.999:  11.946 ms/op
                 createUser·p0.9999: 14.393 ms/op
                 createUser·p1.00:   14.909 ms/op

Iteration   2: 2.631 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.845 ms/op
                 createUser·p0.50:   2.679 ms/op
                 createUser·p0.90:   3.191 ms/op
                 createUser·p0.95:   3.330 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  10.092 ms/op
                 createUser·p0.9999: 13.025 ms/op
                 createUser·p1.00:   13.631 ms/op

Iteration   3: 2.635 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.916 ms/op
                 createUser·p0.50:   2.679 ms/op
                 createUser·p0.90:   3.215 ms/op
                 createUser·p0.95:   3.367 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  9.585 ms/op
                 createUser·p0.9999: 11.321 ms/op
                 createUser·p1.00:   11.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 365111
  mean =      2.628 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 171838 
    [ 2.500,  3.750) = 186563 
    [ 3.750,  5.000) = 5124 
    [ 5.000,  6.250) = 921 
    [ 6.250,  7.500) = 181 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      2.675 ms/op
     p(90.0000) =      3.195 ms/op
     p(95.0000) =      3.334 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      9.763 ms/op
     p(99.9900) =     13.746 ms/op
     p(99.9990) =     14.620 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


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
# Warmup Iteration   1: 3.721 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.416 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.413 ±(99.9%) 0.005 ms/op
Iteration   1: 2.415 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.966 ms/op
                 existUser·p0.50:   2.441 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.551 ms/op
                 existUser·p0.999:  7.945 ms/op
                 existUser·p0.9999: 17.818 ms/op
                 existUser·p1.00:   18.711 ms/op

Iteration   2: 2.407 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.021 ms/op
                 existUser·p0.50:   2.421 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.482 ms/op
                 existUser·p0.999:  5.597 ms/op
                 existUser·p0.9999: 13.156 ms/op
                 existUser·p1.00:   14.156 ms/op

Iteration   3: 2.416 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.982 ms/op
                 existUser·p0.50:   2.437 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  5.911 ms/op
                 existUser·p0.9999: 11.481 ms/op
                 existUser·p1.00:   15.073 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 397450
  mean =      2.412 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 206218 
    [ 2.500,  3.750) = 188313 
    [ 3.750,  5.000) = 2198 
    [ 5.000,  6.250) = 256 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.966 ms/op
     p(50.0000) =      2.433 ms/op
     p(90.0000) =      2.941 ms/op
     p(95.0000) =      3.052 ms/op
     p(99.0000) =      3.555 ms/op
     p(99.9000) =      6.335 ms/op
     p(99.9900) =     14.652 ms/op
     p(99.9990) =     18.023 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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
# Warmup Iteration   1: 3.936 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.006 ms/op
Iteration   1: 2.468 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.987 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.739 ms/op
                 getUser·p0.999:  8.846 ms/op
                 getUser·p0.9999: 13.059 ms/op
                 getUser·p1.00:   14.008 ms/op

Iteration   2: 2.507 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   3.739 ms/op
                 getUser·p0.999:  8.895 ms/op
                 getUser·p0.9999: 13.230 ms/op
                 getUser·p1.00:   13.992 ms/op

Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.911 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.666 ms/op
                 getUser·p0.999:  6.526 ms/op
                 getUser·p0.9999: 10.816 ms/op
                 getUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386176
  mean =      2.484 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 192600 
    [ 2.500,  3.750) = 189891 
    [ 3.750,  5.000) = 2878 
    [ 5.000,  6.250) = 280 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.715 ms/op
     p(99.9000) =      8.622 ms/op
     p(99.9900) =     13.058 ms/op
     p(99.9990) =     13.961 ms/op
     p(99.9999) =     14.008 ms/op
    p(100.0000) =     14.008 ms/op


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
# Warmup Iteration   1: 4.454 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.008 ms/op
Iteration   1: 3.021 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.890 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.857 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.850 ms/op
                 listUser·p0.9999: 12.839 ms/op
                 listUser·p1.00:   15.008 ms/op

Iteration   2: 3.024 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.971 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.475 ms/op
                 listUser·p0.9999: 14.458 ms/op
                 listUser·p1.00:   15.499 ms/op

Iteration   3: 2.989 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.824 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  9.290 ms/op
                 listUser·p0.9999: 11.403 ms/op
                 listUser·p1.00:   11.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318440
  mean =      3.011 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 117 
    [ 1.250,  2.500) = 90758 
    [ 2.500,  3.750) = 188985 
    [ 3.750,  5.000) = 31688 
    [ 5.000,  6.250) = 5604 
    [ 6.250,  7.500) = 591 
    [ 7.500,  8.750) = 210 
    [ 8.750, 10.000) = 268 
    [10.000, 11.250) = 123 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     13.407 ms/op
     p(99.9990) =     14.971 ms/op
     p(99.9999) =     15.499 ms/op
    p(100.0000) =     15.499 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.701 ± 0.929  ops/ms
ClientPb.existUser                       thrpt       3  13.166 ± 1.952  ops/ms
ClientPb.getUser                         thrpt       3  12.910 ± 0.206  ops/ms
ClientPb.listUser                        thrpt       3  10.635 ± 0.844  ops/ms
ClientPb.createUser                       avgt       3   2.524 ± 0.372   ms/op
ClientPb.existUser                        avgt       3   2.404 ± 0.529   ms/op
ClientPb.getUser                          avgt       3   2.456 ± 0.071   ms/op
ClientPb.listUser                         avgt       3   2.983 ± 0.163   ms/op
ClientPb.createUser                     sample  365111   2.628 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.844           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.675           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.334           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.202           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.763           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.746           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.909           ms/op
ClientPb.existUser                      sample  397450   2.412 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.966           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.433           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.941           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.555           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.335           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.652           ms/op
ClientPb.existUser:existUser·p1.00      sample          18.711           ms/op
ClientPb.getUser                        sample  386176   2.484 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.868           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.715           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.622           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.058           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.008           ms/op
ClientPb.listUser                       sample  318440   3.011 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.824           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.538           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.634           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.407           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.499           ms/op
```
