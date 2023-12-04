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
[INFO] benchmark-base ..................................... SUCCESS [  2.829 s]
[INFO] server-base ........................................ SUCCESS [  0.323 s]
[INFO] client-base ........................................ SUCCESS [  0.647 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.519 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  4.622 s
[INFO] Finished at: 2023-12-04T18:08:42Z
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
# Warmup Iteration   1: 4.732 ops/ms
# Warmup Iteration   2: 11.985 ops/ms
# Warmup Iteration   3: 12.318 ops/ms
Iteration   1: 12.417 ops/ms
Iteration   2: 12.588 ops/ms
Iteration   3: 12.603 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.536 ±(99.9%) 1.887 ops/ms [Average]
  (min, avg, max) = (12.417, 12.536, 12.603), stdev = 0.103
  CI (99.9%): [10.649, 14.423] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 7.674 ops/ms
# Warmup Iteration   2: 13.038 ops/ms
# Warmup Iteration   3: 13.206 ops/ms
Iteration   1: 13.082 ops/ms
Iteration   2: 13.067 ops/ms
Iteration   3: 13.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.080 ±(99.9%) 0.229 ops/ms [Average]
  (min, avg, max) = (13.067, 13.080, 13.092), stdev = 0.013
  CI (99.9%): [12.851, 13.310] (assumes normal distribution)


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
# Warmup Iteration   1: 7.971 ops/ms
# Warmup Iteration   2: 12.649 ops/ms
# Warmup Iteration   3: 12.656 ops/ms
Iteration   1: 12.961 ops/ms
Iteration   2: 12.849 ops/ms
Iteration   3: 12.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.861 ±(99.9%) 1.721 ops/ms [Average]
  (min, avg, max) = (12.774, 12.861, 12.961), stdev = 0.094
  CI (99.9%): [11.140, 14.583] (assumes normal distribution)


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
# Warmup Iteration   1: 6.813 ops/ms
# Warmup Iteration   2: 10.444 ops/ms
# Warmup Iteration   3: 10.437 ops/ms
Iteration   1: 10.565 ops/ms
Iteration   2: 10.637 ops/ms
Iteration   3: 10.614 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.606 ±(99.9%) 0.672 ops/ms [Average]
  (min, avg, max) = (10.565, 10.606, 10.637), stdev = 0.037
  CI (99.9%): [9.933, 11.278] (assumes normal distribution)


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
# Warmup Iteration   1: 4.054 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.606 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.005 ms/op
Iteration   1: 2.531 ±(99.9%) 0.004 ms/op
Iteration   2: 2.543 ±(99.9%) 0.004 ms/op
Iteration   3: 2.504 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.526 ±(99.9%) 0.364 ms/op [Average]
  (min, avg, max) = (2.504, 2.526, 2.543), stdev = 0.020
  CI (99.9%): [2.161, 2.890] (assumes normal distribution)


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
# Warmup Iteration   1: 3.814 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.524 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.004 ms/op
Iteration   1: 2.510 ±(99.9%) 0.004 ms/op
Iteration   2: 2.508 ±(99.9%) 0.003 ms/op
Iteration   3: 2.514 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.511 ±(99.9%) 0.058 ms/op [Average]
  (min, avg, max) = (2.508, 2.511, 2.514), stdev = 0.003
  CI (99.9%): [2.453, 2.569] (assumes normal distribution)


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
# Warmup Iteration   1: 3.788 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.004 ms/op
Iteration   1: 2.490 ±(99.9%) 0.004 ms/op
Iteration   2: 2.494 ±(99.9%) 0.004 ms/op
Iteration   3: 2.519 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.501 ±(99.9%) 0.284 ms/op [Average]
  (min, avg, max) = (2.490, 2.501, 2.519), stdev = 0.016
  CI (99.9%): [2.216, 2.785] (assumes normal distribution)


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
# Warmup Iteration   1: 4.789 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.014 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.005 ms/op
Iteration   1: 3.006 ±(99.9%) 0.006 ms/op
Iteration   2: 3.010 ±(99.9%) 0.005 ms/op
Iteration   3: 3.000 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.005 ±(99.9%) 0.086 ms/op [Average]
  (min, avg, max) = (3.000, 3.005, 3.010), stdev = 0.005
  CI (99.9%): [2.919, 3.092] (assumes normal distribution)


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
# Warmup Iteration   1: 4.218 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.652 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.007 ms/op
Iteration   1: 2.509 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.980 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.715 ms/op
                 createUser·p0.999:  11.657 ms/op
                 createUser·p0.9999: 13.881 ms/op
                 createUser·p1.00:   14.680 ms/op

Iteration   2: 2.553 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   3.932 ms/op
                 createUser·p0.999:  10.060 ms/op
                 createUser·p0.9999: 12.173 ms/op
                 createUser·p1.00:   12.583 ms/op

Iteration   3: 2.561 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.996 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   3.998 ms/op
                 createUser·p0.999:  8.751 ms/op
                 createUser·p0.9999: 12.010 ms/op
                 createUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377622
  mean =      2.541 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 179926 
    [ 2.500,  3.750) = 192883 
    [ 3.750,  5.000) = 3916 
    [ 5.000,  6.250) = 427 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 103 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.965 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.883 ms/op
     p(99.9000) =      8.798 ms/op
     p(99.9900) =     13.607 ms/op
     p(99.9990) =     18.259 ms/op
     p(99.9999) =     18.579 ms/op
    p(100.0000) =     18.579 ms/op


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
# Warmup Iteration   1: 3.747 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.495 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
Iteration   1: 2.449 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.889 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.666 ms/op
                 existUser·p0.999:  5.909 ms/op
                 existUser·p0.9999: 13.336 ms/op
                 existUser·p1.00:   14.270 ms/op

Iteration   2: 2.484 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.745 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.682 ms/op
                 existUser·p0.999:  7.980 ms/op
                 existUser·p0.9999: 13.165 ms/op
                 existUser·p1.00:   14.303 ms/op

Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.950 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.195 ms/op
                 existUser·p0.99:   4.214 ms/op
                 existUser·p0.999:  8.995 ms/op
                 existUser·p0.9999: 11.216 ms/op
                 existUser·p1.00:   11.928 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386583
  mean =      2.481 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 192020 
    [ 2.500,  3.750) = 190214 
    [ 3.750,  5.000) = 3270 
    [ 5.000,  6.250) = 601 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =      7.234 ms/op
     p(99.9900) =     13.146 ms/op
     p(99.9990) =     14.207 ms/op
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
# Warmup Iteration   1: 4.000 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.597 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.006 ms/op
Iteration   1: 2.532 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.888 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.817 ms/op
                 getUser·p0.999:  11.906 ms/op
                 getUser·p0.9999: 15.407 ms/op
                 getUser·p1.00:   15.761 ms/op

Iteration   2: 2.550 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.680 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   4.137 ms/op
                 getUser·p0.999:  10.415 ms/op
                 getUser·p0.9999: 13.878 ms/op
                 getUser·p1.00:   14.877 ms/op

Iteration   3: 2.518 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.867 ms/op
                 getUser·p0.999:  8.225 ms/op
                 getUser·p0.9999: 11.878 ms/op
                 getUser·p1.00:   12.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378607
  mean =      2.533 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 185823 
    [ 2.500,  3.750) = 187614 
    [ 3.750,  5.000) = 3894 
    [ 5.000,  6.250) = 726 
    [ 6.250,  7.500) = 112 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.944 ms/op
     p(99.9000) =      8.831 ms/op
     p(99.9900) =     14.296 ms/op
     p(99.9990) =     15.568 ms/op
     p(99.9999) =     15.761 ms/op
    p(100.0000) =     15.761 ms/op


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
# Warmup Iteration   1: 4.862 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.009 ms/op
Iteration   1: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.779 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.526 ms/op
                 listUser·p0.9999: 11.201 ms/op
                 listUser·p1.00:   12.042 ms/op

Iteration   2: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.860 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.388 ms/op
                 listUser·p0.9999: 14.688 ms/op
                 listUser·p1.00:   16.941 ms/op

Iteration   3: 3.007 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.933 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  8.487 ms/op
                 listUser·p0.9999: 10.706 ms/op
                 listUser·p1.00:   11.633 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318867
  mean =      3.008 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 137 
    [ 1.250,  2.500) = 92965 
    [ 2.500,  3.750) = 186881 
    [ 3.750,  5.000) = 31579 
    [ 5.000,  6.250) = 5974 
    [ 6.250,  7.500) = 682 
    [ 7.500,  8.750) = 268 
    [ 8.750, 10.000) = 216 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.161 ms/op
     p(99.9900) =     13.126 ms/op
     p(99.9990) =     16.388 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.536 ± 1.887  ops/ms
ClientPb.existUser                       thrpt       3  13.080 ± 0.229  ops/ms
ClientPb.getUser                         thrpt       3  12.861 ± 1.721  ops/ms
ClientPb.listUser                        thrpt       3  10.606 ± 0.672  ops/ms
ClientPb.createUser                       avgt       3   2.526 ± 0.364   ms/op
ClientPb.existUser                        avgt       3   2.511 ± 0.058   ms/op
ClientPb.getUser                          avgt       3   2.501 ± 0.284   ms/op
ClientPb.listUser                         avgt       3   3.005 ± 0.086   ms/op
ClientPb.createUser                     sample  377622   2.541 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.965           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.798           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.607           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.579           ms/op
ClientPb.existUser                      sample  386583   2.481 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.745           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.822           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.234           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.146           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.303           ms/op
ClientPb.getUser                        sample  378607   2.533 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.680           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.544           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.944           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.831           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.296           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.761           ms/op
ClientPb.listUser                       sample  318867   3.008 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.779           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.161           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.126           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.941           ms/op
```
