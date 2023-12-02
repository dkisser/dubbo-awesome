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
[INFO] benchmark-base ..................................... SUCCESS [  2.826 s]
[INFO] server-base ........................................ SUCCESS [  0.290 s]
[INFO] client-base ........................................ SUCCESS [  0.620 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.512 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  4.555 s
[INFO] Finished at: 2023-12-02T12:09:57Z
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
# Warmup Iteration   1: 4.953 ops/ms
# Warmup Iteration   2: 12.093 ops/ms
# Warmup Iteration   3: 12.381 ops/ms
Iteration   1: 12.454 ops/ms
Iteration   2: 12.731 ops/ms
Iteration   3: 12.867 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.684 ±(99.9%) 3.847 ops/ms [Average]
  (min, avg, max) = (12.454, 12.684, 12.867), stdev = 0.211
  CI (99.9%): [8.837, 16.531] (assumes normal distribution)


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
# Warmup Iteration   1: 8.298 ops/ms
# Warmup Iteration   2: 13.034 ops/ms
# Warmup Iteration   3: 12.974 ops/ms
Iteration   1: 12.921 ops/ms
Iteration   2: 12.908 ops/ms
Iteration   3: 12.936 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.922 ±(99.9%) 0.254 ops/ms [Average]
  (min, avg, max) = (12.908, 12.922, 12.936), stdev = 0.014
  CI (99.9%): [12.668, 13.176] (assumes normal distribution)


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
# Warmup Iteration   1: 7.944 ops/ms
# Warmup Iteration   2: 12.603 ops/ms
# Warmup Iteration   3: 12.796 ops/ms
Iteration   1: 12.907 ops/ms
Iteration   2: 12.883 ops/ms
Iteration   3: 12.977 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.922 ±(99.9%) 0.898 ops/ms [Average]
  (min, avg, max) = (12.883, 12.922, 12.977), stdev = 0.049
  CI (99.9%): [12.024, 13.821] (assumes normal distribution)


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
# Warmup Iteration   1: 6.746 ops/ms
# Warmup Iteration   2: 10.454 ops/ms
# Warmup Iteration   3: 10.453 ops/ms
Iteration   1: 10.599 ops/ms
Iteration   2: 10.642 ops/ms
Iteration   3: 10.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.614 ±(99.9%) 0.433 ops/ms [Average]
  (min, avg, max) = (10.599, 10.614, 10.642), stdev = 0.024
  CI (99.9%): [10.181, 11.047] (assumes normal distribution)


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
# Warmup Iteration   1: 3.881 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.590 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.004 ms/op
Iteration   1: 2.577 ±(99.9%) 0.004 ms/op
Iteration   2: 2.528 ±(99.9%) 0.005 ms/op
Iteration   3: 2.504 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.536 ±(99.9%) 0.678 ms/op [Average]
  (min, avg, max) = (2.504, 2.536, 2.577), stdev = 0.037
  CI (99.9%): [1.858, 3.215] (assumes normal distribution)


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
# Warmup Iteration   1: 3.604 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.003 ms/op
Iteration   1: 2.490 ±(99.9%) 0.003 ms/op
Iteration   2: 2.484 ±(99.9%) 0.004 ms/op
Iteration   3: 2.461 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.478 ±(99.9%) 0.285 ms/op [Average]
  (min, avg, max) = (2.461, 2.478, 2.490), stdev = 0.016
  CI (99.9%): [2.193, 2.764] (assumes normal distribution)


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
# Warmup Iteration   1: 3.792 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.505 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.003 ms/op
Iteration   1: 2.499 ±(99.9%) 0.003 ms/op
Iteration   2: 2.465 ±(99.9%) 0.004 ms/op
Iteration   3: 2.496 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.487 ±(99.9%) 0.346 ms/op [Average]
  (min, avg, max) = (2.465, 2.487, 2.499), stdev = 0.019
  CI (99.9%): [2.141, 2.833] (assumes normal distribution)


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
# Warmup Iteration   1: 4.636 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.005 ms/op
Iteration   1: 3.015 ±(99.9%) 0.005 ms/op
Iteration   2: 3.025 ±(99.9%) 0.006 ms/op
Iteration   3: 3.006 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.015 ±(99.9%) 0.177 ms/op [Average]
  (min, avg, max) = (3.006, 3.015, 3.025), stdev = 0.010
  CI (99.9%): [2.838, 3.192] (assumes normal distribution)


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
# Warmup Iteration   1: 4.104 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.642 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
Iteration   1: 2.498 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.947 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.641 ms/op
                 createUser·p0.999:  11.119 ms/op
                 createUser·p0.9999: 13.238 ms/op
                 createUser·p1.00:   13.517 ms/op

Iteration   2: 2.504 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.912 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.731 ms/op
                 createUser·p0.999:  8.552 ms/op
                 createUser·p0.9999: 11.575 ms/op
                 createUser·p1.00:   12.730 ms/op

Iteration   3: 2.540 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.073 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  8.507 ms/op
                 createUser·p0.9999: 10.827 ms/op
                 createUser·p1.00:   11.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381547
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 25 
    [ 1.250,  2.500) = 184070 
    [ 2.500,  3.750) = 192798 
    [ 3.750,  5.000) = 3570 
    [ 5.000,  6.250) = 650 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 115 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.879 ms/op
     p(99.9000) =      8.511 ms/op
     p(99.9900) =     12.630 ms/op
     p(99.9990) =     13.389 ms/op
     p(99.9999) =     13.517 ms/op
    p(100.0000) =     13.517 ms/op


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
# Warmup Iteration   1: 3.777 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.441 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.432 ±(99.9%) 0.005 ms/op
Iteration   1: 2.433 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.980 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  6.215 ms/op
                 existUser·p0.9999: 13.842 ms/op
                 existUser·p1.00:   14.762 ms/op

Iteration   2: 2.440 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.989 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.485 ms/op
                 existUser·p0.999:  6.332 ms/op
                 existUser·p0.9999: 12.993 ms/op
                 existUser·p1.00:   14.041 ms/op

Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.920 ms/op
                 existUser·p0.999:  8.386 ms/op
                 existUser·p0.9999: 12.567 ms/op
                 existUser·p1.00:   13.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392127
  mean =      2.445 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 31 
    [ 1.250,  2.500) = 192478 
    [ 2.500,  3.750) = 196471 
    [ 3.750,  5.000) = 2350 
    [ 5.000,  6.250) = 350 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 114 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 109 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      2.961 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.621 ms/op
     p(99.9000) =      7.525 ms/op
     p(99.9900) =     13.551 ms/op
     p(99.9990) =     14.490 ms/op
     p(99.9999) =     14.762 ms/op
    p(100.0000) =     14.762 ms/op


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
# Warmup Iteration   1: 4.110 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.592 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.521 ±(99.9%) 0.006 ms/op
Iteration   1: 2.513 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.775 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.916 ms/op
                 getUser·p0.999:  11.158 ms/op
                 getUser·p0.9999: 14.056 ms/op
                 getUser·p1.00:   15.057 ms/op

Iteration   2: 2.516 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.966 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  9.650 ms/op
                 getUser·p0.9999: 12.506 ms/op
                 getUser·p1.00:   12.911 ms/op

Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.996 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.764 ms/op
                 getUser·p0.999:  7.978 ms/op
                 getUser·p0.9999: 11.536 ms/op
                 getUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382998
  mean =      2.504 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 188972 
    [ 2.500,  3.750) = 188405 
    [ 3.750,  5.000) = 4313 
    [ 5.000,  6.250) = 771 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 90 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      4.039 ms/op
     p(99.9000) =      9.060 ms/op
     p(99.9900) =     13.507 ms/op
     p(99.9990) =     14.708 ms/op
     p(99.9999) =     15.057 ms/op
    p(100.0000) =     15.057 ms/op


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
# Warmup Iteration   1: 4.634 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.009 ms/op
Iteration   1: 3.027 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.904 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.165 ms/op
                 listUser·p0.9999: 10.886 ms/op
                 listUser·p1.00:   11.158 ms/op

Iteration   2: 3.036 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.786 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  10.104 ms/op
                 listUser·p0.9999: 11.517 ms/op
                 listUser·p1.00:   12.616 ms/op

Iteration   3: 3.027 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.854 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  8.952 ms/op
                 listUser·p0.9999: 10.584 ms/op
                 listUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316553
  mean =      3.030 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 164 
    [ 1.250,  2.500) = 91201 
    [ 2.500,  3.750) = 183989 
    [ 3.750,  5.000) = 33432 
    [ 5.000,  6.250) = 6159 
    [ 6.250,  7.500) = 989 
    [ 7.500,  8.750) = 168 
    [ 8.750, 10.000) = 250 
    [10.000, 11.250) = 185 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =      9.552 ms/op
     p(99.9900) =     11.043 ms/op
     p(99.9990) =     11.955 ms/op
     p(99.9999) =     12.616 ms/op
    p(100.0000) =     12.616 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.684 ± 3.847  ops/ms
ClientPb.existUser                       thrpt       3  12.922 ± 0.254  ops/ms
ClientPb.getUser                         thrpt       3  12.922 ± 0.898  ops/ms
ClientPb.listUser                        thrpt       3  10.614 ± 0.433  ops/ms
ClientPb.createUser                       avgt       3   2.536 ± 0.678   ms/op
ClientPb.existUser                        avgt       3   2.478 ± 0.285   ms/op
ClientPb.getUser                          avgt       3   2.487 ± 0.346   ms/op
ClientPb.listUser                         avgt       3   3.015 ± 0.177   ms/op
ClientPb.createUser                     sample  381547   2.514 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.912           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.879           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.511           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.630           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.517           ms/op
ClientPb.existUser                      sample  392127   2.445 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.904           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.961           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.525           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.551           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.762           ms/op
ClientPb.getUser                        sample  382998   2.504 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.775           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.039           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.060           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.507           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.057           ms/op
ClientPb.listUser                       sample  316553   3.030 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.786           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.936           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.718           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.552           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.043           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.616           ms/op
```
