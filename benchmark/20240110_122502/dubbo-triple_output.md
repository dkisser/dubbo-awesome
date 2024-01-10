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
[INFO] benchmark-base ..................................... SUCCESS [  2.908 s]
[INFO] server-base ........................................ SUCCESS [  0.297 s]
[INFO] client-base ........................................ SUCCESS [  0.594 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.506 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  4.623 s
[INFO] Finished at: 2024-01-10T12:11:27Z
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
# Warmup Iteration   1: 4.982 ops/ms
# Warmup Iteration   2: 12.077 ops/ms
# Warmup Iteration   3: 12.045 ops/ms
Iteration   1: 12.507 ops/ms
Iteration   2: 12.417 ops/ms
Iteration   3: 12.329 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.418 ±(99.9%) 1.626 ops/ms [Average]
  (min, avg, max) = (12.329, 12.418, 12.507), stdev = 0.089
  CI (99.9%): [10.791, 14.044] (assumes normal distribution)


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
# Warmup Iteration   1: 8.452 ops/ms
# Warmup Iteration   2: 12.967 ops/ms
# Warmup Iteration   3: 13.083 ops/ms
Iteration   1: 13.129 ops/ms
Iteration   2: 13.221 ops/ms
Iteration   3: 13.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.224 ±(99.9%) 1.753 ops/ms [Average]
  (min, avg, max) = (13.129, 13.224, 13.321), stdev = 0.096
  CI (99.9%): [11.471, 14.977] (assumes normal distribution)


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
# Warmup Iteration   1: 7.732 ops/ms
# Warmup Iteration   2: 12.312 ops/ms
# Warmup Iteration   3: 12.956 ops/ms
Iteration   1: 12.934 ops/ms
Iteration   2: 12.916 ops/ms
Iteration   3: 12.896 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.915 ±(99.9%) 0.351 ops/ms [Average]
  (min, avg, max) = (12.896, 12.915, 12.934), stdev = 0.019
  CI (99.9%): [12.564, 13.267] (assumes normal distribution)


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
# Warmup Iteration   1: 6.947 ops/ms
# Warmup Iteration   2: 10.440 ops/ms
# Warmup Iteration   3: 10.613 ops/ms
Iteration   1: 10.628 ops/ms
Iteration   2: 10.659 ops/ms
Iteration   3: 10.646 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.644 ±(99.9%) 0.283 ops/ms [Average]
  (min, avg, max) = (10.628, 10.644, 10.659), stdev = 0.015
  CI (99.9%): [10.361, 10.927] (assumes normal distribution)


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
# Warmup Iteration   1: 4.060 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.612 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
Iteration   1: 2.528 ±(99.9%) 0.004 ms/op
Iteration   2: 2.533 ±(99.9%) 0.003 ms/op
Iteration   3: 2.497 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.519 ±(99.9%) 0.352 ms/op [Average]
  (min, avg, max) = (2.497, 2.519, 2.533), stdev = 0.019
  CI (99.9%): [2.168, 2.871] (assumes normal distribution)


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
# Warmup Iteration   1: 3.566 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.475 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.003 ms/op
Iteration   1: 2.475 ±(99.9%) 0.004 ms/op
Iteration   2: 2.469 ±(99.9%) 0.004 ms/op
Iteration   3: 2.485 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.476 ±(99.9%) 0.150 ms/op [Average]
  (min, avg, max) = (2.469, 2.476, 2.485), stdev = 0.008
  CI (99.9%): [2.327, 2.626] (assumes normal distribution)


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
# Warmup Iteration   1: 3.856 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.532 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.004 ms/op
Iteration   1: 2.496 ±(99.9%) 0.004 ms/op
Iteration   2: 2.522 ±(99.9%) 0.004 ms/op
Iteration   3: 2.484 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.501 ±(99.9%) 0.348 ms/op [Average]
  (min, avg, max) = (2.484, 2.501, 2.522), stdev = 0.019
  CI (99.9%): [2.153, 2.849] (assumes normal distribution)


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
# Warmup Iteration   1: 4.734 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.006 ms/op
Iteration   1: 3.033 ±(99.9%) 0.005 ms/op
Iteration   2: 3.057 ±(99.9%) 0.005 ms/op
Iteration   3: 3.031 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.040 ±(99.9%) 0.268 ms/op [Average]
  (min, avg, max) = (3.031, 3.040, 3.057), stdev = 0.015
  CI (99.9%): [2.773, 3.308] (assumes normal distribution)


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
# Warmup Iteration   1: 4.001 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.666 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.006 ms/op
Iteration   1: 2.542 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.910 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.777 ms/op
                 createUser·p0.999:  11.423 ms/op
                 createUser·p0.9999: 13.311 ms/op
                 createUser·p1.00:   14.107 ms/op

Iteration   2: 2.524 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.880 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  9.556 ms/op
                 createUser·p0.9999: 12.255 ms/op
                 createUser·p1.00:   12.501 ms/op

Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.854 ms/op
                 createUser·p0.999:  8.598 ms/op
                 createUser·p0.9999: 10.797 ms/op
                 createUser·p1.00:   15.958 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378971
  mean =      2.530 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 183041 
    [ 2.500,  3.750) = 191552 
    [ 3.750,  5.000) = 3345 
    [ 5.000,  6.250) = 555 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =      8.668 ms/op
     p(99.9900) =     12.804 ms/op
     p(99.9990) =     13.737 ms/op
     p(99.9999) =     15.958 ms/op
    p(100.0000) =     15.958 ms/op


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
# Warmup Iteration   1: 3.705 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.426 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.409 ±(99.9%) 0.005 ms/op
Iteration   1: 2.414 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.555 ms/op
                 existUser·p0.50:   2.449 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.744 ms/op
                 existUser·p0.999:  6.678 ms/op
                 existUser·p0.9999: 13.500 ms/op
                 existUser·p1.00:   14.074 ms/op

Iteration   2: 2.408 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.790 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.531 ms/op
                 existUser·p0.999:  7.577 ms/op
                 existUser·p0.9999: 13.765 ms/op
                 existUser·p1.00:   14.811 ms/op

Iteration   3: 2.407 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.903 ms/op
                 existUser·p0.50:   2.433 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  7.714 ms/op
                 existUser·p0.9999: 11.787 ms/op
                 existUser·p1.00:   12.861 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 398014
  mean =      2.410 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 81 
    [ 1.250,  2.500) = 204709 
    [ 2.500,  3.750) = 189891 
    [ 3.750,  5.000) = 2517 
    [ 5.000,  6.250) = 353 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      2.458 ms/op
     p(90.0000) =      2.937 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      3.645 ms/op
     p(99.9000) =      7.404 ms/op
     p(99.9900) =     13.484 ms/op
     p(99.9990) =     14.599 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


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
# Warmup Iteration   1: 4.104 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.584 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.006 ms/op
Iteration   1: 2.484 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.726 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.944 ms/op
                 getUser·p0.999:  8.114 ms/op
                 getUser·p0.9999: 13.404 ms/op
                 getUser·p1.00:   14.778 ms/op

Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.873 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.813 ms/op
                 getUser·p0.999:  8.392 ms/op
                 getUser·p0.9999: 12.452 ms/op
                 getUser·p1.00:   16.007 ms/op

Iteration   3: 2.506 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.873 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   4.131 ms/op
                 getUser·p0.999:  7.968 ms/op
                 getUser·p0.9999: 10.211 ms/op
                 getUser·p1.00:   10.928 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385259
  mean =      2.490 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 86 
    [ 1.250,  2.500) = 191317 
    [ 2.500,  3.750) = 188687 
    [ 3.750,  5.000) = 4124 
    [ 5.000,  6.250) = 605 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.940 ms/op
     p(99.9000) =      8.011 ms/op
     p(99.9900) =     13.066 ms/op
     p(99.9990) =     14.062 ms/op
     p(99.9999) =     16.007 ms/op
    p(100.0000) =     16.007 ms/op


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
# Warmup Iteration   1: 4.715 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.009 ms/op
Iteration   1: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.881 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.297 ms/op
                 listUser·p0.9999: 10.541 ms/op
                 listUser·p1.00:   11.223 ms/op

Iteration   2: 3.010 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.904 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.418 ms/op
                 listUser·p0.9999: 13.048 ms/op
                 listUser·p1.00:   13.976 ms/op

Iteration   3: 3.016 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.993 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.388 ms/op
                 listUser·p0.9999: 11.731 ms/op
                 listUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318467
  mean =      3.011 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 112 
    [ 1.250,  2.500) = 92934 
    [ 2.500,  3.750) = 186129 
    [ 3.750,  5.000) = 31675 
    [ 5.000,  6.250) = 6157 
    [ 6.250,  7.500) = 740 
    [ 7.500,  8.750) = 215 
    [ 8.750, 10.000) = 322 
    [10.000, 11.250) = 127 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =     11.914 ms/op
     p(99.9990) =     13.661 ms/op
     p(99.9999) =     13.976 ms/op
    p(100.0000) =     13.976 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.418 ± 1.626  ops/ms
ClientPb.existUser                       thrpt       3  13.224 ± 1.753  ops/ms
ClientPb.getUser                         thrpt       3  12.915 ± 0.351  ops/ms
ClientPb.listUser                        thrpt       3  10.644 ± 0.283  ops/ms
ClientPb.createUser                       avgt       3   2.519 ± 0.352   ms/op
ClientPb.existUser                        avgt       3   2.476 ± 0.150   ms/op
ClientPb.getUser                          avgt       3   2.501 ± 0.348   ms/op
ClientPb.listUser                         avgt       3   3.040 ± 0.268   ms/op
ClientPb.createUser                     sample  378971   2.530 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.880           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.668           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.804           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.958           ms/op
ClientPb.existUser                      sample  398014   2.410 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.555           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.458           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.937           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.645           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.404           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.484           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.811           ms/op
ClientPb.getUser                        sample  385259   2.490 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.726           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.011           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.066           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.007           ms/op
ClientPb.listUser                       sample  318467   3.011 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.881           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.355           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.914           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.976           ms/op
```
