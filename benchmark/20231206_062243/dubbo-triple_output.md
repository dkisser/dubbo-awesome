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
[INFO] benchmark-base ..................................... SUCCESS [  2.920 s]
[INFO] server-base ........................................ SUCCESS [  0.297 s]
[INFO] client-base ........................................ SUCCESS [  0.649 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.513 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  4.688 s
[INFO] Finished at: 2023-12-06T06:09:19Z
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
# Warmup Iteration   1: 4.829 ops/ms
# Warmup Iteration   2: 12.163 ops/ms
# Warmup Iteration   3: 12.282 ops/ms
Iteration   1: 12.534 ops/ms
Iteration   2: 12.627 ops/ms
Iteration   3: 12.642 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.601 ±(99.9%) 1.064 ops/ms [Average]
  (min, avg, max) = (12.534, 12.601, 12.642), stdev = 0.058
  CI (99.9%): [11.537, 13.664] (assumes normal distribution)


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
# Warmup Iteration   1: 7.950 ops/ms
# Warmup Iteration   2: 12.854 ops/ms
# Warmup Iteration   3: 12.882 ops/ms
Iteration   1: 12.981 ops/ms
Iteration   2: 12.885 ops/ms
Iteration   3: 12.847 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.904 ±(99.9%) 1.268 ops/ms [Average]
  (min, avg, max) = (12.847, 12.904, 12.981), stdev = 0.070
  CI (99.9%): [11.636, 14.173] (assumes normal distribution)


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
# Warmup Iteration   1: 7.664 ops/ms
# Warmup Iteration   2: 12.635 ops/ms
# Warmup Iteration   3: 12.869 ops/ms
Iteration   1: 12.707 ops/ms
Iteration   2: 12.967 ops/ms
Iteration   3: 12.950 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.874 ±(99.9%) 2.647 ops/ms [Average]
  (min, avg, max) = (12.707, 12.874, 12.967), stdev = 0.145
  CI (99.9%): [10.227, 15.522] (assumes normal distribution)


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
# Warmup Iteration   1: 6.677 ops/ms
# Warmup Iteration   2: 10.254 ops/ms
# Warmup Iteration   3: 10.523 ops/ms
Iteration   1: 10.442 ops/ms
Iteration   2: 10.412 ops/ms
Iteration   3: 10.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.439 ±(99.9%) 0.481 ops/ms [Average]
  (min, avg, max) = (10.412, 10.439, 10.465), stdev = 0.026
  CI (99.9%): [9.958, 10.920] (assumes normal distribution)


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
# Warmup Iteration   1: 4.156 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.590 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.005 ms/op
Iteration   1: 2.519 ±(99.9%) 0.004 ms/op
Iteration   2: 2.512 ±(99.9%) 0.004 ms/op
Iteration   3: 2.526 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.519 ±(99.9%) 0.126 ms/op [Average]
  (min, avg, max) = (2.512, 2.519, 2.526), stdev = 0.007
  CI (99.9%): [2.393, 2.645] (assumes normal distribution)


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
# Warmup Iteration   1: 3.717 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.493 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.004 ms/op
Iteration   1: 2.443 ±(99.9%) 0.005 ms/op
Iteration   2: 2.443 ±(99.9%) 0.004 ms/op
Iteration   3: 2.447 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.444 ±(99.9%) 0.043 ms/op [Average]
  (min, avg, max) = (2.443, 2.444, 2.447), stdev = 0.002
  CI (99.9%): [2.401, 2.488] (assumes normal distribution)


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
# Warmup Iteration   1: 3.955 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.547 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.005 ms/op
Iteration   1: 2.472 ±(99.9%) 0.005 ms/op
Iteration   2: 2.420 ±(99.9%) 0.008 ms/op
Iteration   3: 2.415 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.436 ±(99.9%) 0.572 ms/op [Average]
  (min, avg, max) = (2.415, 2.436, 2.472), stdev = 0.031
  CI (99.9%): [1.863, 3.008] (assumes normal distribution)


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
# Warmup Iteration   1: 4.564 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 2.996 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.954 ±(99.9%) 0.007 ms/op
Iteration   1: 2.949 ±(99.9%) 0.005 ms/op
Iteration   2: 3.000 ±(99.9%) 0.006 ms/op
Iteration   3: 3.023 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.991 ±(99.9%) 0.693 ms/op [Average]
  (min, avg, max) = (2.949, 2.991, 3.023), stdev = 0.038
  CI (99.9%): [2.298, 3.684] (assumes normal distribution)


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
# Warmup Iteration   1: 4.579 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.655 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.006 ms/op
Iteration   1: 2.533 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.703 ms/op
                 createUser·p0.999:  10.859 ms/op
                 createUser·p0.9999: 14.467 ms/op
                 createUser·p1.00:   15.204 ms/op

Iteration   2: 2.548 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.826 ms/op
                 createUser·p0.999:  9.790 ms/op
                 createUser·p0.9999: 12.508 ms/op
                 createUser·p1.00:   12.812 ms/op

Iteration   3: 2.586 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.842 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.162 ms/op
                 createUser·p0.95:   3.326 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  7.984 ms/op
                 createUser·p0.9999: 10.773 ms/op
                 createUser·p1.00:   11.256 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375250
  mean =      2.556 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 179184 
    [ 2.500,  3.750) = 190861 
    [ 3.750,  5.000) = 4178 
    [ 5.000,  6.250) = 438 
    [ 6.250,  7.500) = 133 
    [ 7.500,  8.750) = 60 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 124 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.248 ms/op
     p(99.0000) =      3.951 ms/op
     p(99.9000) =      8.141 ms/op
     p(99.9900) =     12.976 ms/op
     p(99.9990) =     14.815 ms/op
     p(99.9999) =     15.204 ms/op
    p(100.0000) =     15.204 ms/op


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
# Warmup Iteration   1: 3.773 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.461 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
Iteration   1: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.996 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.727 ms/op
                 existUser·p0.999:  6.696 ms/op
                 existUser·p0.9999: 14.140 ms/op
                 existUser·p1.00:   14.418 ms/op

Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.906 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.666 ms/op
                 existUser·p0.999:  6.864 ms/op
                 existUser·p0.9999: 12.944 ms/op
                 existUser·p1.00:   14.041 ms/op

Iteration   3: 2.491 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.702 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.293 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  10.469 ms/op
                 existUser·p0.9999: 16.633 ms/op
                 existUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388165
  mean =      2.471 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 193392 
    [ 2.500,  3.750) = 189093 
    [ 3.750,  5.000) = 4202 
    [ 5.000,  6.250) = 857 
    [ 6.250,  7.500) = 80 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 135 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      4.043 ms/op
     p(99.9000) =     10.024 ms/op
     p(99.9900) =     14.352 ms/op
     p(99.9990) =     16.789 ms/op
     p(99.9999) =     17.105 ms/op
    p(100.0000) =     17.105 ms/op


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
# Warmup Iteration   1: 3.968 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.550 ±(99.9%) 0.006 ms/op
Iteration   1: 2.543 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.744 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.125 ms/op
                 getUser·p0.95:   3.314 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  11.653 ms/op
                 getUser·p0.9999: 14.518 ms/op
                 getUser·p1.00:   15.139 ms/op

Iteration   2: 2.528 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.626 ms/op
                 getUser·p0.50:   2.437 ms/op
                 getUser·p0.90:   3.178 ms/op
                 getUser·p0.95:   3.482 ms/op
                 getUser·p0.99:   4.576 ms/op
                 getUser·p0.999:  9.794 ms/op
                 getUser·p0.9999: 13.332 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.929 ms/op
                 getUser·p0.50:   2.417 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.293 ms/op
                 getUser·p0.99:   4.107 ms/op
                 getUser·p0.999:  9.066 ms/op
                 getUser·p0.9999: 11.102 ms/op
                 getUser·p1.00:   11.928 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380200
  mean =      2.523 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 135 
    [ 1.250,  2.500) = 198521 
    [ 2.500,  3.750) = 172562 
    [ 3.750,  5.000) = 7683 
    [ 5.000,  6.250) = 793 
    [ 6.250,  7.500) = 103 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.626 ms/op
     p(50.0000) =      2.441 ms/op
     p(90.0000) =      3.133 ms/op
     p(95.0000) =      3.359 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      9.205 ms/op
     p(99.9900) =     13.549 ms/op
     p(99.9990) =     14.962 ms/op
     p(99.9999) =     15.139 ms/op
    p(100.0000) =     15.139 ms/op


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
# Warmup Iteration   1: 4.812 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.009 ms/op
Iteration   1: 2.985 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.937 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.431 ms/op
                 listUser·p0.999:  8.995 ms/op
                 listUser·p0.9999: 10.966 ms/op
                 listUser·p1.00:   11.158 ms/op

Iteration   2: 2.983 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.983 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.390 ms/op
                 listUser·p0.999:  9.762 ms/op
                 listUser·p0.9999: 12.199 ms/op
                 listUser·p1.00:   12.354 ms/op

Iteration   3: 2.999 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.780 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.886 ms/op
                 listUser·p0.9999: 11.917 ms/op
                 listUser·p1.00:   12.599 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320911
  mean =      2.989 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 252 
    [ 1.250,  2.500) = 95756 
    [ 2.500,  3.750) = 183293 
    [ 3.750,  5.000) = 35372 
    [ 5.000,  6.250) = 5069 
    [ 6.250,  7.500) = 484 
    [ 7.500,  8.750) = 209 
    [ 8.750, 10.000) = 234 
    [10.000, 11.250) = 186 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.780 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =      9.424 ms/op
     p(99.9900) =     11.843 ms/op
     p(99.9990) =     12.350 ms/op
     p(99.9999) =     12.599 ms/op
    p(100.0000) =     12.599 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.601 ± 1.064  ops/ms
ClientPb.existUser                       thrpt       3  12.904 ± 1.268  ops/ms
ClientPb.getUser                         thrpt       3  12.874 ± 2.647  ops/ms
ClientPb.listUser                        thrpt       3  10.439 ± 0.481  ops/ms
ClientPb.createUser                       avgt       3   2.519 ± 0.126   ms/op
ClientPb.existUser                        avgt       3   2.444 ± 0.043   ms/op
ClientPb.getUser                          avgt       3   2.436 ± 0.572   ms/op
ClientPb.listUser                         avgt       3   2.991 ± 0.693   ms/op
ClientPb.createUser                     sample  375250   2.556 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.842           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.248           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.951           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.141           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.976           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.204           ms/op
ClientPb.existUser                      sample  388165   2.471 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.702           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.043           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.024           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.352           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.105           ms/op
ClientPb.getUser                        sample  380200   2.523 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.626           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.441           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.359           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.317           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.205           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.549           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.139           ms/op
ClientPb.listUser                       sample  320911   2.989 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.780           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.431           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.424           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.843           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.599           ms/op
```
