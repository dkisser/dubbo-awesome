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
[INFO] benchmark-base ..................................... SUCCESS [  2.860 s]
[INFO] server-base ........................................ SUCCESS [  0.342 s]
[INFO] client-base ........................................ SUCCESS [  0.653 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.425 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  4.587 s
[INFO] Finished at: 2024-01-02T18:08:34Z
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
# Warmup Iteration   1: 4.532 ops/ms
# Warmup Iteration   2: 11.915 ops/ms
# Warmup Iteration   3: 12.338 ops/ms
Iteration   1: 12.293 ops/ms
Iteration   2: 12.398 ops/ms
Iteration   3: 12.551 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.414 ±(99.9%) 2.365 ops/ms [Average]
  (min, avg, max) = (12.293, 12.414, 12.551), stdev = 0.130
  CI (99.9%): [10.049, 14.779] (assumes normal distribution)


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
# Warmup Iteration   1: 7.459 ops/ms
# Warmup Iteration   2: 12.883 ops/ms
# Warmup Iteration   3: 12.879 ops/ms
Iteration   1: 12.900 ops/ms
Iteration   2: 12.962 ops/ms
Iteration   3: 12.940 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.934 ±(99.9%) 0.567 ops/ms [Average]
  (min, avg, max) = (12.900, 12.934, 12.962), stdev = 0.031
  CI (99.9%): [12.367, 13.501] (assumes normal distribution)


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
# Warmup Iteration   1: 7.727 ops/ms
# Warmup Iteration   2: 12.199 ops/ms
# Warmup Iteration   3: 12.484 ops/ms
Iteration   1: 12.768 ops/ms
Iteration   2: 12.453 ops/ms
Iteration   3: 12.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.637 ±(99.9%) 2.987 ops/ms [Average]
  (min, avg, max) = (12.453, 12.637, 12.768), stdev = 0.164
  CI (99.9%): [9.650, 15.623] (assumes normal distribution)


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
# Warmup Iteration   1: 6.777 ops/ms
# Warmup Iteration   2: 10.529 ops/ms
# Warmup Iteration   3: 10.645 ops/ms
Iteration   1: 10.652 ops/ms
Iteration   2: 10.758 ops/ms
Iteration   3: 10.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.679 ±(99.9%) 1.281 ops/ms [Average]
  (min, avg, max) = (10.626, 10.679, 10.758), stdev = 0.070
  CI (99.9%): [9.398, 11.959] (assumes normal distribution)


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
# Warmup Iteration   1: 4.050 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.536 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.004 ms/op
Iteration   1: 2.531 ±(99.9%) 0.004 ms/op
Iteration   2: 2.560 ±(99.9%) 0.003 ms/op
Iteration   3: 2.501 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.531 ±(99.9%) 0.539 ms/op [Average]
  (min, avg, max) = (2.501, 2.531, 2.560), stdev = 0.030
  CI (99.9%): [1.992, 3.070] (assumes normal distribution)


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
# Warmup Iteration   1: 3.761 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.449 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.446 ±(99.9%) 0.004 ms/op
Iteration   1: 2.454 ±(99.9%) 0.004 ms/op
Iteration   2: 2.446 ±(99.9%) 0.004 ms/op
Iteration   3: 2.445 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.448 ±(99.9%) 0.089 ms/op [Average]
  (min, avg, max) = (2.445, 2.448, 2.454), stdev = 0.005
  CI (99.9%): [2.360, 2.537] (assumes normal distribution)


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
# Warmup Iteration   1: 4.301 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.528 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.004 ms/op
Iteration   1: 2.479 ±(99.9%) 0.004 ms/op
Iteration   2: 2.463 ±(99.9%) 0.004 ms/op
Iteration   3: 2.489 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.477 ±(99.9%) 0.239 ms/op [Average]
  (min, avg, max) = (2.463, 2.477, 2.489), stdev = 0.013
  CI (99.9%): [2.238, 2.716] (assumes normal distribution)


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
# Warmup Iteration   1: 4.687 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.013 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.006 ms/op
Iteration   1: 2.976 ±(99.9%) 0.006 ms/op
Iteration   2: 2.971 ±(99.9%) 0.005 ms/op
Iteration   3: 2.964 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.971 ±(99.9%) 0.106 ms/op [Average]
  (min, avg, max) = (2.964, 2.971, 2.976), stdev = 0.006
  CI (99.9%): [2.864, 3.077] (assumes normal distribution)


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
# Warmup Iteration   1: 4.150 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.611 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.006 ms/op
Iteration   1: 2.502 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.040 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.834 ms/op
                 createUser·p0.999:  11.266 ms/op
                 createUser·p0.9999: 13.249 ms/op
                 createUser·p1.00:   14.221 ms/op

Iteration   2: 2.478 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.033 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.117 ms/op
                 createUser·p0.99:   3.592 ms/op
                 createUser·p0.999:  9.634 ms/op
                 createUser·p0.9999: 12.829 ms/op
                 createUser·p1.00:   13.156 ms/op

Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.025 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.810 ms/op
                 createUser·p0.999:  8.520 ms/op
                 createUser·p0.9999: 10.420 ms/op
                 createUser·p1.00:   11.502 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 384265
  mean =      2.496 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 186097 
    [ 2.500,  3.750) = 194262 
    [ 3.750,  5.000) = 3146 
    [ 5.000,  6.250) = 255 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 133 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.025 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.752 ms/op
     p(99.9000) =      8.880 ms/op
     p(99.9900) =     13.074 ms/op
     p(99.9990) =     13.956 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


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
# Warmup Iteration   1: 3.790 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.487 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.441 ±(99.9%) 0.005 ms/op
Iteration   1: 2.424 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.988 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.330 ms/op
                 existUser·p0.999:  5.367 ms/op
                 existUser·p0.9999: 13.855 ms/op
                 existUser·p1.00:   14.516 ms/op

Iteration   2: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.924 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.482 ms/op
                 existUser·p0.999:  5.661 ms/op
                 existUser·p0.9999: 12.156 ms/op
                 existUser·p1.00:   12.780 ms/op

Iteration   3: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.801 ms/op
                 existUser·p0.999:  8.032 ms/op
                 existUser·p0.9999: 12.123 ms/op
                 existUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392567
  mean =      2.443 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 194441 
    [ 2.500,  3.750) = 195319 
    [ 3.750,  5.000) = 2001 
    [ 5.000,  6.250) = 321 
    [ 6.250,  7.500) = 80 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 136 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.924 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.527 ms/op
     p(99.9000) =      6.578 ms/op
     p(99.9900) =     13.050 ms/op
     p(99.9990) =     14.094 ms/op
     p(99.9999) =     14.516 ms/op
    p(100.0000) =     14.516 ms/op


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
# Warmup Iteration   1: 3.816 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.550 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.006 ms/op
Iteration   1: 2.470 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.849 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.596 ms/op
                 getUser·p0.999:  6.646 ms/op
                 getUser·p0.9999: 14.025 ms/op
                 getUser·p1.00:   14.893 ms/op

Iteration   2: 2.485 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.911 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.777 ms/op
                 getUser·p0.999:  7.810 ms/op
                 getUser·p0.9999: 13.699 ms/op
                 getUser·p1.00:   14.844 ms/op

Iteration   3: 2.520 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.027 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.232 ms/op
                 getUser·p0.99:   4.702 ms/op
                 getUser·p0.999:  9.030 ms/op
                 getUser·p0.9999: 10.945 ms/op
                 getUser·p1.00:   11.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384908
  mean =      2.492 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 191787 
    [ 2.500,  3.750) = 188039 
    [ 3.750,  5.000) = 3597 
    [ 5.000,  6.250) = 824 
    [ 6.250,  7.500) = 189 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 163 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.985 ms/op
     p(99.9000) =      8.898 ms/op
     p(99.9900) =     13.640 ms/op
     p(99.9990) =     14.477 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


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
# Warmup Iteration   1: 4.740 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.009 ms/op
Iteration   1: 2.985 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.885 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.764 ms/op
                 listUser·p0.9999: 15.398 ms/op
                 listUser·p1.00:   15.794 ms/op

Iteration   2: 3.002 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.967 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.265 ms/op
                 listUser·p0.9999: 10.737 ms/op
                 listUser·p1.00:   11.190 ms/op

Iteration   3: 2.997 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.799 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.961 ms/op
                 listUser·p0.9999: 11.895 ms/op
                 listUser·p1.00:   12.730 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320280
  mean =      2.994 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 166 
    [ 1.250,  2.500) = 95612 
    [ 2.500,  3.750) = 186373 
    [ 3.750,  5.000) = 31342 
    [ 5.000,  6.250) = 5440 
    [ 6.250,  7.500) = 646 
    [ 7.500,  8.750) = 172 
    [ 8.750, 10.000) = 264 
    [10.000, 11.250) = 183 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.732 ms/op
     p(99.9900) =     14.576 ms/op
     p(99.9990) =     15.761 ms/op
     p(99.9999) =     15.794 ms/op
    p(100.0000) =     15.794 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.414 ± 2.365  ops/ms
ClientPb.existUser                       thrpt       3  12.934 ± 0.567  ops/ms
ClientPb.getUser                         thrpt       3  12.637 ± 2.987  ops/ms
ClientPb.listUser                        thrpt       3  10.679 ± 1.281  ops/ms
ClientPb.createUser                       avgt       3   2.531 ± 0.539   ms/op
ClientPb.existUser                        avgt       3   2.448 ± 0.089   ms/op
ClientPb.getUser                          avgt       3   2.477 ± 0.239   ms/op
ClientPb.listUser                         avgt       3   2.971 ± 0.106   ms/op
ClientPb.createUser                     sample  384265   2.496 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.025           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.027           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.880           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.074           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.221           ms/op
ClientPb.existUser                      sample  392567   2.443 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.924           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.527           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.578           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.050           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.516           ms/op
ClientPb.getUser                        sample  384908   2.492 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.849           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.150           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.985           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.898           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.640           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.893           ms/op
ClientPb.listUser                       sample  320280   2.994 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.799           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.732           ms/op
ClientPb.listUser:listUser·p0.9999      sample          14.576           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.794           ms/op
```
