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
[INFO] benchmark-base ..................................... SUCCESS [  2.855 s]
[INFO] server-base ........................................ SUCCESS [  0.342 s]
[INFO] client-base ........................................ SUCCESS [  0.628 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.519 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  4.650 s
[INFO] Finished at: 2023-12-17T12:10:00Z
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
# Warmup Iteration   1: 5.167 ops/ms
# Warmup Iteration   2: 12.276 ops/ms
# Warmup Iteration   3: 12.184 ops/ms
Iteration   1: 12.539 ops/ms
Iteration   2: 12.543 ops/ms
Iteration   3: 12.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.548 ±(99.9%) 0.209 ops/ms [Average]
  (min, avg, max) = (12.539, 12.548, 12.561), stdev = 0.011
  CI (99.9%): [12.338, 12.757] (assumes normal distribution)


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
# Warmup Iteration   1: 8.260 ops/ms
# Warmup Iteration   2: 13.183 ops/ms
# Warmup Iteration   3: 13.299 ops/ms
Iteration   1: 13.217 ops/ms
Iteration   2: 13.305 ops/ms
Iteration   3: 13.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.250 ±(99.9%) 0.875 ops/ms [Average]
  (min, avg, max) = (13.217, 13.250, 13.305), stdev = 0.048
  CI (99.9%): [12.375, 14.125] (assumes normal distribution)


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
# Warmup Iteration   1: 7.800 ops/ms
# Warmup Iteration   2: 12.505 ops/ms
# Warmup Iteration   3: 12.828 ops/ms
Iteration   1: 12.904 ops/ms
Iteration   2: 12.946 ops/ms
Iteration   3: 12.858 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.903 ±(99.9%) 0.801 ops/ms [Average]
  (min, avg, max) = (12.858, 12.903, 12.946), stdev = 0.044
  CI (99.9%): [12.102, 13.704] (assumes normal distribution)


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
# Warmup Iteration   1: 6.802 ops/ms
# Warmup Iteration   2: 10.549 ops/ms
# Warmup Iteration   3: 10.595 ops/ms
Iteration   1: 10.663 ops/ms
Iteration   2: 10.591 ops/ms
Iteration   3: 10.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.650 ±(99.9%) 0.987 ops/ms [Average]
  (min, avg, max) = (10.591, 10.650, 10.697), stdev = 0.054
  CI (99.9%): [9.663, 11.638] (assumes normal distribution)


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
# Warmup Iteration   1: 3.872 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.575 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.003 ms/op
Iteration   1: 2.475 ±(99.9%) 0.004 ms/op
Iteration   2: 2.524 ±(99.9%) 0.004 ms/op
Iteration   3: 2.482 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.493 ±(99.9%) 0.487 ms/op [Average]
  (min, avg, max) = (2.475, 2.493, 2.524), stdev = 0.027
  CI (99.9%): [2.007, 2.980] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.527 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.438 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.003 ms/op
Iteration   1: 2.422 ±(99.9%) 0.004 ms/op
Iteration   2: 2.437 ±(99.9%) 0.005 ms/op
Iteration   3: 2.431 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.430 ±(99.9%) 0.134 ms/op [Average]
  (min, avg, max) = (2.422, 2.430, 2.437), stdev = 0.007
  CI (99.9%): [2.296, 2.564] (assumes normal distribution)


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
# Warmup Iteration   1: 3.815 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.516 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.004 ms/op
Iteration   1: 2.445 ±(99.9%) 0.004 ms/op
Iteration   2: 2.446 ±(99.9%) 0.003 ms/op
Iteration   3: 2.453 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.448 ±(99.9%) 0.082 ms/op [Average]
  (min, avg, max) = (2.445, 2.448, 2.453), stdev = 0.004
  CI (99.9%): [2.366, 2.530] (assumes normal distribution)


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
# Warmup Iteration   1: 4.800 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.993 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.006 ms/op
Iteration   1: 2.988 ±(99.9%) 0.006 ms/op
Iteration   2: 2.977 ±(99.9%) 0.005 ms/op
Iteration   3: 2.975 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.980 ±(99.9%) 0.126 ms/op [Average]
  (min, avg, max) = (2.975, 2.980, 2.988), stdev = 0.007
  CI (99.9%): [2.854, 3.106] (assumes normal distribution)


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
# Warmup Iteration   1: 4.142 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.584 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.006 ms/op
Iteration   1: 2.477 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.905 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   2.994 ms/op
                 createUser·p0.95:   3.105 ms/op
                 createUser·p0.99:   3.600 ms/op
                 createUser·p0.999:  7.045 ms/op
                 createUser·p0.9999: 13.633 ms/op
                 createUser·p1.00:   14.074 ms/op

Iteration   2: 2.500 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.580 ms/op
                 createUser·p0.999:  9.901 ms/op
                 createUser·p0.9999: 13.124 ms/op
                 createUser·p1.00:   13.550 ms/op

Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.954 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.785 ms/op
                 createUser·p0.999:  8.463 ms/op
                 createUser·p0.9999: 11.203 ms/op
                 createUser·p1.00:   11.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385073
  mean =      2.490 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 186061 
    [ 2.500,  3.750) = 195739 
    [ 3.750,  5.000) = 2500 
    [ 5.000,  6.250) = 275 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.658 ms/op
     p(99.9000) =      9.191 ms/op
     p(99.9900) =     13.238 ms/op
     p(99.9990) =     13.945 ms/op
     p(99.9999) =     14.074 ms/op
    p(100.0000) =     14.074 ms/op


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
# Warmup Iteration   1: 3.633 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.441 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.433 ±(99.9%) 0.005 ms/op
Iteration   1: 2.403 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.894 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.904 ms/op
                 existUser·p0.95:   2.986 ms/op
                 existUser·p0.99:   3.236 ms/op
                 existUser·p0.999:  5.472 ms/op
                 existUser·p0.9999: 13.156 ms/op
                 existUser·p1.00:   13.746 ms/op

Iteration   2: 2.428 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.923 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.389 ms/op
                 existUser·p0.999:  5.975 ms/op
                 existUser·p0.9999: 12.648 ms/op
                 existUser·p1.00:   12.976 ms/op

Iteration   3: 2.429 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.948 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.742 ms/op
                 existUser·p0.999:  5.789 ms/op
                 existUser·p0.9999: 11.859 ms/op
                 existUser·p1.00:   12.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396339
  mean =      2.420 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 197918 
    [ 2.500,  3.750) = 195798 
    [ 3.750,  5.000) = 1943 
    [ 5.000,  6.250) = 270 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 121 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.933 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      3.465 ms/op
     p(99.9000) =      5.811 ms/op
     p(99.9900) =     13.009 ms/op
     p(99.9990) =     13.697 ms/op
     p(99.9999) =     13.746 ms/op
    p(100.0000) =     13.746 ms/op


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
# Warmup Iteration   1: 3.858 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
Iteration   1: 2.456 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.649 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   2.978 ms/op
                 getUser·p0.95:   3.080 ms/op
                 getUser·p0.99:   3.637 ms/op
                 getUser·p0.999:  6.671 ms/op
                 getUser·p0.9999: 13.550 ms/op
                 getUser·p1.00:   14.320 ms/op

Iteration   2: 2.451 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.904 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   2.970 ms/op
                 getUser·p0.95:   3.052 ms/op
                 getUser·p0.99:   3.391 ms/op
                 getUser·p0.999:  5.965 ms/op
                 getUser·p0.9999: 12.418 ms/op
                 getUser·p1.00:   13.664 ms/op

Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.901 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  8.349 ms/op
                 getUser·p0.9999: 11.734 ms/op
                 getUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388430
  mean =      2.469 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 193610 
    [ 2.500,  3.750) = 190583 
    [ 3.750,  5.000) = 3221 
    [ 5.000,  6.250) = 466 
    [ 6.250,  7.500) = 92 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 118 
    [11.250, 12.500) = 133 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.649 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.801 ms/op
     p(99.9000) =      7.940 ms/op
     p(99.9900) =     13.208 ms/op
     p(99.9990) =     13.848 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


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
# Warmup Iteration   1: 4.645 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.033 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.008 ms/op
Iteration   1: 2.991 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.791 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.079 ms/op
                 listUser·p0.9999: 11.790 ms/op
                 listUser·p1.00:   12.780 ms/op

Iteration   2: 2.989 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.839 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.651 ms/op
                 listUser·p0.9999: 10.966 ms/op
                 listUser·p1.00:   11.420 ms/op

Iteration   3: 2.989 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.626 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.290 ms/op
                 listUser·p0.9999: 10.453 ms/op
                 listUser·p1.00:   11.026 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320800
  mean =      2.990 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 170 
    [ 1.250,  2.500) = 96052 
    [ 2.500,  3.750) = 185487 
    [ 3.750,  5.000) = 31874 
    [ 5.000,  6.250) = 5925 
    [ 6.250,  7.500) = 624 
    [ 7.500,  8.750) = 221 
    [ 8.750, 10.000) = 281 
    [10.000, 11.250) = 151 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.626 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.290 ms/op
     p(99.9900) =     10.846 ms/op
     p(99.9990) =     12.310 ms/op
     p(99.9999) =     12.780 ms/op
    p(100.0000) =     12.780 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.548 ± 0.209  ops/ms
ClientPb.existUser                       thrpt       3  13.250 ± 0.875  ops/ms
ClientPb.getUser                         thrpt       3  12.903 ± 0.801  ops/ms
ClientPb.listUser                        thrpt       3  10.650 ± 0.987  ops/ms
ClientPb.createUser                       avgt       3   2.493 ± 0.487   ms/op
ClientPb.existUser                        avgt       3   2.430 ± 0.134   ms/op
ClientPb.getUser                          avgt       3   2.448 ± 0.082   ms/op
ClientPb.listUser                         avgt       3   2.980 ± 0.126   ms/op
ClientPb.createUser                     sample  385073   2.490 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.905           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.580           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.658           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.191           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.238           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.074           ms/op
ClientPb.existUser                      sample  396339   2.420 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.894           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.933           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.465           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.811           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.009           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.746           ms/op
ClientPb.getUser                        sample  388430   2.469 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.649           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.940           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.208           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.320           ms/op
ClientPb.listUser                       sample  320800   2.990 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.626           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.290           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.846           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.780           ms/op
```
