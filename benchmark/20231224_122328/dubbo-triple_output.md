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
[INFO] benchmark-base ..................................... SUCCESS [  2.918 s]
[INFO] server-base ........................................ SUCCESS [  0.334 s]
[INFO] client-base ........................................ SUCCESS [  0.629 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.504 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  4.681 s
[INFO] Finished at: 2023-12-24T12:09:44Z
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
# Warmup Iteration   1: 4.984 ops/ms
# Warmup Iteration   2: 12.391 ops/ms
# Warmup Iteration   3: 12.595 ops/ms
Iteration   1: 12.750 ops/ms
Iteration   2: 12.889 ops/ms
Iteration   3: 12.905 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.848 ±(99.9%) 1.556 ops/ms [Average]
  (min, avg, max) = (12.750, 12.848, 12.905), stdev = 0.085
  CI (99.9%): [11.292, 14.404] (assumes normal distribution)


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
# Warmup Iteration   1: 8.425 ops/ms
# Warmup Iteration   2: 13.088 ops/ms
# Warmup Iteration   3: 13.232 ops/ms
Iteration   1: 13.106 ops/ms
Iteration   2: 13.134 ops/ms
Iteration   3: 13.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.121 ±(99.9%) 0.260 ops/ms [Average]
  (min, avg, max) = (13.106, 13.121, 13.134), stdev = 0.014
  CI (99.9%): [12.861, 13.381] (assumes normal distribution)


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
# Warmup Iteration   1: 8.384 ops/ms
# Warmup Iteration   2: 12.733 ops/ms
# Warmup Iteration   3: 12.863 ops/ms
Iteration   1: 13.034 ops/ms
Iteration   2: 12.819 ops/ms
Iteration   3: 12.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.936 ±(99.9%) 1.983 ops/ms [Average]
  (min, avg, max) = (12.819, 12.936, 13.034), stdev = 0.109
  CI (99.9%): [10.953, 14.920] (assumes normal distribution)


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
# Warmup Iteration   1: 7.002 ops/ms
# Warmup Iteration   2: 10.738 ops/ms
# Warmup Iteration   3: 10.763 ops/ms
Iteration   1: 10.802 ops/ms
Iteration   2: 10.891 ops/ms
Iteration   3: 10.811 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.834 ±(99.9%) 0.893 ops/ms [Average]
  (min, avg, max) = (10.802, 10.834, 10.891), stdev = 0.049
  CI (99.9%): [9.941, 11.728] (assumes normal distribution)


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
# Warmup Iteration   1: 3.931 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.550 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.002 ms/op
Iteration   1: 2.445 ±(99.9%) 0.004 ms/op
Iteration   2: 2.490 ±(99.9%) 0.004 ms/op
Iteration   3: 2.457 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.464 ±(99.9%) 0.424 ms/op [Average]
  (min, avg, max) = (2.445, 2.464, 2.490), stdev = 0.023
  CI (99.9%): [2.040, 2.888] (assumes normal distribution)


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
# Warmup Iteration   1: 3.718 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.416 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.444 ±(99.9%) 0.004 ms/op
Iteration   1: 2.426 ±(99.9%) 0.003 ms/op
Iteration   2: 2.447 ±(99.9%) 0.004 ms/op
Iteration   3: 2.419 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.431 ±(99.9%) 0.259 ms/op [Average]
  (min, avg, max) = (2.419, 2.431, 2.447), stdev = 0.014
  CI (99.9%): [2.172, 2.690] (assumes normal distribution)


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
# Warmup Iteration   1: 3.739 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.506 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
Iteration   1: 2.451 ±(99.9%) 0.004 ms/op
Iteration   2: 2.464 ±(99.9%) 0.004 ms/op
Iteration   3: 2.464 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.460 ±(99.9%) 0.142 ms/op [Average]
  (min, avg, max) = (2.451, 2.460, 2.464), stdev = 0.008
  CI (99.9%): [2.318, 2.601] (assumes normal distribution)


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
# Warmup Iteration   1: 4.654 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.013 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.006 ms/op
Iteration   1: 2.974 ±(99.9%) 0.005 ms/op
Iteration   2: 2.960 ±(99.9%) 0.005 ms/op
Iteration   3: 2.968 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.967 ±(99.9%) 0.130 ms/op [Average]
  (min, avg, max) = (2.960, 2.967, 2.974), stdev = 0.007
  CI (99.9%): [2.837, 3.097] (assumes normal distribution)


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
# Warmup Iteration   1: 4.066 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.636 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
Iteration   1: 2.494 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.587 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.672 ms/op
                 createUser·p0.999:  11.070 ms/op
                 createUser·p0.9999: 13.064 ms/op
                 createUser·p1.00:   13.550 ms/op

Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.921 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.555 ms/op
                 createUser·p0.999:  8.473 ms/op
                 createUser·p0.9999: 11.183 ms/op
                 createUser·p1.00:   11.600 ms/op

Iteration   3: 2.518 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.810 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.867 ms/op
                 createUser·p0.999:  8.309 ms/op
                 createUser·p0.9999: 12.789 ms/op
                 createUser·p1.00:   15.598 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383200
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 185275 
    [ 2.500,  3.750) = 194373 
    [ 3.750,  5.000) = 2714 
    [ 5.000,  6.250) = 308 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 85 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 131 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.703 ms/op
     p(99.9000) =      8.700 ms/op
     p(99.9900) =     12.791 ms/op
     p(99.9990) =     13.490 ms/op
     p(99.9999) =     15.598 ms/op
    p(100.0000) =     15.598 ms/op


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
# Warmup Iteration   1: 3.670 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.429 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.438 ±(99.9%) 0.005 ms/op
Iteration   1: 2.422 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.872 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.420 ms/op
                 existUser·p0.999:  5.226 ms/op
                 existUser·p0.9999: 13.435 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   2: 2.446 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.985 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.842 ms/op
                 existUser·p0.999:  7.791 ms/op
                 existUser·p0.9999: 12.681 ms/op
                 existUser·p1.00:   13.812 ms/op

Iteration   3: 2.421 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.890 ms/op
                 existUser·p0.50:   2.425 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  8.897 ms/op
                 existUser·p0.9999: 11.990 ms/op
                 existUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394791
  mean =      2.430 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 200465 
    [ 2.500,  3.750) = 191122 
    [ 3.750,  5.000) = 2466 
    [ 5.000,  6.250) = 240 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 74 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      2.466 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      3.621 ms/op
     p(99.9000) =      7.390 ms/op
     p(99.9900) =     13.067 ms/op
     p(99.9990) =     13.796 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


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
# Warmup Iteration   1: 4.158 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.006 ms/op
Iteration   1: 2.488 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.889 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.715 ms/op
                 getUser·p0.999:  8.982 ms/op
                 getUser·p0.9999: 13.208 ms/op
                 getUser·p1.00:   14.221 ms/op

Iteration   2: 2.521 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.740 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.901 ms/op
                 getUser·p0.999:  9.093 ms/op
                 getUser·p0.9999: 12.599 ms/op
                 getUser·p1.00:   13.763 ms/op

Iteration   3: 2.492 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.913 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.887 ms/op
                 getUser·p0.999:  7.826 ms/op
                 getUser·p0.9999: 10.961 ms/op
                 getUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383520
  mean =      2.501 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 91 
    [ 1.250,  2.500) = 191516 
    [ 2.500,  3.750) = 187329 
    [ 3.750,  5.000) = 3692 
    [ 5.000,  6.250) = 486 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.846 ms/op
     p(99.9000) =      8.274 ms/op
     p(99.9900) =     12.675 ms/op
     p(99.9990) =     13.926 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.514 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.002 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.938 ±(99.9%) 0.008 ms/op
Iteration   1: 2.969 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.913 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.126 ms/op
                 listUser·p0.9999: 11.417 ms/op
                 listUser·p1.00:   12.780 ms/op

Iteration   2: 2.925 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.738 ms/op
                 listUser·p0.50:   2.871 ms/op
                 listUser·p0.90:   3.772 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   5.390 ms/op
                 listUser·p0.999:  9.055 ms/op
                 listUser·p0.9999: 11.194 ms/op
                 listUser·p1.00:   12.714 ms/op

Iteration   3: 2.925 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.843 ms/op
                 listUser·p0.50:   2.867 ms/op
                 listUser·p0.90:   3.768 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  8.716 ms/op
                 listUser·p0.9999: 10.437 ms/op
                 listUser·p1.00:   11.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 326322
  mean =      2.939 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 152 
    [ 1.250,  2.500) = 105164 
    [ 2.500,  3.750) = 185926 
    [ 3.750,  5.000) = 28728 
    [ 5.000,  6.250) = 5107 
    [ 6.250,  7.500) = 557 
    [ 7.500,  8.750) = 300 
    [ 8.750, 10.000) = 254 
    [10.000, 11.250) = 112 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =      9.006 ms/op
     p(99.9900) =     11.092 ms/op
     p(99.9990) =     12.705 ms/op
     p(99.9999) =     12.780 ms/op
    p(100.0000) =     12.780 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.848 ± 1.556  ops/ms
ClientPb.existUser                       thrpt       3  13.121 ± 0.260  ops/ms
ClientPb.getUser                         thrpt       3  12.936 ± 1.983  ops/ms
ClientPb.listUser                        thrpt       3  10.834 ± 0.893  ops/ms
ClientPb.createUser                       avgt       3   2.464 ± 0.424   ms/op
ClientPb.existUser                        avgt       3   2.431 ± 0.259   ms/op
ClientPb.getUser                          avgt       3   2.460 ± 0.142   ms/op
ClientPb.listUser                         avgt       3   2.967 ± 0.130   ms/op
ClientPb.createUser                     sample  383200   2.502 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.587           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.703           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.700           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.791           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.598           ms/op
ClientPb.existUser                      sample  394791   2.430 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.872           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.466           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.390           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.067           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.254           ms/op
ClientPb.getUser                        sample  383520   2.501 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.740           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.274           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.675           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.221           ms/op
ClientPb.listUser                       sample  326322   2.939 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.738           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.879           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.797           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.464           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.006           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.092           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.780           ms/op
```
