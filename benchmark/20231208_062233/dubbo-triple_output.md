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
[INFO] benchmark-base ..................................... SUCCESS [  2.999 s]
[INFO] server-base ........................................ SUCCESS [  0.343 s]
[INFO] client-base ........................................ SUCCESS [  0.649 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.536 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  4.843 s
[INFO] Finished at: 2023-12-08T06:09:11Z
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
# Warmup Iteration   1: 4.647 ops/ms
# Warmup Iteration   2: 11.472 ops/ms
# Warmup Iteration   3: 12.069 ops/ms
Iteration   1: 12.168 ops/ms
Iteration   2: 12.298 ops/ms
Iteration   3: 12.383 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.283 ±(99.9%) 1.972 ops/ms [Average]
  (min, avg, max) = (12.168, 12.283, 12.383), stdev = 0.108
  CI (99.9%): [10.311, 14.255] (assumes normal distribution)


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
# Warmup Iteration   1: 7.788 ops/ms
# Warmup Iteration   2: 12.595 ops/ms
# Warmup Iteration   3: 12.779 ops/ms
Iteration   1: 12.686 ops/ms
Iteration   2: 12.767 ops/ms
Iteration   3: 12.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.762 ±(99.9%) 1.358 ops/ms [Average]
  (min, avg, max) = (12.686, 12.762, 12.835), stdev = 0.074
  CI (99.9%): [11.405, 14.120] (assumes normal distribution)


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
# Warmup Iteration   1: 7.181 ops/ms
# Warmup Iteration   2: 12.507 ops/ms
# Warmup Iteration   3: 12.755 ops/ms
Iteration   1: 12.729 ops/ms
Iteration   2: 12.643 ops/ms
Iteration   3: 12.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.671 ±(99.9%) 0.922 ops/ms [Average]
  (min, avg, max) = (12.641, 12.671, 12.729), stdev = 0.051
  CI (99.9%): [11.749, 13.593] (assumes normal distribution)


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
# Warmup Iteration   1: 6.473 ops/ms
# Warmup Iteration   2: 10.476 ops/ms
# Warmup Iteration   3: 10.607 ops/ms
Iteration   1: 10.768 ops/ms
Iteration   2: 10.645 ops/ms
Iteration   3: 10.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.680 ±(99.9%) 1.397 ops/ms [Average]
  (min, avg, max) = (10.628, 10.680, 10.768), stdev = 0.077
  CI (99.9%): [9.283, 12.078] (assumes normal distribution)


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
# Warmup Iteration   1: 4.086 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.641 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.589 ±(99.9%) 0.004 ms/op
Iteration   1: 2.551 ±(99.9%) 0.004 ms/op
Iteration   2: 2.590 ±(99.9%) 0.004 ms/op
Iteration   3: 2.536 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.559 ±(99.9%) 0.511 ms/op [Average]
  (min, avg, max) = (2.536, 2.559, 2.590), stdev = 0.028
  CI (99.9%): [2.048, 3.070] (assumes normal distribution)


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
# Warmup Iteration   1: 3.769 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.509 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.003 ms/op
Iteration   1: 2.469 ±(99.9%) 0.004 ms/op
Iteration   2: 2.485 ±(99.9%) 0.003 ms/op
Iteration   3: 2.492 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.482 ±(99.9%) 0.209 ms/op [Average]
  (min, avg, max) = (2.469, 2.482, 2.492), stdev = 0.011
  CI (99.9%): [2.273, 2.691] (assumes normal distribution)


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
# Warmup Iteration   1: 3.922 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.004 ms/op
Iteration   1: 2.503 ±(99.9%) 0.005 ms/op
Iteration   2: 2.511 ±(99.9%) 0.004 ms/op
Iteration   3: 2.531 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.515 ±(99.9%) 0.257 ms/op [Average]
  (min, avg, max) = (2.503, 2.515, 2.531), stdev = 0.014
  CI (99.9%): [2.258, 2.772] (assumes normal distribution)


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
# Warmup Iteration   1: 4.734 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.006 ms/op
Iteration   1: 3.038 ±(99.9%) 0.006 ms/op
Iteration   2: 3.016 ±(99.9%) 0.005 ms/op
Iteration   3: 3.023 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.025 ±(99.9%) 0.207 ms/op [Average]
  (min, avg, max) = (3.016, 3.025, 3.038), stdev = 0.011
  CI (99.9%): [2.819, 3.232] (assumes normal distribution)


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
# Warmup Iteration   1: 4.134 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.723 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.555 ±(99.9%) 0.006 ms/op
Iteration   1: 2.573 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.085 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   3.891 ms/op
                 createUser·p0.999:  11.616 ms/op
                 createUser·p0.9999: 13.807 ms/op
                 createUser·p1.00:   14.139 ms/op

Iteration   2: 2.563 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   2.662 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.645 ms/op
                 createUser·p0.999:  9.622 ms/op
                 createUser·p0.9999: 13.247 ms/op
                 createUser·p1.00:   13.976 ms/op

Iteration   3: 2.571 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.894 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   3.869 ms/op
                 createUser·p0.999:  8.514 ms/op
                 createUser·p0.9999: 11.967 ms/op
                 createUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 373347
  mean =      2.569 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 177575 
    [ 2.500,  3.750) = 191550 
    [ 3.750,  5.000) = 3341 
    [ 5.000,  6.250) = 353 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 115 
    [12.500, 13.750) = 105 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      2.654 ms/op
     p(90.0000) =      3.117 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      3.813 ms/op
     p(99.9000) =      8.612 ms/op
     p(99.9900) =     13.418 ms/op
     p(99.9990) =     14.107 ms/op
     p(99.9999) =     14.139 ms/op
    p(100.0000) =     14.139 ms/op


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
# Warmup Iteration   1: 3.690 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
Iteration   1: 2.446 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.116 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.457 ms/op
                 existUser·p0.999:  4.975 ms/op
                 existUser·p0.9999: 13.384 ms/op
                 existUser·p1.00:   13.844 ms/op

Iteration   2: 2.485 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.978 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.010 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.727 ms/op
                 existUser·p0.999:  8.377 ms/op
                 existUser·p0.9999: 12.168 ms/op
                 existUser·p1.00:   13.124 ms/op

Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.874 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.034 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   3.883 ms/op
                 existUser·p0.999:  8.274 ms/op
                 existUser·p0.9999: 12.255 ms/op
                 existUser·p1.00:   13.206 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387719
  mean =      2.474 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 191300 
    [ 2.500,  3.750) = 192770 
    [ 3.750,  5.000) = 2864 
    [ 5.000,  6.250) = 329 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.715 ms/op
     p(99.9000) =      6.580 ms/op
     p(99.9900) =     12.832 ms/op
     p(99.9990) =     13.623 ms/op
     p(99.9999) =     13.844 ms/op
    p(100.0000) =     13.844 ms/op


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
# Warmup Iteration   1: 3.987 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.598 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.006 ms/op
Iteration   1: 2.505 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.048 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.940 ms/op
                 getUser·p0.999:  6.619 ms/op
                 getUser·p0.9999: 14.582 ms/op
                 getUser·p1.00:   15.811 ms/op

Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.929 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.478 ms/op
                 getUser·p0.999:  8.686 ms/op
                 getUser·p0.9999: 13.946 ms/op
                 getUser·p1.00:   14.451 ms/op

Iteration   3: 2.585 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.166 ms/op
                 getUser·p0.95:   3.363 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  8.331 ms/op
                 getUser·p0.9999: 11.807 ms/op
                 getUser·p1.00:   12.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379568
  mean =      2.527 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 185353 
    [ 2.500,  3.750) = 188601 
    [ 3.750,  5.000) = 4153 
    [ 5.000,  6.250) = 948 
    [ 6.250,  7.500) = 104 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      4.043 ms/op
     p(99.9000) =      6.978 ms/op
     p(99.9900) =     13.943 ms/op
     p(99.9990) =     15.022 ms/op
     p(99.9999) =     15.811 ms/op
    p(100.0000) =     15.811 ms/op


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
# Warmup Iteration   1: 4.896 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.009 ms/op
Iteration   1: 3.010 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.805 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.155 ms/op
                 listUser·p0.9999: 11.432 ms/op
                 listUser·p1.00:   12.059 ms/op

Iteration   2: 3.039 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.867 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   5.816 ms/op
                 listUser·p0.999:  9.814 ms/op
                 listUser·p0.9999: 11.772 ms/op
                 listUser·p1.00:   12.403 ms/op

Iteration   3: 2.970 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.835 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.509 ms/op
                 listUser·p0.9999: 12.722 ms/op
                 listUser·p1.00:   13.664 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319059
  mean =      3.006 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 147 
    [ 1.250,  2.500) = 95013 
    [ 2.500,  3.750) = 184199 
    [ 3.750,  5.000) = 31570 
    [ 5.000,  6.250) = 6791 
    [ 6.250,  7.500) = 664 
    [ 7.500,  8.750) = 228 
    [ 8.750, 10.000) = 191 
    [10.000, 11.250) = 173 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =      9.617 ms/op
     p(99.9900) =     11.913 ms/op
     p(99.9990) =     13.151 ms/op
     p(99.9999) =     13.664 ms/op
    p(100.0000) =     13.664 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.283 ± 1.972  ops/ms
ClientPb.existUser                       thrpt       3  12.762 ± 1.358  ops/ms
ClientPb.getUser                         thrpt       3  12.671 ± 0.922  ops/ms
ClientPb.listUser                        thrpt       3  10.680 ± 1.397  ops/ms
ClientPb.createUser                       avgt       3   2.559 ± 0.511   ms/op
ClientPb.existUser                        avgt       3   2.482 ± 0.209   ms/op
ClientPb.getUser                          avgt       3   2.515 ± 0.257   ms/op
ClientPb.listUser                         avgt       3   3.025 ± 0.207   ms/op
ClientPb.createUser                     sample  373347   2.569 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.894           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.654           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.813           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.612           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.418           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.139           ms/op
ClientPb.existUser                      sample  387719   2.474 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.874           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.715           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.580           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.832           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.844           ms/op
ClientPb.getUser                        sample  379568   2.527 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.929           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.043           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.978           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.943           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.811           ms/op
ClientPb.listUser                       sample  319059   3.006 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.805           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.652           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.617           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.913           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.664           ms/op
```
