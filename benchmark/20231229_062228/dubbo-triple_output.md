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
[INFO] benchmark-base ..................................... SUCCESS [  2.856 s]
[INFO] server-base ........................................ SUCCESS [  0.351 s]
[INFO] client-base ........................................ SUCCESS [  0.632 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.516 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  4.654 s
[INFO] Finished at: 2023-12-29T06:09:03Z
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
# Warmup Iteration   1: 5.208 ops/ms
# Warmup Iteration   2: 12.179 ops/ms
# Warmup Iteration   3: 12.625 ops/ms
Iteration   1: 12.750 ops/ms
Iteration   2: 12.863 ops/ms
Iteration   3: 12.845 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.819 ±(99.9%) 1.107 ops/ms [Average]
  (min, avg, max) = (12.750, 12.819, 12.863), stdev = 0.061
  CI (99.9%): [11.712, 13.926] (assumes normal distribution)


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
# Warmup Iteration   1: 8.425 ops/ms
# Warmup Iteration   2: 13.130 ops/ms
# Warmup Iteration   3: 13.182 ops/ms
Iteration   1: 13.201 ops/ms
Iteration   2: 13.287 ops/ms
Iteration   3: 13.192 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.227 ±(99.9%) 0.955 ops/ms [Average]
  (min, avg, max) = (13.192, 13.227, 13.287), stdev = 0.052
  CI (99.9%): [12.272, 14.181] (assumes normal distribution)


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
# Warmup Iteration   1: 8.270 ops/ms
# Warmup Iteration   2: 12.593 ops/ms
# Warmup Iteration   3: 12.823 ops/ms
Iteration   1: 12.942 ops/ms
Iteration   2: 12.764 ops/ms
Iteration   3: 12.790 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.832 ±(99.9%) 1.757 ops/ms [Average]
  (min, avg, max) = (12.764, 12.832, 12.942), stdev = 0.096
  CI (99.9%): [11.075, 14.590] (assumes normal distribution)


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
# Warmup Iteration   1: 6.870 ops/ms
# Warmup Iteration   2: 10.528 ops/ms
# Warmup Iteration   3: 10.647 ops/ms
Iteration   1: 10.708 ops/ms
Iteration   2: 10.802 ops/ms
Iteration   3: 10.731 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.747 ±(99.9%) 0.894 ops/ms [Average]
  (min, avg, max) = (10.708, 10.747, 10.802), stdev = 0.049
  CI (99.9%): [9.853, 11.642] (assumes normal distribution)


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
# Warmup Iteration   1: 3.884 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.603 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.004 ms/op
Iteration   1: 2.537 ±(99.9%) 0.003 ms/op
Iteration   2: 2.534 ±(99.9%) 0.004 ms/op
Iteration   3: 2.512 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.528 ±(99.9%) 0.245 ms/op [Average]
  (min, avg, max) = (2.512, 2.528, 2.537), stdev = 0.013
  CI (99.9%): [2.283, 2.772] (assumes normal distribution)


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
# Warmup Iteration   1: 3.685 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.443 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.004 ms/op
Iteration   1: 2.427 ±(99.9%) 0.004 ms/op
Iteration   2: 2.435 ±(99.9%) 0.004 ms/op
Iteration   3: 2.430 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.431 ±(99.9%) 0.074 ms/op [Average]
  (min, avg, max) = (2.427, 2.431, 2.435), stdev = 0.004
  CI (99.9%): [2.357, 2.504] (assumes normal distribution)


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
# Warmup Iteration   1: 3.894 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.518 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.004 ms/op
Iteration   1: 2.509 ±(99.9%) 0.004 ms/op
Iteration   2: 2.478 ±(99.9%) 0.004 ms/op
Iteration   3: 2.466 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.484 ±(99.9%) 0.411 ms/op [Average]
  (min, avg, max) = (2.466, 2.484, 2.509), stdev = 0.023
  CI (99.9%): [2.073, 2.895] (assumes normal distribution)


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
# Warmup Iteration   1: 4.607 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.030 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.005 ms/op
Iteration   1: 2.983 ±(99.9%) 0.006 ms/op
Iteration   2: 2.963 ±(99.9%) 0.005 ms/op
Iteration   3: 2.958 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.968 ±(99.9%) 0.239 ms/op [Average]
  (min, avg, max) = (2.958, 2.968, 2.983), stdev = 0.013
  CI (99.9%): [2.729, 3.207] (assumes normal distribution)


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
# Warmup Iteration   1: 4.140 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.644 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
Iteration   1: 2.474 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.907 ms/op
                 createUser·p0.50:   2.494 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.777 ms/op
                 createUser·p0.999:  7.172 ms/op
                 createUser·p0.9999: 13.731 ms/op
                 createUser·p1.00:   14.254 ms/op

Iteration   2: 2.471 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.802 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.097 ms/op
                 createUser·p0.99:   3.486 ms/op
                 createUser·p0.999:  5.573 ms/op
                 createUser·p0.9999: 11.656 ms/op
                 createUser·p1.00:   12.272 ms/op

Iteration   3: 2.494 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.996 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.740 ms/op
                 createUser·p0.999:  9.060 ms/op
                 createUser·p0.9999: 10.803 ms/op
                 createUser·p1.00:   11.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386825
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 190387 
    [ 2.500,  3.750) = 193052 
    [ 3.750,  5.000) = 2586 
    [ 5.000,  6.250) = 289 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 134 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.670 ms/op
     p(99.9000) =      8.881 ms/op
     p(99.9900) =     13.173 ms/op
     p(99.9990) =     14.162 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.792 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.496 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
Iteration   1: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.087 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.654 ms/op
                 existUser·p0.999:  6.469 ms/op
                 existUser·p0.9999: 13.729 ms/op
                 existUser·p1.00:   14.369 ms/op

Iteration   2: 2.464 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.963 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.543 ms/op
                 existUser·p0.999:  5.359 ms/op
                 existUser·p0.9999: 12.616 ms/op
                 existUser·p1.00:   13.746 ms/op

Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.911 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.641 ms/op
                 existUser·p0.999:  8.037 ms/op
                 existUser·p0.9999: 12.206 ms/op
                 existUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389548
  mean =      2.463 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 192263 
    [ 2.500,  3.750) = 194162 
    [ 3.750,  5.000) = 2384 
    [ 5.000,  6.250) = 265 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 130 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.613 ms/op
     p(99.9000) =      7.344 ms/op
     p(99.9900) =     13.042 ms/op
     p(99.9990) =     14.081 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


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
# Warmup Iteration   1: 3.945 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.561 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.006 ms/op
Iteration   1: 2.474 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.753 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.727 ms/op
                 getUser·p0.999:  6.557 ms/op
                 getUser·p0.9999: 13.731 ms/op
                 getUser·p1.00:   14.434 ms/op

Iteration   2: 2.503 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.897 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   4.030 ms/op
                 getUser·p0.999:  8.967 ms/op
                 getUser·p0.9999: 17.760 ms/op
                 getUser·p1.00:   17.924 ms/op

Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.744 ms/op
                 getUser·p0.999:  8.764 ms/op
                 getUser·p0.9999: 12.738 ms/op
                 getUser·p1.00:   13.402 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385427
  mean =      2.488 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 192335 
    [ 2.500,  3.750) = 188612 
    [ 3.750,  5.000) = 3407 
    [ 5.000,  6.250) = 565 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.830 ms/op
     p(99.9000) =      8.149 ms/op
     p(99.9900) =     14.028 ms/op
     p(99.9990) =     17.826 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 4.731 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.008 ms/op
Iteration   1: 2.988 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.951 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  8.569 ms/op
                 listUser·p0.9999: 10.232 ms/op
                 listUser·p1.00:   10.977 ms/op

Iteration   2: 2.954 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.684 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.789 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.688 ms/op
                 listUser·p0.9999: 12.108 ms/op
                 listUser·p1.00:   12.632 ms/op

Iteration   3: 2.988 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.933 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.699 ms/op
                 listUser·p0.9999: 12.172 ms/op
                 listUser·p1.00:   13.599 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322220
  mean =      2.976 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 132 
    [ 1.250,  2.500) = 100943 
    [ 2.500,  3.750) = 183610 
    [ 3.750,  5.000) = 30018 
    [ 5.000,  6.250) = 6253 
    [ 6.250,  7.500) = 615 
    [ 7.500,  8.750) = 187 
    [ 8.750, 10.000) = 289 
    [10.000, 11.250) = 128 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.221 ms/op
     p(99.9900) =     11.826 ms/op
     p(99.9990) =     13.193 ms/op
     p(99.9999) =     13.599 ms/op
    p(100.0000) =     13.599 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.819 ± 1.107  ops/ms
ClientPb.existUser                       thrpt       3  13.227 ± 0.955  ops/ms
ClientPb.getUser                         thrpt       3  12.832 ± 1.757  ops/ms
ClientPb.listUser                        thrpt       3  10.747 ± 0.894  ops/ms
ClientPb.createUser                       avgt       3   2.528 ± 0.245   ms/op
ClientPb.existUser                        avgt       3   2.431 ± 0.074   ms/op
ClientPb.getUser                          avgt       3   2.484 ± 0.411   ms/op
ClientPb.listUser                         avgt       3   2.968 ± 0.239   ms/op
ClientPb.createUser                     sample  386825   2.480 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.802           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.535           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.011           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.670           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.881           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.173           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.254           ms/op
ClientPb.existUser                      sample  389548   2.463 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.911           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.344           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.042           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.369           ms/op
ClientPb.getUser                        sample  385427   2.488 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.753           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.149           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.028           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.924           ms/op
ClientPb.listUser                       sample  322220   2.976 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.684           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.221           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.826           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.599           ms/op
```
