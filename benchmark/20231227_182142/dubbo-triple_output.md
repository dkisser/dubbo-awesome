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
[INFO] benchmark-base ..................................... SUCCESS [  2.953 s]
[INFO] server-base ........................................ SUCCESS [  0.328 s]
[INFO] client-base ........................................ SUCCESS [  0.550 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.476 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  4.606 s
[INFO] Finished at: 2023-12-27T18:08:01Z
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
# Warmup Iteration   1: 4.823 ops/ms
# Warmup Iteration   2: 11.990 ops/ms
# Warmup Iteration   3: 12.470 ops/ms
Iteration   1: 12.776 ops/ms
Iteration   2: 12.569 ops/ms
Iteration   3: 12.586 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.644 ±(99.9%) 2.100 ops/ms [Average]
  (min, avg, max) = (12.569, 12.644, 12.776), stdev = 0.115
  CI (99.9%): [10.544, 14.743] (assumes normal distribution)


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
# Warmup Iteration   1: 8.601 ops/ms
# Warmup Iteration   2: 13.112 ops/ms
# Warmup Iteration   3: 13.076 ops/ms
Iteration   1: 13.044 ops/ms
Iteration   2: 12.879 ops/ms
Iteration   3: 13.014 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.979 ±(99.9%) 1.602 ops/ms [Average]
  (min, avg, max) = (12.879, 12.979, 13.044), stdev = 0.088
  CI (99.9%): [11.376, 14.581] (assumes normal distribution)


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
# Warmup Iteration   1: 7.843 ops/ms
# Warmup Iteration   2: 12.321 ops/ms
# Warmup Iteration   3: 12.806 ops/ms
Iteration   1: 12.691 ops/ms
Iteration   2: 12.660 ops/ms
Iteration   3: 12.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.696 ±(99.9%) 0.713 ops/ms [Average]
  (min, avg, max) = (12.660, 12.696, 12.737), stdev = 0.039
  CI (99.9%): [11.983, 13.409] (assumes normal distribution)


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
# Warmup Iteration   1: 6.400 ops/ms
# Warmup Iteration   2: 10.596 ops/ms
# Warmup Iteration   3: 10.749 ops/ms
Iteration   1: 10.738 ops/ms
Iteration   2: 10.778 ops/ms
Iteration   3: 10.822 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.779 ±(99.9%) 0.769 ops/ms [Average]
  (min, avg, max) = (10.738, 10.779, 10.822), stdev = 0.042
  CI (99.9%): [10.011, 11.548] (assumes normal distribution)


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
# Warmup Iteration   1: 3.944 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.620 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.004 ms/op
Iteration   1: 2.553 ±(99.9%) 0.004 ms/op
Iteration   2: 2.508 ±(99.9%) 0.004 ms/op
Iteration   3: 2.533 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.531 ±(99.9%) 0.410 ms/op [Average]
  (min, avg, max) = (2.508, 2.531, 2.553), stdev = 0.022
  CI (99.9%): [2.121, 2.941] (assumes normal distribution)


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
# Warmup Iteration   1: 3.686 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.461 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
Iteration   1: 2.440 ±(99.9%) 0.003 ms/op
Iteration   2: 2.434 ±(99.9%) 0.004 ms/op
Iteration   3: 2.444 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.439 ±(99.9%) 0.092 ms/op [Average]
  (min, avg, max) = (2.434, 2.439, 2.444), stdev = 0.005
  CI (99.9%): [2.347, 2.531] (assumes normal distribution)


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
# Warmup Iteration   1: 3.724 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.004 ms/op
Iteration   1: 2.463 ±(99.9%) 0.004 ms/op
Iteration   2: 2.473 ±(99.9%) 0.004 ms/op
Iteration   3: 2.448 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.461 ±(99.9%) 0.233 ms/op [Average]
  (min, avg, max) = (2.448, 2.461, 2.473), stdev = 0.013
  CI (99.9%): [2.228, 2.694] (assumes normal distribution)


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
# Warmup Iteration   1: 4.626 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.005 ms/op
Iteration   1: 2.991 ±(99.9%) 0.005 ms/op
Iteration   2: 2.993 ±(99.9%) 0.005 ms/op
Iteration   3: 2.982 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.989 ±(99.9%) 0.105 ms/op [Average]
  (min, avg, max) = (2.982, 2.989, 2.993), stdev = 0.006
  CI (99.9%): [2.884, 3.093] (assumes normal distribution)


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
# Warmup Iteration   1: 4.406 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.711 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.584 ±(99.9%) 0.006 ms/op
Iteration   1: 2.610 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.606 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.170 ms/op
                 createUser·p0.95:   3.322 ms/op
                 createUser·p0.99:   4.330 ms/op
                 createUser·p0.999:  11.460 ms/op
                 createUser·p0.9999: 13.513 ms/op
                 createUser·p1.00:   13.795 ms/op

Iteration   2: 2.565 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.918 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.756 ms/op
                 createUser·p0.999:  9.269 ms/op
                 createUser·p0.9999: 12.347 ms/op
                 createUser·p1.00:   12.780 ms/op

Iteration   3: 2.614 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.985 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.187 ms/op
                 createUser·p0.95:   3.322 ms/op
                 createUser·p0.99:   4.104 ms/op
                 createUser·p0.999:  9.748 ms/op
                 createUser·p0.9999: 15.696 ms/op
                 createUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 369452
  mean =      2.596 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 173974 
    [ 2.500,  3.750) = 189573 
    [ 3.750,  5.000) = 4535 
    [ 5.000,  6.250) = 686 
    [ 6.250,  7.500) = 140 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 145 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      2.642 ms/op
     p(90.0000) =      3.154 ms/op
     p(95.0000) =      3.289 ms/op
     p(99.0000) =      4.043 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     14.598 ms/op
     p(99.9990) =     16.787 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


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
# Warmup Iteration   1: 3.770 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.458 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.005 ms/op
Iteration   1: 2.457 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.944 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.535 ms/op
                 existUser·p0.999:  6.287 ms/op
                 existUser·p0.9999: 13.959 ms/op
                 existUser·p1.00:   15.073 ms/op

Iteration   2: 2.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.953 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.494 ms/op
                 existUser·p0.999:  6.761 ms/op
                 existUser·p0.9999: 11.874 ms/op
                 existUser·p1.00:   12.714 ms/op

Iteration   3: 2.459 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.859 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   4.100 ms/op
                 existUser·p0.999:  5.932 ms/op
                 existUser·p0.9999: 12.108 ms/op
                 existUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390977
  mean =      2.452 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 196110 
    [ 2.500,  3.750) = 191233 
    [ 3.750,  5.000) = 2620 
    [ 5.000,  6.250) = 564 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 109 
    [11.250, 12.500) = 119 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.690 ms/op
     p(99.9000) =      6.357 ms/op
     p(99.9900) =     12.665 ms/op
     p(99.9990) =     14.716 ms/op
     p(99.9999) =     15.073 ms/op
    p(100.0000) =     15.073 ms/op


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
# Warmup Iteration   1: 3.922 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.521 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
Iteration   1: 2.479 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.933 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.699 ms/op
                 getUser·p0.999:  7.816 ms/op
                 getUser·p0.9999: 13.322 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.629 ms/op
                 getUser·p0.999:  6.538 ms/op
                 getUser·p0.9999: 11.764 ms/op
                 getUser·p1.00:   12.698 ms/op

Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.114 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   4.170 ms/op
                 getUser·p0.999:  8.445 ms/op
                 getUser·p0.9999: 10.634 ms/op
                 getUser·p1.00:   11.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388382
  mean =      2.470 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 194849 
    [ 2.500,  3.750) = 189306 
    [ 3.750,  5.000) = 3257 
    [ 5.000,  6.250) = 460 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.793 ms/op
     p(99.9000) =      7.733 ms/op
     p(99.9900) =     12.878 ms/op
     p(99.9990) =     14.022 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


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
# Warmup Iteration   1: 4.690 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.008 ms/op
Iteration   1: 3.007 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.901 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 11.935 ms/op
                 listUser·p1.00:   13.517 ms/op

Iteration   2: 3.004 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.898 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  10.125 ms/op
                 listUser·p0.9999: 11.223 ms/op
                 listUser·p1.00:   12.812 ms/op

Iteration   3: 3.019 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.801 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.948 ms/op
                 listUser·p0.9999: 13.432 ms/op
                 listUser·p1.00:   14.778 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318611
  mean =      3.010 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 118 
    [ 1.250,  2.500) = 92021 
    [ 2.500,  3.750) = 187678 
    [ 3.750,  5.000) = 32017 
    [ 5.000,  6.250) = 5585 
    [ 6.250,  7.500) = 510 
    [ 7.500,  8.750) = 136 
    [ 8.750, 10.000) = 273 
    [10.000, 11.250) = 177 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.601 ms/op
     p(99.9900) =     12.435 ms/op
     p(99.9990) =     14.342 ms/op
     p(99.9999) =     14.778 ms/op
    p(100.0000) =     14.778 ms/op


# Run complete. Total time: 00:12:56

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.644 ± 2.100  ops/ms
ClientPb.existUser                       thrpt       3  12.979 ± 1.602  ops/ms
ClientPb.getUser                         thrpt       3  12.696 ± 0.713  ops/ms
ClientPb.listUser                        thrpt       3  10.779 ± 0.769  ops/ms
ClientPb.createUser                       avgt       3   2.531 ± 0.410   ms/op
ClientPb.existUser                        avgt       3   2.439 ± 0.092   ms/op
ClientPb.getUser                          avgt       3   2.461 ± 0.233   ms/op
ClientPb.listUser                         avgt       3   2.989 ± 0.105   ms/op
ClientPb.createUser                     sample  369452   2.596 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.606           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.642           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.289           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.043           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.568           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.598           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.810           ms/op
ClientPb.existUser                      sample  390977   2.452 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.859           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.494           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.357           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.665           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.073           ms/op
ClientPb.getUser                        sample  388382   2.470 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.933           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.490           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.015           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.733           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.878           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.270           ms/op
ClientPb.listUser                       sample  318611   3.010 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.801           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.601           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.435           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.778           ms/op
```
