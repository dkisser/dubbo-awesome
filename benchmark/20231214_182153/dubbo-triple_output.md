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
[INFO] benchmark-base ..................................... SUCCESS [  2.997 s]
[INFO] server-base ........................................ SUCCESS [  0.332 s]
[INFO] client-base ........................................ SUCCESS [  0.645 s]
[INFO] dubbo-triple-client ................................ SUCCESS [  0.441 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  4.726 s
[INFO] Finished at: 2023-12-14T18:08:31Z
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
# Warmup Iteration   1: 4.812 ops/ms
# Warmup Iteration   2: 12.058 ops/ms
# Warmup Iteration   3: 12.250 ops/ms
Iteration   1: 12.831 ops/ms
Iteration   2: 12.844 ops/ms
Iteration   3: 12.747 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.807 ±(99.9%) 0.963 ops/ms [Average]
  (min, avg, max) = (12.747, 12.807, 12.844), stdev = 0.053
  CI (99.9%): [11.844, 13.770] (assumes normal distribution)


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
# Warmup Iteration   2: 13.220 ops/ms
# Warmup Iteration   3: 13.198 ops/ms
Iteration   1: 13.305 ops/ms
Iteration   2: 13.184 ops/ms
Iteration   3: 13.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.253 ±(99.9%) 1.144 ops/ms [Average]
  (min, avg, max) = (13.184, 13.253, 13.305), stdev = 0.063
  CI (99.9%): [12.109, 14.397] (assumes normal distribution)


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
# Warmup Iteration   1: 7.853 ops/ms
# Warmup Iteration   2: 12.817 ops/ms
# Warmup Iteration   3: 12.941 ops/ms
Iteration   1: 13.144 ops/ms
Iteration   2: 12.974 ops/ms
Iteration   3: 13.097 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.072 ±(99.9%) 1.600 ops/ms [Average]
  (min, avg, max) = (12.974, 13.072, 13.144), stdev = 0.088
  CI (99.9%): [11.472, 14.671] (assumes normal distribution)


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
# Warmup Iteration   1: 6.823 ops/ms
# Warmup Iteration   2: 10.597 ops/ms
# Warmup Iteration   3: 10.734 ops/ms
Iteration   1: 10.850 ops/ms
Iteration   2: 10.792 ops/ms
Iteration   3: 10.676 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.772 ±(99.9%) 1.618 ops/ms [Average]
  (min, avg, max) = (10.676, 10.772, 10.850), stdev = 0.089
  CI (99.9%): [9.155, 12.390] (assumes normal distribution)


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
# Warmup Iteration   1: 3.950 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.004 ms/op
Iteration   1: 2.487 ±(99.9%) 0.004 ms/op
Iteration   2: 2.527 ±(99.9%) 0.004 ms/op
Iteration   3: 2.470 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.495 ±(99.9%) 0.534 ms/op [Average]
  (min, avg, max) = (2.470, 2.495, 2.527), stdev = 0.029
  CI (99.9%): [1.961, 3.029] (assumes normal distribution)


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
# Warmup Iteration   1: 3.822 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.410 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.407 ±(99.9%) 0.004 ms/op
Iteration   1: 2.430 ±(99.9%) 0.004 ms/op
Iteration   2: 2.414 ±(99.9%) 0.003 ms/op
Iteration   3: 2.420 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.422 ±(99.9%) 0.150 ms/op [Average]
  (min, avg, max) = (2.414, 2.422, 2.430), stdev = 0.008
  CI (99.9%): [2.272, 2.571] (assumes normal distribution)


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
# Warmup Iteration   1: 3.878 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.464 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.421 ±(99.9%) 0.004 ms/op
Iteration   1: 2.445 ±(99.9%) 0.004 ms/op
Iteration   2: 2.449 ±(99.9%) 0.004 ms/op
Iteration   3: 2.432 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.442 ±(99.9%) 0.163 ms/op [Average]
  (min, avg, max) = (2.432, 2.442, 2.449), stdev = 0.009
  CI (99.9%): [2.279, 2.605] (assumes normal distribution)


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
# Warmup Iteration   1: 4.683 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.999 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.005 ms/op
Iteration   1: 2.942 ±(99.9%) 0.005 ms/op
Iteration   2: 2.954 ±(99.9%) 0.004 ms/op
Iteration   3: 2.936 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.944 ±(99.9%) 0.160 ms/op [Average]
  (min, avg, max) = (2.936, 2.944, 2.954), stdev = 0.009
  CI (99.9%): [2.783, 3.104] (assumes normal distribution)


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
# Warmup Iteration   1: 4.055 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 2.734 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.006 ms/op
Iteration   1: 2.542 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.968 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  11.223 ms/op
                 createUser·p0.9999: 14.099 ms/op
                 createUser·p1.00:   14.631 ms/op

Iteration   2: 2.484 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.999 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.011 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.539 ms/op
                 createUser·p0.999:  9.068 ms/op
                 createUser·p0.9999: 11.698 ms/op
                 createUser·p1.00:   12.485 ms/op

Iteration   3: 2.510 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.006 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.596 ms/op
                 createUser·p0.999:  8.389 ms/op
                 createUser·p0.9999: 11.277 ms/op
                 createUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381837
  mean =      2.512 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 185964 
    [ 2.500,  3.750) = 192871 
    [ 3.750,  5.000) = 2327 
    [ 5.000,  6.250) = 230 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 118 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.613 ms/op
     p(99.9000) =      8.427 ms/op
     p(99.9900) =     13.219 ms/op
     p(99.9990) =     14.403 ms/op
     p(99.9999) =     14.631 ms/op
    p(100.0000) =     14.631 ms/op


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
# Warmup Iteration   1: 3.702 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.438 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.408 ±(99.9%) 0.005 ms/op
Iteration   1: 2.378 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.971 ms/op
                 existUser·p0.50:   2.441 ms/op
                 existUser·p0.90:   2.888 ms/op
                 existUser·p0.95:   2.979 ms/op
                 existUser·p0.99:   3.387 ms/op
                 existUser·p0.999:  5.455 ms/op
                 existUser·p0.9999: 13.861 ms/op
                 existUser·p1.00:   14.418 ms/op

Iteration   2: 2.403 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.005 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.473 ms/op
                 existUser·p0.999:  5.677 ms/op
                 existUser·p0.9999: 10.399 ms/op
                 existUser·p1.00:   11.108 ms/op

Iteration   3: 2.428 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.104 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.617 ms/op
                 existUser·p0.999:  8.204 ms/op
                 existUser·p0.9999: 11.698 ms/op
                 existUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 399046
  mean =      2.403 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 201853 
    [ 2.500,  3.750) = 194632 
    [ 3.750,  5.000) = 1819 
    [ 5.000,  6.250) = 300 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 120 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.971 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      2.920 ms/op
     p(95.0000) =      3.023 ms/op
     p(99.0000) =      3.486 ms/op
     p(99.9000) =      6.577 ms/op
     p(99.9900) =     12.535 ms/op
     p(99.9990) =     14.271 ms/op
     p(99.9999) =     14.418 ms/op
    p(100.0000) =     14.418 ms/op


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
# Warmup Iteration   1: 3.908 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.507 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.006 ms/op
Iteration   1: 2.460 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.983 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.830 ms/op
                 getUser·p0.999:  6.204 ms/op
                 getUser·p0.9999: 13.992 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   2: 2.441 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.975 ms/op
                 getUser·p0.50:   2.454 ms/op
                 getUser·p0.90:   2.970 ms/op
                 getUser·p0.95:   3.068 ms/op
                 getUser·p0.99:   3.502 ms/op
                 getUser·p0.999:  5.812 ms/op
                 getUser·p0.9999: 13.500 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.957 ms/op
                 getUser·p0.50:   2.454 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.850 ms/op
                 getUser·p0.999:  6.906 ms/op
                 getUser·p0.9999: 11.814 ms/op
                 getUser·p1.00:   13.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 390148
  mean =      2.458 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 87 
    [ 1.250,  2.500) = 198678 
    [ 2.500,  3.750) = 187672 
    [ 3.750,  5.000) = 3072 
    [ 5.000,  6.250) = 244 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 113 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      2.462 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.723 ms/op
     p(99.9000) =      6.636 ms/op
     p(99.9900) =     13.533 ms/op
     p(99.9990) =     14.239 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


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
# Warmup Iteration   1: 4.525 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.013 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.008 ms/op
Iteration   1: 2.951 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.920 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.801 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   5.407 ms/op
                 listUser·p0.999:  9.060 ms/op
                 listUser·p0.9999: 10.338 ms/op
                 listUser·p1.00:   11.223 ms/op

Iteration   2: 2.946 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.792 ms/op
                 listUser·p0.50:   2.875 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  8.920 ms/op
                 listUser·p0.9999: 10.341 ms/op
                 listUser·p1.00:   10.813 ms/op

Iteration   3: 2.950 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.889 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.322 ms/op
                 listUser·p0.9999: 12.725 ms/op
                 listUser·p1.00:   13.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 325234
  mean =      2.949 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 137 
    [ 1.250,  2.500) = 104312 
    [ 2.500,  3.750) = 185222 
    [ 3.750,  5.000) = 28907 
    [ 5.000,  6.250) = 5500 
    [ 6.250,  7.500) = 483 
    [ 7.500,  8.750) = 252 
    [ 8.750, 10.000) = 303 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     11.182 ms/op
     p(99.9990) =     13.021 ms/op
     p(99.9999) =     13.042 ms/op
    p(100.0000) =     13.042 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.807 ± 0.963  ops/ms
ClientPb.existUser                       thrpt       3  13.253 ± 1.144  ops/ms
ClientPb.getUser                         thrpt       3  13.072 ± 1.600  ops/ms
ClientPb.listUser                        thrpt       3  10.772 ± 1.618  ops/ms
ClientPb.createUser                       avgt       3   2.495 ± 0.534   ms/op
ClientPb.existUser                        avgt       3   2.422 ± 0.150   ms/op
ClientPb.getUser                          avgt       3   2.442 ± 0.163   ms/op
ClientPb.listUser                         avgt       3   2.944 ± 0.160   ms/op
ClientPb.createUser                     sample  381837   2.512 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.968           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.613           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.427           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.219           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.631           ms/op
ClientPb.existUser                      sample  399046   2.403 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.971           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.478           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.920           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.486           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.577           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.535           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.418           ms/op
ClientPb.getUser                        sample  390148   2.458 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.957           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.462           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.723           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.636           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.533           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.402           ms/op
ClientPb.listUser                       sample  325234   2.949 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.792           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.892           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.809           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.472           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.044           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.182           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.042           ms/op
```
