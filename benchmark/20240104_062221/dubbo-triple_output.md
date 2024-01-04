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
[INFO] benchmark-base ..................................... SUCCESS [  3.011 s]
[INFO] server-base ........................................ SUCCESS [  0.312 s]
[INFO] client-base ........................................ SUCCESS [  0.577 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.419 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  4.632 s
[INFO] Finished at: 2024-01-04T06:09:00Z
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
# Warmup Iteration   1: 5.001 ops/ms
# Warmup Iteration   2: 12.307 ops/ms
# Warmup Iteration   3: 12.423 ops/ms
Iteration   1: 12.640 ops/ms
Iteration   2: 12.818 ops/ms
Iteration   3: 12.676 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.711 ±(99.9%) 1.715 ops/ms [Average]
  (min, avg, max) = (12.640, 12.711, 12.818), stdev = 0.094
  CI (99.9%): [10.996, 14.426] (assumes normal distribution)


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
# Warmup Iteration   1: 8.375 ops/ms
# Warmup Iteration   2: 12.888 ops/ms
# Warmup Iteration   3: 12.877 ops/ms
Iteration   1: 12.904 ops/ms
Iteration   2: 12.965 ops/ms
Iteration   3: 12.873 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.914 ±(99.9%) 0.849 ops/ms [Average]
  (min, avg, max) = (12.873, 12.914, 12.965), stdev = 0.047
  CI (99.9%): [12.065, 13.762] (assumes normal distribution)


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
# Warmup Iteration   1: 7.884 ops/ms
# Warmup Iteration   2: 12.750 ops/ms
# Warmup Iteration   3: 12.962 ops/ms
Iteration   1: 12.830 ops/ms
Iteration   2: 12.897 ops/ms
Iteration   3: 13.027 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.918 ±(99.9%) 1.821 ops/ms [Average]
  (min, avg, max) = (12.830, 12.918, 13.027), stdev = 0.100
  CI (99.9%): [11.097, 14.739] (assumes normal distribution)


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
# Warmup Iteration   1: 6.430 ops/ms
# Warmup Iteration   2: 10.411 ops/ms
# Warmup Iteration   3: 10.630 ops/ms
Iteration   1: 10.778 ops/ms
Iteration   2: 10.710 ops/ms
Iteration   3: 10.649 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.712 ±(99.9%) 1.176 ops/ms [Average]
  (min, avg, max) = (10.649, 10.712, 10.778), stdev = 0.064
  CI (99.9%): [9.536, 11.889] (assumes normal distribution)


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
# Warmup Iteration   1: 3.899 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.554 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.004 ms/op
Iteration   1: 2.493 ±(99.9%) 0.004 ms/op
Iteration   2: 2.469 ±(99.9%) 0.005 ms/op
Iteration   3: 2.488 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.483 ±(99.9%) 0.225 ms/op [Average]
  (min, avg, max) = (2.469, 2.483, 2.493), stdev = 0.012
  CI (99.9%): [2.258, 2.709] (assumes normal distribution)


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
# Warmup Iteration   1: 3.677 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.483 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.004 ms/op
Iteration   1: 2.450 ±(99.9%) 0.004 ms/op
Iteration   2: 2.438 ±(99.9%) 0.003 ms/op
Iteration   3: 2.466 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.451 ±(99.9%) 0.258 ms/op [Average]
  (min, avg, max) = (2.438, 2.451, 2.466), stdev = 0.014
  CI (99.9%): [2.193, 2.709] (assumes normal distribution)


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
# Warmup Iteration   1: 3.787 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.003 ms/op
Iteration   1: 2.486 ±(99.9%) 0.004 ms/op
Iteration   2: 2.485 ±(99.9%) 0.004 ms/op
Iteration   3: 2.499 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.490 ±(99.9%) 0.145 ms/op [Average]
  (min, avg, max) = (2.485, 2.490, 2.499), stdev = 0.008
  CI (99.9%): [2.345, 2.635] (assumes normal distribution)


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
# Warmup Iteration   1: 4.662 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.006 ms/op
Iteration   1: 3.022 ±(99.9%) 0.006 ms/op
Iteration   2: 2.972 ±(99.9%) 0.005 ms/op
Iteration   3: 3.006 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.000 ±(99.9%) 0.468 ms/op [Average]
  (min, avg, max) = (2.972, 3.000, 3.022), stdev = 0.026
  CI (99.9%): [2.532, 3.468] (assumes normal distribution)


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
# Warmup Iteration   1: 4.370 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.649 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.006 ms/op
Iteration   1: 2.504 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.817 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.789 ms/op
                 createUser·p0.999:  10.909 ms/op
                 createUser·p0.9999: 13.770 ms/op
                 createUser·p1.00:   14.287 ms/op

Iteration   2: 2.567 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.012 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.836 ms/op
                 createUser·p0.999:  8.978 ms/op
                 createUser·p0.9999: 11.889 ms/op
                 createUser·p1.00:   12.599 ms/op

Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.463 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.883 ms/op
                 createUser·p0.999:  9.290 ms/op
                 createUser·p0.9999: 12.500 ms/op
                 createUser·p1.00:   13.402 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379838
  mean =      2.525 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 183978 
    [ 2.500,  3.750) = 191373 
    [ 3.750,  5.000) = 3598 
    [ 5.000,  6.250) = 394 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 111 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.463 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =      9.262 ms/op
     p(99.9900) =     13.239 ms/op
     p(99.9990) =     14.015 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.686 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.484 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
Iteration   1: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.966 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.371 ms/op
                 existUser·p0.999:  5.936 ms/op
                 existUser·p0.9999: 13.517 ms/op
                 existUser·p1.00:   14.303 ms/op

Iteration   2: 2.457 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.551 ms/op
                 existUser·p0.999:  7.053 ms/op
                 existUser·p0.9999: 12.681 ms/op
                 existUser·p1.00:   13.337 ms/op

Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.731 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   4.145 ms/op
                 existUser·p0.999:  6.655 ms/op
                 existUser·p0.9999: 12.523 ms/op
                 existUser·p1.00:   13.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388571
  mean =      2.468 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 191059 
    [ 2.500,  3.750) = 193992 
    [ 3.750,  5.000) = 2302 
    [ 5.000,  6.250) = 753 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 118 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.675 ms/op
     p(99.9000) =      6.786 ms/op
     p(99.9900) =     13.337 ms/op
     p(99.9990) =     14.240 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


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
# Warmup Iteration   1: 3.985 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.006 ms/op
Iteration   1: 2.499 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.864 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.752 ms/op
                 getUser·p0.999:  11.062 ms/op
                 getUser·p0.9999: 14.176 ms/op
                 getUser·p1.00:   14.483 ms/op

Iteration   2: 2.427 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.901 ms/op
                 getUser·p0.50:   2.449 ms/op
                 getUser·p0.90:   2.957 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   4.146 ms/op
                 getUser·p0.999:  6.995 ms/op
                 getUser·p0.9999: 12.667 ms/op
                 getUser·p1.00:   13.369 ms/op

Iteration   3: 2.465 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.425 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.727 ms/op
                 getUser·p0.999:  6.326 ms/op
                 getUser·p0.9999: 11.764 ms/op
                 getUser·p1.00:   12.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389441
  mean =      2.463 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 100 
    [ 1.250,  2.500) = 197263 
    [ 2.500,  3.750) = 187775 
    [ 3.750,  5.000) = 3342 
    [ 5.000,  6.250) = 543 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 123 
    [11.250, 12.500) = 109 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.425 ms/op
     p(50.0000) =      2.474 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.813 ms/op
     p(99.9000) =      7.033 ms/op
     p(99.9900) =     13.582 ms/op
     p(99.9990) =     14.354 ms/op
     p(99.9999) =     14.483 ms/op
    p(100.0000) =     14.483 ms/op


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
# Warmup Iteration   1: 4.768 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.009 ms/op
Iteration   1: 2.997 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.915 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.126 ms/op
                 listUser·p0.9999: 12.845 ms/op
                 listUser·p1.00:   13.730 ms/op

Iteration   2: 3.010 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.876 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.384 ms/op
                 listUser·p0.9999: 16.779 ms/op
                 listUser·p1.00:   17.367 ms/op

Iteration   3: 2.995 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.903 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.184 ms/op
                 listUser·p0.9999: 11.271 ms/op
                 listUser·p1.00:   11.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319638
  mean =      3.001 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 139 
    [ 1.250,  2.500) = 93818 
    [ 2.500,  3.750) = 187839 
    [ 3.750,  5.000) = 30446 
    [ 5.000,  6.250) = 6025 
    [ 6.250,  7.500) = 684 
    [ 7.500,  8.750) = 229 
    [ 8.750, 10.000) = 265 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.257 ms/op
     p(99.9900) =     15.715 ms/op
     p(99.9990) =     17.321 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.711 ± 1.715  ops/ms
ClientPb.existUser                       thrpt       3  12.914 ± 0.849  ops/ms
ClientPb.getUser                         thrpt       3  12.918 ± 1.821  ops/ms
ClientPb.listUser                        thrpt       3  10.712 ± 1.176  ops/ms
ClientPb.createUser                       avgt       3   2.483 ± 0.225   ms/op
ClientPb.existUser                        avgt       3   2.451 ± 0.258   ms/op
ClientPb.getUser                          avgt       3   2.490 ± 0.145   ms/op
ClientPb.listUser                         avgt       3   3.000 ± 0.468   ms/op
ClientPb.createUser                     sample  379838   2.525 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.463           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.262           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.239           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.287           ms/op
ClientPb.existUser                      sample  388571   2.468 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.731           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.675           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.786           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.337           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.303           ms/op
ClientPb.getUser                        sample  389441   2.463 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.425           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.474           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.011           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.813           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.033           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.582           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.483           ms/op
ClientPb.listUser                       sample  319638   3.001 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.876           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.257           ms/op
ClientPb.listUser:listUser·p0.9999      sample          15.715           ms/op
ClientPb.listUser:listUser·p1.00        sample          17.367           ms/op
```
