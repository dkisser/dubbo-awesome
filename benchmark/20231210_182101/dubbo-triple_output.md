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
[INFO] benchmark-base ..................................... SUCCESS [  2.821 s]
[INFO] server-base ........................................ SUCCESS [  0.294 s]
[INFO] client-base ........................................ SUCCESS [  0.575 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.332 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  4.354 s
[INFO] Finished at: 2023-12-10T18:07:27Z
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
# Warmup Iteration   1: 4.310 ops/ms
# Warmup Iteration   2: 11.841 ops/ms
# Warmup Iteration   3: 12.150 ops/ms
Iteration   1: 12.421 ops/ms
Iteration   2: 12.371 ops/ms
Iteration   3: 12.434 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.409 ±(99.9%) 0.614 ops/ms [Average]
  (min, avg, max) = (12.371, 12.409, 12.434), stdev = 0.034
  CI (99.9%): [11.795, 13.022] (assumes normal distribution)


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
# Warmup Iteration   1: 8.170 ops/ms
# Warmup Iteration   2: 12.981 ops/ms
# Warmup Iteration   3: 12.875 ops/ms
Iteration   1: 12.864 ops/ms
Iteration   2: 12.960 ops/ms
Iteration   3: 12.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.928 ±(99.9%) 1.000 ops/ms [Average]
  (min, avg, max) = (12.864, 12.928, 12.960), stdev = 0.055
  CI (99.9%): [11.928, 13.927] (assumes normal distribution)


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
# Warmup Iteration   1: 7.736 ops/ms
# Warmup Iteration   2: 12.440 ops/ms
# Warmup Iteration   3: 12.751 ops/ms
Iteration   1: 12.593 ops/ms
Iteration   2: 12.857 ops/ms
Iteration   3: 12.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.773 ±(99.9%) 2.845 ops/ms [Average]
  (min, avg, max) = (12.593, 12.773, 12.869), stdev = 0.156
  CI (99.9%): [9.928, 15.618] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.230 ops/ms
# Warmup Iteration   2: 10.369 ops/ms
# Warmup Iteration   3: 10.505 ops/ms
Iteration   1: 10.405 ops/ms
Iteration   2: 10.500 ops/ms
Iteration   3: 10.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.483 ±(99.9%) 1.287 ops/ms [Average]
  (min, avg, max) = (10.405, 10.483, 10.543), stdev = 0.071
  CI (99.9%): [9.196, 11.769] (assumes normal distribution)


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
# Warmup Iteration   1: 4.214 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.604 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.534 ±(99.9%) 0.004 ms/op
Iteration   1: 2.562 ±(99.9%) 0.004 ms/op
Iteration   2: 2.532 ±(99.9%) 0.004 ms/op
Iteration   3: 2.526 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.540 ±(99.9%) 0.354 ms/op [Average]
  (min, avg, max) = (2.526, 2.540, 2.562), stdev = 0.019
  CI (99.9%): [2.185, 2.894] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.652 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.486 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.004 ms/op
Iteration   1: 2.445 ±(99.9%) 0.004 ms/op
Iteration   2: 2.426 ±(99.9%) 0.004 ms/op
Iteration   3: 2.470 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.447 ±(99.9%) 0.409 ms/op [Average]
  (min, avg, max) = (2.426, 2.447, 2.470), stdev = 0.022
  CI (99.9%): [2.038, 2.856] (assumes normal distribution)


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
# Warmup Iteration   1: 3.846 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.548 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
Iteration   1: 2.467 ±(99.9%) 0.004 ms/op
Iteration   2: 2.460 ±(99.9%) 0.004 ms/op
Iteration   3: 2.479 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.469 ±(99.9%) 0.180 ms/op [Average]
  (min, avg, max) = (2.460, 2.469, 2.479), stdev = 0.010
  CI (99.9%): [2.289, 2.649] (assumes normal distribution)


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
# Warmup Iteration   1: 4.759 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.006 ms/op
Iteration   1: 3.119 ±(99.9%) 0.004 ms/op
Iteration   2: 3.025 ±(99.9%) 0.006 ms/op
Iteration   3: 2.922 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.022 ±(99.9%) 1.796 ms/op [Average]
  (min, avg, max) = (2.922, 3.022, 3.119), stdev = 0.098
  CI (99.9%): [1.225, 4.818] (assumes normal distribution)


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
# Warmup Iteration   1: 4.471 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 2.680 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.007 ms/op
Iteration   1: 2.492 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.749 ms/op
                 createUser·p0.50:   2.445 ms/op
                 createUser·p0.90:   3.207 ms/op
                 createUser·p0.95:   3.564 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  11.665 ms/op
                 createUser·p0.9999: 15.491 ms/op
                 createUser·p1.00:   17.105 ms/op

Iteration   2: 2.554 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.709 ms/op
                 createUser·p0.50:   2.519 ms/op
                 createUser·p0.90:   3.297 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  11.401 ms/op
                 createUser·p0.9999: 20.840 ms/op
                 createUser·p1.00:   22.282 ms/op

Iteration   3: 2.540 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.570 ms/op
                 createUser·p0.50:   2.499 ms/op
                 createUser·p0.90:   3.310 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  9.681 ms/op
                 createUser·p0.9999: 12.247 ms/op
                 createUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379309
  mean =      2.528 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 191825 
    [ 2.500,  5.000) = 185189 
    [ 5.000,  7.500) = 1721 
    [ 7.500, 10.000) = 179 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      3.269 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =     10.322 ms/op
     p(99.9900) =     16.845 ms/op
     p(99.9990) =     21.772 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


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
# Warmup Iteration   1: 3.894 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.591 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.006 ms/op
Iteration   1: 2.518 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.625 ms/op
                 existUser·p0.999:  12.665 ms/op
                 existUser·p0.9999: 18.721 ms/op
                 existUser·p1.00:   22.970 ms/op

Iteration   2: 2.460 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.560 ms/op
                 existUser·p0.50:   2.413 ms/op
                 existUser·p0.90:   3.146 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  8.219 ms/op
                 existUser·p0.9999: 17.826 ms/op
                 existUser·p1.00:   21.856 ms/op

Iteration   3: 2.475 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.764 ms/op
                 existUser·p0.50:   2.425 ms/op
                 existUser·p0.90:   3.162 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  11.136 ms/op
                 existUser·p0.9999: 16.338 ms/op
                 existUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386015
  mean =      2.484 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 206783 
    [ 2.500,  5.000) = 177139 
    [ 5.000,  7.500) = 1520 
    [ 7.500, 10.000) = 207 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      2.433 ms/op
     p(90.0000) =      3.183 ms/op
     p(95.0000) =      3.559 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      9.552 ms/op
     p(99.9900) =     17.609 ms/op
     p(99.9990) =     21.349 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


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
# Warmup Iteration   1: 4.123 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.652 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.555 ±(99.9%) 0.007 ms/op
Iteration   1: 2.612 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.517 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.387 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.940 ms/op
                 getUser·p0.999:  12.429 ms/op
                 getUser·p0.9999: 16.159 ms/op
                 getUser·p1.00:   23.626 ms/op

Iteration   2: 2.639 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.561 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   5.169 ms/op
                 getUser·p0.999:  11.158 ms/op
                 getUser·p0.9999: 15.696 ms/op
                 getUser·p1.00:   17.138 ms/op

Iteration   3: 2.568 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.536 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.318 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.686 ms/op
                 getUser·p0.999:  11.166 ms/op
                 getUser·p0.9999: 15.896 ms/op
                 getUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 368034
  mean =      2.606 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 176347 
    [ 2.500,  5.000) = 188285 
    [ 5.000,  7.500) = 2780 
    [ 7.500, 10.000) = 213 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.517 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.923 ms/op
     p(99.9000) =     11.239 ms/op
     p(99.9900) =     15.974 ms/op
     p(99.9990) =     16.937 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 4.853 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.011 ms/op
Iteration   1: 3.268 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.423 ms/op
                 listUser·p0.50:   3.109 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   5.030 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  11.357 ms/op
                 listUser·p0.9999: 20.108 ms/op
                 listUser·p1.00:   24.314 ms/op

Iteration   2: 3.120 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.402 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   6.237 ms/op
                 listUser·p0.999:  11.354 ms/op
                 listUser·p0.9999: 14.275 ms/op
                 listUser·p1.00:   15.090 ms/op

Iteration   3: 3.105 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.808 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   6.275 ms/op
                 listUser·p0.999:  10.143 ms/op
                 listUser·p0.9999: 13.442 ms/op
                 listUser·p1.00:   31.588 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 303257
  mean =      3.163 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 86356 
    [ 2.500,  5.000) = 203704 
    [ 5.000,  7.500) = 11440 
    [ 7.500, 10.000) = 1289 
    [10.000, 12.500) = 331 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.402 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      6.529 ms/op
     p(99.9000) =     11.088 ms/op
     p(99.9900) =     18.765 ms/op
     p(99.9990) =     30.115 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.409 ± 0.614  ops/ms
ClientPb.existUser                       thrpt       3  12.928 ± 1.000  ops/ms
ClientPb.getUser                         thrpt       3  12.773 ± 2.845  ops/ms
ClientPb.listUser                        thrpt       3  10.483 ± 1.287  ops/ms
ClientPb.createUser                       avgt       3   2.540 ± 0.354   ms/op
ClientPb.existUser                        avgt       3   2.447 ± 0.409   ms/op
ClientPb.getUser                          avgt       3   2.469 ± 0.180   ms/op
ClientPb.listUser                         avgt       3   3.022 ± 1.796   ms/op
ClientPb.createUser                     sample  379309   2.528 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.570           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.490           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.269           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.658           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.579           ms/op
ClientPb.createUser:createUser·p0.999   sample          10.322           ms/op
ClientPb.createUser:createUser·p0.9999  sample          16.845           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.282           ms/op
ClientPb.existUser                      sample  386015   2.484 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.560           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.433           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.183           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.559           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.514           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.552           ms/op
ClientPb.existUser:existUser·p0.9999    sample          17.609           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.970           ms/op
ClientPb.getUser                        sample  368034   2.606 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.517           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.383           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.923           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.239           ms/op
ClientPb.getUser:getUser·p0.9999        sample          15.974           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.626           ms/op
ClientPb.listUser                       sample  303257   3.163 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.402           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.031           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.891           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.529           ms/op
ClientPb.listUser:listUser·p0.999       sample          11.088           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.765           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.588           ms/op
```
