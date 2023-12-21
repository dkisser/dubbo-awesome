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
[INFO] benchmark-base ..................................... SUCCESS [  2.971 s]
[INFO] server-base ........................................ SUCCESS [  0.303 s]
[INFO] client-base ........................................ SUCCESS [  0.652 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.501 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  4.756 s
[INFO] Finished at: 2023-12-21T12:11:04Z
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
# Warmup Iteration   1: 4.645 ops/ms
# Warmup Iteration   2: 11.747 ops/ms
# Warmup Iteration   3: 12.195 ops/ms
Iteration   1: 12.380 ops/ms
Iteration   2: 12.594 ops/ms
Iteration   3: 12.644 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.539 ±(99.9%) 2.564 ops/ms [Average]
  (min, avg, max) = (12.380, 12.539, 12.644), stdev = 0.141
  CI (99.9%): [9.976, 15.103] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.823 ops/ms
# Warmup Iteration   2: 12.766 ops/ms
# Warmup Iteration   3: 12.770 ops/ms
Iteration   1: 12.715 ops/ms
Iteration   2: 12.684 ops/ms
Iteration   3: 12.909 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.769 ±(99.9%) 2.228 ops/ms [Average]
  (min, avg, max) = (12.684, 12.769, 12.909), stdev = 0.122
  CI (99.9%): [10.542, 14.997] (assumes normal distribution)


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
# Warmup Iteration   1: 6.279 ops/ms
# Warmup Iteration   2: 12.225 ops/ms
# Warmup Iteration   3: 12.448 ops/ms
Iteration   1: 12.566 ops/ms
Iteration   2: 12.709 ops/ms
Iteration   3: 12.606 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.627 ±(99.9%) 1.344 ops/ms [Average]
  (min, avg, max) = (12.566, 12.627, 12.709), stdev = 0.074
  CI (99.9%): [11.283, 13.971] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.855 ops/ms
# Warmup Iteration   2: 10.350 ops/ms
# Warmup Iteration   3: 10.560 ops/ms
Iteration   1: 10.454 ops/ms
Iteration   2: 10.490 ops/ms
Iteration   3: 10.467 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.470 ±(99.9%) 0.340 ops/ms [Average]
  (min, avg, max) = (10.454, 10.470, 10.490), stdev = 0.019
  CI (99.9%): [10.131, 10.810] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 3.982 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.650 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.582 ±(99.9%) 0.004 ms/op
Iteration   1: 2.546 ±(99.9%) 0.004 ms/op
Iteration   2: 2.612 ±(99.9%) 0.004 ms/op
Iteration   3: 2.566 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.575 ±(99.9%) 0.612 ms/op [Average]
  (min, avg, max) = (2.546, 2.575, 2.612), stdev = 0.034
  CI (99.9%): [1.962, 3.187] (assumes normal distribution)


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
# Warmup Iteration   1: 3.865 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.498 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.004 ms/op
Iteration   1: 2.441 ±(99.9%) 0.004 ms/op
Iteration   2: 2.440 ±(99.9%) 0.004 ms/op
Iteration   3: 2.469 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.450 ±(99.9%) 0.303 ms/op [Average]
  (min, avg, max) = (2.440, 2.450, 2.469), stdev = 0.017
  CI (99.9%): [2.147, 2.753] (assumes normal distribution)


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
# Warmup Iteration   1: 3.929 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.004 ms/op
Iteration   1: 2.502 ±(99.9%) 0.004 ms/op
Iteration   2: 2.493 ±(99.9%) 0.004 ms/op
Iteration   3: 2.507 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.501 ±(99.9%) 0.131 ms/op [Average]
  (min, avg, max) = (2.493, 2.501, 2.507), stdev = 0.007
  CI (99.9%): [2.369, 2.632] (assumes normal distribution)


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
# Warmup Iteration   1: 4.679 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.006 ms/op
Iteration   1: 2.985 ±(99.9%) 0.005 ms/op
Iteration   2: 2.971 ±(99.9%) 0.005 ms/op
Iteration   3: 3.000 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.985 ±(99.9%) 0.263 ms/op [Average]
  (min, avg, max) = (2.971, 2.985, 3.000), stdev = 0.014
  CI (99.9%): [2.723, 3.248] (assumes normal distribution)


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
# Warmup Iteration   1: 4.060 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.660 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.005 ms/op
Iteration   1: 2.544 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.040 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.764 ms/op
                 createUser·p0.999:  11.190 ms/op
                 createUser·p0.9999: 13.589 ms/op
                 createUser·p1.00:   14.270 ms/op

Iteration   2: 2.546 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.989 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.871 ms/op
                 createUser·p0.999:  9.107 ms/op
                 createUser·p0.9999: 12.517 ms/op
                 createUser·p1.00:   13.468 ms/op

Iteration   3: 2.531 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.987 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.940 ms/op
                 createUser·p0.999:  8.159 ms/op
                 createUser·p0.9999: 10.732 ms/op
                 createUser·p1.00:   10.912 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377561
  mean =      2.540 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 180733 
    [ 2.500,  3.750) = 192281 
    [ 3.750,  5.000) = 3572 
    [ 5.000,  6.250) = 506 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 127 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.987 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.858 ms/op
     p(99.9000) =      8.583 ms/op
     p(99.9900) =     13.164 ms/op
     p(99.9990) =     13.978 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.629 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.468 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.005 ms/op
Iteration   1: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.932 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.789 ms/op
                 existUser·p0.999:  6.510 ms/op
                 existUser·p0.9999: 14.222 ms/op
                 existUser·p1.00:   14.533 ms/op

Iteration   2: 2.468 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.012 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.487 ms/op
                 existUser·p0.999:  8.808 ms/op
                 existUser·p0.9999: 15.041 ms/op
                 existUser·p1.00:   15.876 ms/op

Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.947 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  6.039 ms/op
                 existUser·p0.9999: 12.468 ms/op
                 existUser·p1.00:   12.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389352
  mean =      2.463 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 194897 
    [ 2.500,  3.750) = 191177 
    [ 3.750,  5.000) = 2356 
    [ 5.000,  6.250) = 458 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 123 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.633 ms/op
     p(99.9000) =      8.373 ms/op
     p(99.9900) =     14.191 ms/op
     p(99.9990) =     15.827 ms/op
     p(99.9999) =     15.876 ms/op
    p(100.0000) =     15.876 ms/op


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
# Warmup Iteration   1: 3.830 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.578 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.576 ±(99.9%) 0.006 ms/op
Iteration   1: 2.510 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.008 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.674 ms/op
                 getUser·p0.999:  12.007 ms/op
                 getUser·p0.9999: 15.876 ms/op
                 getUser·p1.00:   17.072 ms/op

Iteration   2: 2.525 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.918 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   3.928 ms/op
                 getUser·p0.999:  9.388 ms/op
                 getUser·p0.9999: 13.970 ms/op
                 getUser·p1.00:   14.451 ms/op

Iteration   3: 2.553 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.981 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.256 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  8.385 ms/op
                 getUser·p0.9999: 10.519 ms/op
                 getUser·p1.00:   11.502 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379230
  mean =      2.529 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 185759 
    [ 2.500,  3.750) = 188457 
    [ 3.750,  5.000) = 3938 
    [ 5.000,  6.250) = 611 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 103 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.918 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.912 ms/op
     p(99.9000) =      8.405 ms/op
     p(99.9900) =     14.357 ms/op
     p(99.9990) =     16.798 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


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
# Warmup Iteration   1: 4.670 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.008 ms/op
Iteration   1: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.922 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.403 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 14.553 ms/op
                 listUser·p1.00:   16.040 ms/op

Iteration   2: 2.974 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.934 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.801 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   5.333 ms/op
                 listUser·p0.999:  9.996 ms/op
                 listUser·p0.9999: 11.342 ms/op
                 listUser·p1.00:   12.009 ms/op

Iteration   3: 3.014 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.901 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.912 ms/op
                 listUser·p0.9999: 11.006 ms/op
                 listUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319839
  mean =      2.999 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 145 
    [ 1.250,  2.500) = 92296 
    [ 2.500,  3.750) = 189368 
    [ 3.750,  5.000) = 31251 
    [ 5.000,  6.250) = 5528 
    [ 6.250,  7.500) = 553 
    [ 7.500,  8.750) = 160 
    [ 8.750, 10.000) = 264 
    [10.000, 11.250) = 197 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.901 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.667 ms/op
     p(99.9900) =     12.403 ms/op
     p(99.9990) =     15.722 ms/op
     p(99.9999) =     16.040 ms/op
    p(100.0000) =     16.040 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.539 ± 2.564  ops/ms
ClientPb.existUser                       thrpt       3  12.769 ± 2.228  ops/ms
ClientPb.getUser                         thrpt       3  12.627 ± 1.344  ops/ms
ClientPb.listUser                        thrpt       3  10.470 ± 0.340  ops/ms
ClientPb.createUser                       avgt       3   2.575 ± 0.612   ms/op
ClientPb.existUser                        avgt       3   2.450 ± 0.303   ms/op
ClientPb.getUser                          avgt       3   2.501 ± 0.131   ms/op
ClientPb.listUser                         avgt       3   2.985 ± 0.263   ms/op
ClientPb.createUser                     sample  377561   2.540 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.987           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.858           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.583           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.164           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.270           ms/op
ClientPb.existUser                      sample  389352   2.463 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.932           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.499           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.373           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.191           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.876           ms/op
ClientPb.getUser                        sample  379230   2.529 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.918           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.405           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.357           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.072           ms/op
ClientPb.listUser                       sample  319839   2.999 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.901           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.667           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.403           ms/op
ClientPb.listUser:listUser·p1.00        sample          16.040           ms/op
```
