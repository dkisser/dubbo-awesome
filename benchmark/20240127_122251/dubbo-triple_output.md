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
[INFO] benchmark-base ..................................... SUCCESS [  2.783 s]
[INFO] server-base ........................................ SUCCESS [  0.338 s]
[INFO] client-base ........................................ SUCCESS [  0.644 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.343 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  4.409 s
[INFO] Finished at: 2024-01-27T12:09:28Z
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
# Warmup Iteration   1: 4.961 ops/ms
# Warmup Iteration   2: 12.353 ops/ms
# Warmup Iteration   3: 12.571 ops/ms
Iteration   1: 12.747 ops/ms
Iteration   2: 13.025 ops/ms
Iteration   3: 12.961 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.911 ±(99.9%) 2.663 ops/ms [Average]
  (min, avg, max) = (12.747, 12.911, 13.025), stdev = 0.146
  CI (99.9%): [10.248, 15.574] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.497 ops/ms
# Warmup Iteration   2: 13.124 ops/ms
# Warmup Iteration   3: 13.248 ops/ms
Iteration   1: 13.375 ops/ms
Iteration   2: 13.425 ops/ms
Iteration   3: 13.301 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.367 ±(99.9%) 1.147 ops/ms [Average]
  (min, avg, max) = (13.301, 13.367, 13.425), stdev = 0.063
  CI (99.9%): [12.221, 14.514] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.723 ops/ms
# Warmup Iteration   2: 12.833 ops/ms
# Warmup Iteration   3: 12.941 ops/ms
Iteration   1: 13.136 ops/ms
Iteration   2: 13.131 ops/ms
Iteration   3: 13.076 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.114 ±(99.9%) 0.611 ops/ms [Average]
  (min, avg, max) = (13.076, 13.114, 13.136), stdev = 0.033
  CI (99.9%): [12.504, 13.725] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.861 ops/ms
# Warmup Iteration   2: 10.409 ops/ms
# Warmup Iteration   3: 10.727 ops/ms
Iteration   1: 10.764 ops/ms
Iteration   2: 10.722 ops/ms
Iteration   3: 10.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.709 ±(99.9%) 1.139 ops/ms [Average]
  (min, avg, max) = (10.641, 10.709, 10.764), stdev = 0.062
  CI (99.9%): [9.570, 11.848] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.961 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.004 ms/op
Iteration   1: 2.470 ±(99.9%) 0.003 ms/op
Iteration   2: 2.497 ±(99.9%) 0.003 ms/op
Iteration   3: 2.470 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.479 ±(99.9%) 0.287 ms/op [Average]
  (min, avg, max) = (2.470, 2.479, 2.497), stdev = 0.016
  CI (99.9%): [2.192, 2.766] (assumes normal distribution)


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
# Warmup Iteration   1: 3.685 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.408 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.410 ±(99.9%) 0.004 ms/op
Iteration   1: 2.409 ±(99.9%) 0.004 ms/op
Iteration   2: 2.385 ±(99.9%) 0.004 ms/op
Iteration   3: 2.383 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.392 ±(99.9%) 0.260 ms/op [Average]
  (min, avg, max) = (2.383, 2.392, 2.409), stdev = 0.014
  CI (99.9%): [2.132, 2.652] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.759 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.513 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.444 ±(99.9%) 0.003 ms/op
Iteration   1: 2.441 ±(99.9%) 0.004 ms/op
Iteration   2: 2.451 ±(99.9%) 0.005 ms/op
Iteration   3: 2.463 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.452 ±(99.9%) 0.199 ms/op [Average]
  (min, avg, max) = (2.441, 2.452, 2.463), stdev = 0.011
  CI (99.9%): [2.252, 2.651] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.687 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.001 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.964 ±(99.9%) 0.005 ms/op
Iteration   1: 2.961 ±(99.9%) 0.005 ms/op
Iteration   2: 2.960 ±(99.9%) 0.004 ms/op
Iteration   3: 2.960 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.960 ±(99.9%) 0.018 ms/op [Average]
  (min, avg, max) = (2.960, 2.960, 2.961), stdev = 0.001
  CI (99.9%): [2.942, 2.979] (assumes normal distribution)


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
# Warmup Iteration   1: 3.763 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.565 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
Iteration   1: 2.453 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   2.978 ms/op
                 createUser·p0.95:   3.080 ms/op
                 createUser·p0.99:   3.539 ms/op
                 createUser·p0.999:  5.994 ms/op
                 createUser·p0.9999: 14.204 ms/op
                 createUser·p1.00:   14.549 ms/op

Iteration   2: 2.447 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.914 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   2.970 ms/op
                 createUser·p0.95:   3.068 ms/op
                 createUser·p0.99:   3.518 ms/op
                 createUser·p0.999:  6.513 ms/op
                 createUser·p0.9999: 11.043 ms/op
                 createUser·p1.00:   11.567 ms/op

Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.929 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.830 ms/op
                 createUser·p0.999:  8.716 ms/op
                 createUser·p0.9999: 11.707 ms/op
                 createUser·p1.00:   15.647 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 389891
  mean =      2.460 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 191520 
    [ 2.500,  3.750) = 195239 
    [ 3.750,  5.000) = 2415 
    [ 5.000,  6.250) = 194 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 80 
    [ 8.750, 10.000) = 168 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.914 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.633 ms/op
     p(99.9000) =      8.227 ms/op
     p(99.9900) =     12.845 ms/op
     p(99.9990) =     15.226 ms/op
     p(99.9999) =     15.647 ms/op
    p(100.0000) =     15.647 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.606 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.457 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
Iteration   1: 2.448 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.208 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.343 ms/op
                 existUser·p0.999:  5.824 ms/op
                 existUser·p0.9999: 13.107 ms/op
                 existUser·p1.00:   13.976 ms/op

Iteration   2: 2.448 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.075 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.645 ms/op
                 existUser·p0.999:  5.754 ms/op
                 existUser·p0.9999: 12.465 ms/op
                 existUser·p1.00:   12.730 ms/op

Iteration   3: 2.455 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.799 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.711 ms/op
                 existUser·p0.999:  6.298 ms/op
                 existUser·p0.9999: 12.319 ms/op
                 existUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391458
  mean =      2.450 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 24 
    [ 1.250,  2.500) = 194298 
    [ 2.500,  3.750) = 194050 
    [ 3.750,  5.000) = 2048 
    [ 5.000,  6.250) = 669 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 165 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      3.576 ms/op
     p(99.9000) =      5.759 ms/op
     p(99.9900) =     12.791 ms/op
     p(99.9990) =     13.567 ms/op
     p(99.9999) =     13.976 ms/op
    p(100.0000) =     13.976 ms/op


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
# Warmup Iteration   1: 3.787 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.455 ±(99.9%) 0.005 ms/op
Iteration   1: 2.439 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.880 ms/op
                 getUser·p0.50:   2.458 ms/op
                 getUser·p0.90:   2.970 ms/op
                 getUser·p0.95:   3.084 ms/op
                 getUser·p0.99:   3.699 ms/op
                 getUser·p0.999:  7.224 ms/op
                 getUser·p0.9999: 13.105 ms/op
                 getUser·p1.00:   13.500 ms/op

Iteration   2: 2.486 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  7.612 ms/op
                 getUser·p0.9999: 14.455 ms/op
                 getUser·p1.00:   16.695 ms/op

Iteration   3: 2.431 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.824 ms/op
                 getUser·p0.50:   2.445 ms/op
                 getUser·p0.90:   2.957 ms/op
                 getUser·p0.95:   3.064 ms/op
                 getUser·p0.99:   3.637 ms/op
                 getUser·p0.999:  6.579 ms/op
                 getUser·p0.9999: 10.446 ms/op
                 getUser·p1.00:   10.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 391284
  mean =      2.452 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 197441 
    [ 2.500,  3.750) = 188731 
    [ 3.750,  5.000) = 3868 
    [ 5.000,  6.250) = 707 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 122 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.965 ms/op
     p(99.9000) =      7.215 ms/op
     p(99.9900) =     13.258 ms/op
     p(99.9990) =     16.663 ms/op
     p(99.9999) =     16.695 ms/op
    p(100.0000) =     16.695 ms/op


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
# Warmup Iteration   1: 4.747 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.030 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.008 ms/op
Iteration   1: 2.999 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.949 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  9.688 ms/op
                 listUser·p0.9999: 13.850 ms/op
                 listUser·p1.00:   15.073 ms/op

Iteration   2: 2.970 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.815 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.590 ms/op
                 listUser·p0.9999: 11.014 ms/op
                 listUser·p1.00:   12.780 ms/op

Iteration   3: 2.951 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.990 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.407 ms/op
                 listUser·p0.999:  8.897 ms/op
                 listUser·p0.9999: 12.274 ms/op
                 listUser·p1.00:   12.681 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322695
  mean =      2.973 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 170 
    [ 1.250,  2.500) = 102268 
    [ 2.500,  3.750) = 183375 
    [ 3.750,  5.000) = 29865 
    [ 5.000,  6.250) = 5645 
    [ 6.250,  7.500) = 623 
    [ 7.500,  8.750) = 240 
    [ 8.750, 10.000) = 305 
    [10.000, 11.250) = 130 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.519 ms/op
     p(99.9900) =     12.372 ms/op
     p(99.9990) =     14.156 ms/op
     p(99.9999) =     15.073 ms/op
    p(100.0000) =     15.073 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.911 ± 2.663  ops/ms
ClientPb.existUser                       thrpt       3  13.367 ± 1.147  ops/ms
ClientPb.getUser                         thrpt       3  13.114 ± 0.611  ops/ms
ClientPb.listUser                        thrpt       3  10.709 ± 1.139  ops/ms
ClientPb.createUser                       avgt       3   2.479 ± 0.287   ms/op
ClientPb.existUser                        avgt       3   2.392 ± 0.260   ms/op
ClientPb.getUser                          avgt       3   2.452 ± 0.199   ms/op
ClientPb.listUser                         avgt       3   2.960 ± 0.018   ms/op
ClientPb.createUser                     sample  389891   2.460 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.914           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.535           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.990           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.633           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.227           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.845           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.647           ms/op
ClientPb.existUser                      sample  391458   2.450 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.799           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.759           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.791           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.976           ms/op
ClientPb.getUser                        sample  391284   2.452 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.824           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.478           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.974           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.965           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.215           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.258           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.695           ms/op
ClientPb.listUser                       sample  322695   2.973 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.815           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.519           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.372           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.073           ms/op
```
