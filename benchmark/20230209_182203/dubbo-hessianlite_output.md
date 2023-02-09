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
[INFO] os.detected.version: 5.15
[INFO] os.detected.version.major: 5
[INFO] os.detected.version.minor: 15
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
[INFO] dubbo-hessianlite-client                                           [jar]
[INFO] 
[INFO] ------------------< org.apache.dubbo:benchmark-base >-------------------
[INFO] Building benchmark-base 1.0-SNAPSHOT                               [1/4]
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
[INFO] --- build-helper-maven-plugin:3.3.0:add-source (default) @ benchmark-base ---
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
[INFO] -------------< org.apache.dubbo:dubbo-hessianlite-client >--------------
[INFO] Building dubbo-hessianlite-client 1.0-SNAPSHOT                     [4/4]
[INFO] --------------------------------[ jar ]---------------------------------
[INFO] 
[INFO] --- maven-clean-plugin:2.5:clean (default-clean) @ dubbo-hessianlite-client ---
[INFO] 
[INFO] --- maven-resources-plugin:2.6:resources (default-resources) @ dubbo-hessianlite-client ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] Copying 1 resource
[INFO] 
[INFO] --- maven-compiler-plugin:3.7.0:compile (default-compile) @ dubbo-hessianlite-client ---
[INFO] No sources to compile
[INFO] 
[INFO] --- maven-resources-plugin:2.6:testResources (default-testResources) @ dubbo-hessianlite-client ---
[WARNING] Using platform encoding (UTF-8 actually) to copy filtered resources, i.e. build is platform dependent!
[INFO] skip non existing resourceDirectory /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/src/test/resources
[INFO] 
[INFO] --- maven-compiler-plugin:3.7.0:testCompile (default-testCompile) @ dubbo-hessianlite-client ---
[INFO] No sources to compile
[INFO] 
[INFO] --- maven-surefire-plugin:2.12.4:test (default-test) @ dubbo-hessianlite-client ---
[INFO] No tests to run.
[INFO] 
[INFO] --- maven-dependency-plugin:3.1.0:copy-dependencies (copy-dependencies) @ dubbo-hessianlite-client ---
Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/1.0.8/plexus-1.0.8.pom
Progress (1): 2.7/7.2 kBProgress (1): 5.5/7.2 kBProgress (1): 7.2 kB                        Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/1.0.8/plexus-1.0.8.pom (7.2 kB at 2.4 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-classworlds/1.2-alpha-7/plexus-classworlds-1.2-alpha-7.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-classworlds/1.2-alpha-7/plexus-classworlds-1.2-alpha-7.pom (0 B at 0 B/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/1.0.9/plexus-1.0.9.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus/1.0.9/plexus-1.0.9.pom (0 B at 0 B/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/velocity/velocity/1.5/velocity-1.5.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/velocity/velocity/1.5/velocity-1.5.pom (0 B at 0 B/s)
Downloading from central: https://repo.maven.apache.org/maven2/commons-collections/commons-collections/3.1/commons-collections-3.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/commons-collections/commons-collections/3.1/commons-collections-3.1.pom (0 B at 0 B/s)
Downloading from central: https://repo.maven.apache.org/maven2/commons-lang/commons-lang/2.1/commons-lang-2.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/commons-lang/commons-lang/2.1/commons-lang-2.1.pom (0 B at 0 B/s)
Downloading from central: https://repo.maven.apache.org/maven2/commons-validator/commons-validator/1.3.1/commons-validator-1.3.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/commons-validator/commons-validator/1.3.1/commons-validator-1.3.1.pom (0 B at 0 B/s)
Downloading from central: https://repo.maven.apache.org/maven2/commons-collections/commons-collections/2.0/commons-collections-2.0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/commons-collections/commons-collections/2.0/commons-collections-2.0.pom (0 B at 0 B/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/doxia/doxia-site-renderer/1.4/doxia-site-renderer-1.4.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/doxia/doxia-site-renderer/1.4/doxia-site-renderer-1.4.pom (0 B at 0 B/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/doxia/doxia-decoration-model/1.4/doxia-decoration-model-1.4.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/doxia/doxia-decoration-model/1.4/doxia-decoration-model-1.4.pom (0 B at 0 B/s)
Downloading from central: https://repo.maven.apache.org/maven2/logkit/logkit/1.0.1/logkit-1.0.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/logkit/logkit/1.0.1/logkit-1.0.1.pom (0 B at 0 B/s)
Downloading from central: https://repo.maven.apache.org/maven2/sslext/sslext/1.2-0/sslext-1.2-0.pom
Downloaded from central: https://repo.maven.apache.org/maven2/sslext/sslext/1.2-0/sslext-1.2-0.pom (0 B at 0 B/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/struts/struts-taglib/1.3.8/struts-taglib-1.3.8.pom
Progress (1): 2.7/3.1 kBProgress (1): 3.1 kB                        Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/struts/struts-taglib/1.3.8/struts-taglib-1.3.8.pom (3.1 kB at 110 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/velocity/velocity/1.6.2/velocity-1.6.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/velocity/velocity/1.6.2/velocity-1.6.2.pom (0 B at 0 B/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven/2.0.2/maven-2.0.2.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/maven/2.0.2/maven-2.0.2.pom (0 B at 0 B/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-dependency-analyzer/1.9/maven-dependency-analyzer-1.9.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-dependency-analyzer/1.9/maven-dependency-analyzer-1.9.pom (0 B at 0 B/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-dependency-tree/3.0.1/maven-dependency-tree-3.0.1.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-dependency-tree/3.0.1/maven-dependency-tree-3.0.1.pom (0 B at 0 B/s)
Downloading from central: https://repo.maven.apache.org/maven2/commons-codec/commons-codec/1.6/commons-codec-1.6.pom
Progress (1): 2.7/11 kBProgress (1): 5.5/11 kBProgress (1): 8.2/11 kBProgress (1): 11/11 kB Progress (1): 11 kB                      Downloaded from central: https://repo.maven.apache.org/maven2/commons-codec/commons-codec/1.6/commons-codec-1.6.pom (11 kB at 485 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-parent/1.7.5/slf4j-parent-1.7.5.pom
Downloaded from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-parent/1.7.5/slf4j-parent-1.7.5.pom (0 B at 0 B/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/reporting/maven-reporting-api/3.0/maven-reporting-api-3.0.jar
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/reporting/maven-reporting-impl/2.3/maven-reporting-impl-2.3.jar
Downloading from central: https://repo.maven.apache.org/maven2/xerces/xercesImpl/2.9.1/xercesImpl-2.9.1.jar
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/doxia/doxia-core/1.2/doxia-core-1.2.jar
Downloading from central: https://repo.maven.apache.org/maven2/xml-apis/xml-apis/1.3.04/xml-apis-1.3.04.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/reporting/maven-reporting-api/3.0/maven-reporting-api-3.0.jar (0 B at 0 B/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/httpclient/4.0.2/httpclient-4.0.2.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/doxia/doxia-core/1.2/doxia-core-1.2.jar (0 B at 0 B/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/httpcore/4.0.1/httpcore-4.0.1.jar
Downloaded from central: https://repo.maven.apache.org/maven2/xml-apis/xml-apis/1.3.04/xml-apis-1.3.04.jar (0 B at 0 B/s)
Downloading from central: https://repo.maven.apache.org/maven2/commons-validator/commons-validator/1.3.1/commons-validator-1.3.1.jar
Progress (1): 2.7/173 kBProgress (1): 5.5/173 kBProgress (1): 8.2/173 kBProgress (1): 11/173 kB Progress (1): 14/173 kBProgress (1): 16/173 kBProgress (2): 16/173 kB | 4.1/139 kBProgress (2): 16/173 kB | 8.2/139 kBProgress (2): 20/173 kB | 8.2/139 kBProgress (2): 24/173 kB | 8.2/139 kBProgress (2): 28/173 kB | 8.2/139 kBProgress (2): 32/173 kB | 8.2/139 kBProgress (2): 32/173 kB | 12/139 kB Progress (2): 32/173 kB | 16/139 kBProgress (2): 36/173 kB | 16/139 kBProgress (2): 40/173 kB | 16/139 kBProgress (2): 45/173 kB | 16/139 kBProgress (2): 49/173 kB | 16/139 kBProgress (2): 53/173 kB | 16/139 kBProgress (2): 57/173 kB | 16/139 kBProgress (2): 61/173 kB | 16/139 kBProgress (2): 65/173 kB | 16/139 kBProgress (2): 69/173 kB | 16/139 kBProgress (2): 73/173 kB | 16/139 kBProgress (2): 77/173 kB | 16/139 kBProgress (2): 81/173 kB | 16/139 kBProgress (2): 86/173 kB | 16/139 kBProgress (2): 86/173 kB | 20/139 kBProgress (2): 86/173 kB | 25/139 kBProgress (2): 86/173 kB | 29/139 kBProgress (2): 86/173 kB | 33/139 kBProgress (2): 86/173 kB | 37/139 kBProgress (2): 86/173 kB | 41/139 kBProgress (2): 86/173 kB | 45/139 kBProgress (2): 86/173 kB | 49/139 kBProgress (2): 86/173 kB | 53/139 kBProgress (2): 86/173 kB | 57/139 kBProgress (2): 86/173 kB | 61/139 kBProgress (2): 86/173 kB | 66/139 kBProgress (2): 86/173 kB | 70/139 kBProgress (2): 86/173 kB | 74/139 kBProgress (2): 86/173 kB | 78/139 kBProgress (2): 86/173 kB | 82/139 kBProgress (2): 86/173 kB | 86/139 kBProgress (2): 86/173 kB | 90/139 kBProgress (2): 86/173 kB | 94/139 kBProgress (2): 86/173 kB | 98/139 kBProgress (2): 86/173 kB | 102/139 kB                                    Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/httpclient/4.0.2/httpclient-4.0.2.jar (0 B at 0 B/s)
Downloading from central: https://repo.maven.apache.org/maven2/commons-beanutils/commons-beanutils/1.7.0/commons-beanutils-1.7.0.jar
Progress (2): 90/173 kB | 102/139 kBProgress (2): 94/173 kB | 102/139 kBProgress (2): 98/173 kB | 102/139 kBProgress (2): 98/173 kB | 106/139 kBProgress (2): 98/173 kB | 111/139 kBProgress (2): 98/173 kB | 115/139 kBProgress (2): 98/173 kB | 119/139 kBProgress (2): 98/173 kB | 123/139 kBProgress (2): 98/173 kB | 127/139 kBProgress (2): 102/173 kB | 127/139 kBProgress (2): 106/173 kB | 127/139 kBProgress (2): 110/173 kB | 127/139 kBProgress (2): 114/173 kB | 127/139 kBProgress (2): 118/173 kB | 127/139 kBProgress (2): 122/173 kB | 127/139 kBProgress (2): 126/173 kB | 127/139 kBProgress (2): 131/173 kB | 127/139 kBProgress (2): 131/173 kB | 131/139 kBProgress (3): 131/173 kB | 131/139 kB | 4.1/189 kBProgress (3): 131/173 kB | 131/139 kB | 8.2/189 kBProgress (3): 131/173 kB | 131/139 kB | 12/189 kB Progress (3): 131/173 kB | 131/139 kB | 16/189 kBProgress (3): 135/173 kB | 131/139 kB | 16/189 kBProgress (3): 139/173 kB | 131/139 kB | 16/189 kBProgress (3): 143/173 kB | 131/139 kB | 16/189 kBProgress (3): 147/173 kB | 131/139 kB | 16/189 kBProgress (3): 151/173 kB | 131/139 kB | 16/189 kBProgress (3): 155/173 kB | 131/139 kB | 16/189 kBProgress (3): 155/173 kB | 135/139 kB | 16/189 kBProgress (3): 155/173 kB | 139 kB | 16/189 kB    Progress (3): 155/173 kB | 139 kB | 20/189 kBProgress (3): 155/173 kB | 139 kB | 25/189 kBProgress (3): 155/173 kB | 139 kB | 29/189 kBProgress (3): 155/173 kB | 139 kB | 33/189 kBProgress (3): 155/173 kB | 139 kB | 37/189 kBProgress (3): 155/173 kB | 139 kB | 41/189 kBProgress (3): 155/173 kB | 139 kB | 45/189 kBProgress (3): 155/173 kB | 139 kB | 49/189 kBProgress (3): 159/173 kB | 139 kB | 49/189 kBProgress (3): 163/173 kB | 139 kB | 49/189 kBProgress (3): 167/173 kB | 139 kB | 49/189 kBProgress (3): 172/173 kB | 139 kB | 49/189 kBProgress (3): 173 kB | 139 kB | 49/189 kB                                             Downloaded from central: https://repo.maven.apache.org/maven2/commons-validator/commons-validator/1.3.1/commons-validator-1.3.1.jar (139 kB at 491 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/commons-digester/commons-digester/1.6/commons-digester-1.6.jar
Progress (2): 173 kB | 53/189 kBProgress (2): 173 kB | 57/189 kBProgress (2): 173 kB | 61/189 kBProgress (2): 173 kB | 66/189 kBProgress (2): 173 kB | 70/189 kBProgress (2): 173 kB | 74/189 kBProgress (2): 173 kB | 78/189 kBProgress (2): 173 kB | 82/189 kB                                Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/httpcomponents/httpcore/4.0.1/httpcore-4.0.1.jar (173 kB at 586 kB/s)
Progress (1): 86/189 kBProgress (1): 90/189 kBProgress (1): 94/189 kBProgress (1): 98/189 kBProgress (2): 98/189 kB | 4.1/168 kBProgress (2): 98/189 kB | 8.2/168 kBProgress (2): 98/189 kB | 12/168 kB Progress (2): 98/189 kB | 16/168 kBProgress (2): 98/189 kB | 20/168 kBProgress (2): 98/189 kB | 25/168 kBProgress (2): 98/189 kB | 29/168 kBProgress (2): 98/189 kB | 33/168 kBProgress (2): 98/189 kB | 37/168 kBProgress (2): 98/189 kB | 41/168 kBProgress (2): 98/189 kB | 45/168 kBProgress (2): 98/189 kB | 49/168 kBProgress (2): 102/189 kB | 49/168 kBProgress (2): 106/189 kB | 49/168 kBProgress (2): 111/189 kB | 49/168 kBProgress (2): 115/189 kB | 49/168 kB                                    Downloading from central: https://repo.maven.apache.org/maven2/commons-logging/commons-logging/1.0.4/commons-logging-1.0.4.jar
Progress (2): 119/189 kB | 49/168 kBProgress (2): 123/189 kB | 49/168 kBProgress (2): 127/189 kB | 49/168 kBProgress (2): 131/189 kB | 49/168 kBProgress (2): 135/189 kB | 49/168 kBProgress (2): 139/189 kB | 49/168 kBProgress (2): 143/189 kB | 49/168 kBProgress (2): 147/189 kB | 49/168 kB                                    Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/reporting/maven-reporting-impl/2.3/maven-reporting-impl-2.3.jar (0 B at 0 B/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/doxia/doxia-sink-api/1.4/doxia-sink-api-1.4.jar
Progress (2): 147/189 kB | 53/168 kBProgress (2): 147/189 kB | 57/168 kBProgress (2): 147/189 kB | 61/168 kBProgress (2): 147/189 kB | 66/168 kBProgress (3): 147/189 kB | 66/168 kB | 2.7/11 kBProgress (3): 147/189 kB | 66/168 kB | 5.5/11 kBProgress (3): 147/189 kB | 66/168 kB | 8.2/11 kBProgress (3): 147/189 kB | 66/168 kB | 11/11 kB Progress (3): 147/189 kB | 66/168 kB | 11 kB   Progress (4): 147/189 kB | 66/168 kB | 11 kB | 4.1/38 kBProgress (4): 147/189 kB | 66/168 kB | 11 kB | 8.2/38 kBProgress (4): 147/189 kB | 66/168 kB | 11 kB | 12/38 kB Progress (4): 147/189 kB | 66/168 kB | 11 kB | 16/38 kBProgress (4): 147/189 kB | 66/168 kB | 11 kB | 20/38 kBProgress (4): 147/189 kB | 66/168 kB | 11 kB | 25/38 kBProgress (4): 147/189 kB | 66/168 kB | 11 kB | 29/38 kBProgress (4): 147/189 kB | 66/168 kB | 11 kB | 33/38 kB                                                       Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/doxia/doxia-sink-api/1.4/doxia-sink-api-1.4.jar (11 kB at 34 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/doxia/doxia-logging-api/1.4/doxia-logging-api-1.4.jar
Progress (3): 152/189 kB | 66/168 kB | 33/38 kBProgress (3): 156/189 kB | 66/168 kB | 33/38 kBProgress (3): 160/189 kB | 66/168 kB | 33/38 kBProgress (3): 164/189 kB | 66/168 kB | 33/38 kBProgress (3): 168/189 kB | 66/168 kB | 33/38 kBProgress (4): 168/189 kB | 66/168 kB | 33/38 kB | 2.7/11 kBProgress (4): 168/189 kB | 70/168 kB | 33/38 kB | 2.7/11 kBProgress (4): 168/189 kB | 74/168 kB | 33/38 kB | 2.7/11 kBProgress (4): 168/189 kB | 78/168 kB | 33/38 kB | 2.7/11 kBProgress (4): 168/189 kB | 82/168 kB | 33/38 kB | 2.7/11 kBProgress (4): 168/189 kB | 86/168 kB | 33/38 kB | 2.7/11 kBProgress (4): 168/189 kB | 90/168 kB | 33/38 kB | 2.7/11 kBProgress (4): 168/189 kB | 94/168 kB | 33/38 kB | 2.7/11 kBProgress (4): 168/189 kB | 98/168 kB | 33/38 kB | 2.7/11 kBProgress (4): 168/189 kB | 102/168 kB | 33/38 kB | 2.7/11 kBProgress (4): 168/189 kB | 106/168 kB | 33/38 kB | 2.7/11 kBProgress (4): 168/189 kB | 111/168 kB | 33/38 kB | 2.7/11 kBProgress (4): 168/189 kB | 115/168 kB | 33/38 kB | 2.7/11 kBProgress (4): 168/189 kB | 115/168 kB | 37/38 kB | 2.7/11 kBProgress (4): 168/189 kB | 115/168 kB | 38 kB | 2.7/11 kB   Progress (4): 168/189 kB | 115/168 kB | 38 kB | 5.5/11 kBProgress (4): 168/189 kB | 115/168 kB | 38 kB | 8.2/11 kBProgress (4): 168/189 kB | 115/168 kB | 38 kB | 11/11 kB Progress (4): 168/189 kB | 115/168 kB | 38 kB | 11 kB   Progress (4): 172/189 kB | 115/168 kB | 38 kB | 11 kBProgress (4): 176/189 kB | 115/168 kB | 38 kB | 11 kBProgress (4): 180/189 kB | 115/168 kB | 38 kB | 11 kBProgress (4): 184/189 kB | 115/168 kB | 38 kB | 11 kBProgress (4): 188/189 kB | 115/168 kB | 38 kB | 11 kBProgress (4): 189 kB | 115/168 kB | 38 kB | 11 kB                                                     Downloaded from central: https://repo.maven.apache.org/maven2/commons-logging/commons-logging/1.0.4/commons-logging-1.0.4.jar (38 kB at 107 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/doxia/doxia-site-renderer/1.4/doxia-site-renderer-1.4.jar
Progress (3): 189 kB | 119/168 kB | 11 kBProgress (3): 189 kB | 123/168 kB | 11 kBProgress (3): 189 kB | 127/168 kB | 11 kBProgress (3): 189 kB | 131/168 kB | 11 kBProgress (3): 189 kB | 135/168 kB | 11 kBProgress (4): 189 kB | 135/168 kB | 11 kB | 4.1/53 kBProgress (4): 189 kB | 135/168 kB | 11 kB | 8.2/53 kBProgress (4): 189 kB | 135/168 kB | 11 kB | 12/53 kB Progress (4): 189 kB | 135/168 kB | 11 kB | 16/53 kBProgress (4): 189 kB | 135/168 kB | 11 kB | 20/53 kBProgress (4): 189 kB | 135/168 kB | 11 kB | 24/53 kBProgress (4): 189 kB | 135/168 kB | 11 kB | 28/53 kBProgress (4): 189 kB | 135/168 kB | 11 kB | 32/53 kB                                                    Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/doxia/doxia-logging-api/1.4/doxia-logging-api-1.4.jar (11 kB at 31 kB/s)
Downloaded from central: https://repo.maven.apache.org/maven2/commons-beanutils/commons-beanutils/1.7.0/commons-beanutils-1.7.0.jar (189 kB at 511 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/doxia/doxia-decoration-model/1.4/doxia-decoration-model-1.4.jar
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/doxia/doxia-module-xhtml/1.4/doxia-module-xhtml-1.4.jar
Progress (2): 139/168 kB | 32/53 kBProgress (2): 143/168 kB | 32/53 kBProgress (2): 147/168 kB | 32/53 kBProgress (2): 152/168 kB | 32/53 kBProgress (2): 156/168 kB | 32/53 kBProgress (2): 160/168 kB | 32/53 kBProgress (2): 164/168 kB | 32/53 kBProgress (2): 168/168 kB | 32/53 kBProgress (2): 168/168 kB | 36/53 kBProgress (2): 168/168 kB | 40/53 kBProgress (2): 168/168 kB | 45/53 kBProgress (2): 168/168 kB | 49/53 kBProgress (2): 168/168 kB | 53/53 kBProgress (2): 168/168 kB | 53 kB   Progress (3): 168/168 kB | 53 kB | 4.1/61 kBProgress (3): 168/168 kB | 53 kB | 8.2/61 kBProgress (3): 168/168 kB | 53 kB | 12/61 kB Progress (3): 168/168 kB | 53 kB | 16/61 kBProgress (4): 168/168 kB | 53 kB | 16/61 kB | 4.1/15 kBProgress (4): 168/168 kB | 53 kB | 16/61 kB | 8.2/15 kBProgress (4): 168/168 kB | 53 kB | 16/61 kB | 12/15 kB Progress (4): 168/168 kB | 53 kB | 16/61 kB | 15 kB   Progress (4): 168/168 kB | 53 kB | 20/61 kB | 15 kBProgress (4): 168/168 kB | 53 kB | 25/61 kB | 15 kBProgress (4): 168/168 kB | 53 kB | 29/61 kB | 15 kBProgress (4): 168/168 kB | 53 kB | 33/61 kB | 15 kB                                                   Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/doxia/doxia-site-renderer/1.4/doxia-site-renderer-1.4.jar (53 kB at 136 kB/s)
Progress (3): 168/168 kB | 37/61 kB | 15 kBProgress (3): 168/168 kB | 41/61 kB | 15 kBProgress (3): 168/168 kB | 45/61 kB | 15 kBProgress (3): 168 kB | 45/61 kB | 15 kB                                           Downloaded from central: https://repo.maven.apache.org/maven2/xerces/xercesImpl/2.9.1/xercesImpl-2.9.1.jar (0 B at 0 B/s)
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/doxia/doxia-module-xhtml/1.4/doxia-module-xhtml-1.4.jar (15 kB at 38 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-i18n/1.0-beta-7/plexus-i18n-1.0-beta-7.jar
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/doxia/doxia-module-fml/1.4/doxia-module-fml-1.4.jar
Downloaded from central: https://repo.maven.apache.org/maven2/commons-digester/commons-digester/1.6/commons-digester-1.6.jar (168 kB at 416 kB/s)
Progress (1): 49/61 kBProgress (1): 53/61 kBProgress (1): 57/61 kBProgress (1): 61 kB                      Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-container-default/1.0-alpha-30/plexus-container-default-1.0-alpha-30.jar
Downloading from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-velocity/1.1.7/plexus-velocity-1.1.7.jar
Progress (2): 61 kB | 4.1/38 kBProgress (2): 61 kB | 8.2/38 kBProgress (2): 61 kB | 12/38 kB Progress (2): 61 kB | 16/38 kBProgress (2): 61 kB | 20/38 kBProgress (2): 61 kB | 25/38 kBProgress (2): 61 kB | 29/38 kBProgress (2): 61 kB | 33/38 kBProgress (2): 61 kB | 37/38 kBProgress (2): 61 kB | 38 kB   Progress (3): 61 kB | 38 kB | 2.7/237 kBProgress (3): 61 kB | 38 kB | 5.5/237 kBProgress (3): 61 kB | 38 kB | 8.2/237 kBProgress (3): 61 kB | 38 kB | 11/237 kB Progress (3): 61 kB | 38 kB | 14/237 kBProgress (3): 61 kB | 38 kB | 16/237 kBProgress (3): 61 kB | 38 kB | 20/237 kBProgress (3): 61 kB | 38 kB | 24/237 kBProgress (3): 61 kB | 38 kB | 28/237 kBProgress (3): 61 kB | 38 kB | 32/237 kBProgress (4): 61 kB | 38 kB | 32/237 kB | 4.1/7.7 kBProgress (4): 61 kB | 38 kB | 32/237 kB | 7.7 kB    Progress (5): 61 kB | 38 kB | 32/237 kB | 7.7 kB | 4.1/11 kBProgress (5): 61 kB | 38 kB | 32/237 kB | 7.7 kB | 8.2/11 kBProgress (5): 61 kB | 38 kB | 32/237 kB | 7.7 kB | 11 kB                                                            Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/doxia/doxia-decoration-model/1.4/doxia-decoration-model-1.4.jar (61 kB at 144 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/velocity/velocity/1.5/velocity-1.5.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/doxia/doxia-module-fml/1.4/doxia-module-fml-1.4.jar (38 kB at 89 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/oro/oro/2.0.8/oro-2.0.8.jar
Progress (3): 36/237 kB | 7.7 kB | 11 kBProgress (3): 40/237 kB | 7.7 kB | 11 kBProgress (3): 45/237 kB | 7.7 kB | 11 kBProgress (3): 49/237 kB | 7.7 kB | 11 kBProgress (3): 53/237 kB | 7.7 kB | 11 kBProgress (3): 57/237 kB | 7.7 kB | 11 kBProgress (3): 61/237 kB | 7.7 kB | 11 kBProgress (3): 65/237 kB | 7.7 kB | 11 kB                                        Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-i18n/1.0-beta-7/plexus-i18n-1.0-beta-7.jar (11 kB at 24 kB/s)
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-velocity/1.1.7/plexus-velocity-1.1.7.jar (7.7 kB at 18 kB/s)
Progress (2): 65/237 kB | 4.1/392 kBProgress (2): 65/237 kB | 8.2/392 kBProgress (2): 65/237 kB | 12/392 kB Progress (2): 65/237 kB | 16/392 kB                                   Downloading from central: https://repo.maven.apache.org/maven2/org/apache/velocity/velocity-tools/2.0/velocity-tools-2.0.jar
Progress (3): 65/237 kB | 16/392 kB | 4.1/65 kB                                               Downloading from central: https://repo.maven.apache.org/maven2/commons-chain/commons-chain/1.1/commons-chain-1.1.jar
Progress (3): 65/237 kB | 20/392 kB | 4.1/65 kBProgress (3): 65/237 kB | 24/392 kB | 4.1/65 kBProgress (3): 65/237 kB | 28/392 kB | 4.1/65 kBProgress (3): 65/237 kB | 32/392 kB | 4.1/65 kBProgress (3): 65/237 kB | 36/392 kB | 4.1/65 kBProgress (3): 65/237 kB | 40/392 kB | 4.1/65 kBProgress (3): 65/237 kB | 45/392 kB | 4.1/65 kBProgress (3): 65/237 kB | 49/392 kB | 4.1/65 kBProgress (3): 65/237 kB | 53/392 kB | 4.1/65 kBProgress (3): 65/237 kB | 57/392 kB | 4.1/65 kBProgress (3): 65/237 kB | 61/392 kB | 4.1/65 kBProgress (3): 65/237 kB | 65/392 kB | 4.1/65 kBProgress (3): 65/237 kB | 65/392 kB | 8.2/65 kBProgress (3): 65/237 kB | 65/392 kB | 12/65 kB Progress (3): 65/237 kB | 65/392 kB | 16/65 kBProgress (3): 65/237 kB | 65/392 kB | 20/65 kBProgress (3): 65/237 kB | 65/392 kB | 25/65 kBProgress (3): 65/237 kB | 65/392 kB | 29/65 kBProgress (3): 65/237 kB | 65/392 kB | 33/65 kBProgress (3): 65/237 kB | 65/392 kB | 37/65 kBProgress (3): 65/237 kB | 65/392 kB | 41/65 kBProgress (3): 65/237 kB | 65/392 kB | 45/65 kBProgress (3): 65/237 kB | 65/392 kB | 49/65 kBProgress (3): 65/237 kB | 65/392 kB | 53/65 kBProgress (3): 65/237 kB | 65/392 kB | 57/65 kBProgress (3): 65/237 kB | 65/392 kB | 61/65 kBProgress (3): 65/237 kB | 65/392 kB | 65 kB   Progress (4): 65/237 kB | 65/392 kB | 65 kB | 4.1/347 kBProgress (4): 65/237 kB | 65/392 kB | 65 kB | 8.2/347 kBProgress (4): 65/237 kB | 65/392 kB | 65 kB | 12/347 kB Progress (4): 65/237 kB | 65/392 kB | 65 kB | 16/347 kBProgress (4): 65/237 kB | 65/392 kB | 65 kB | 20/347 kBProgress (4): 65/237 kB | 65/392 kB | 65 kB | 24/347 kBProgress (4): 65/237 kB | 65/392 kB | 65 kB | 28/347 kBProgress (4): 65/237 kB | 65/392 kB | 65 kB | 32/347 kBProgress (4): 65/237 kB | 65/392 kB | 65 kB | 36/347 kBProgress (4): 65/237 kB | 65/392 kB | 65 kB | 40/347 kBProgress (4): 65/237 kB | 65/392 kB | 65 kB | 45/347 kBProgress (4): 65/237 kB | 65/392 kB | 65 kB | 49/347 kBProgress (5): 65/237 kB | 65/392 kB | 65 kB | 49/347 kB | 4.1/90 kBProgress (5): 65/237 kB | 65/392 kB | 65 kB | 49/347 kB | 8.2/90 kBProgress (5): 65/237 kB | 65/392 kB | 65 kB | 49/347 kB | 12/90 kB Progress (5): 65/237 kB | 65/392 kB | 65 kB | 49/347 kB | 16/90 kBProgress (5): 65/237 kB | 65/392 kB | 65 kB | 49/347 kB | 20/90 kBProgress (5): 65/237 kB | 65/392 kB | 65 kB | 49/347 kB | 25/90 kBProgress (5): 65/237 kB | 65/392 kB | 65 kB | 49/347 kB | 29/90 kBProgress (5): 65/237 kB | 65/392 kB | 65 kB | 49/347 kB | 33/90 kBProgress (5): 65/237 kB | 65/392 kB | 65 kB | 49/347 kB | 37/90 kBProgress (5): 65/237 kB | 65/392 kB | 65 kB | 49/347 kB | 41/90 kBProgress (5): 65/237 kB | 65/392 kB | 65 kB | 49/347 kB | 45/90 kBProgress (5): 65/237 kB | 65/392 kB | 65 kB | 49/347 kB | 49/90 kBProgress (5): 65/237 kB | 65/392 kB | 65 kB | 49/347 kB | 53/90 kBProgress (5): 65/237 kB | 65/392 kB | 65 kB | 49/347 kB | 57/90 kBProgress (5): 65/237 kB | 65/392 kB | 65 kB | 49/347 kB | 61/90 kBProgress (5): 65/237 kB | 65/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 69/237 kB | 65/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 73/237 kB | 65/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 77/237 kB | 65/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 81/237 kB | 65/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 86/237 kB | 65/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 90/237 kB | 65/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 94/237 kB | 65/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 98/237 kB | 65/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 102/237 kB | 65/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 106/237 kB | 65/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 110/237 kB | 65/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 114/237 kB | 65/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 118/237 kB | 65/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 122/237 kB | 65/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 126/237 kB | 65/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 131/237 kB | 65/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 135/237 kB | 65/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 139/237 kB | 65/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 139/237 kB | 69/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 139/237 kB | 73/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 139/237 kB | 77/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 139/237 kB | 81/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 139/237 kB | 86/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 139/237 kB | 90/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 139/237 kB | 94/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 139/237 kB | 98/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 139/237 kB | 102/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 139/237 kB | 106/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 139/237 kB | 110/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 139/237 kB | 114/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 139/237 kB | 118/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 139/237 kB | 122/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 139/237 kB | 126/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 139/237 kB | 131/392 kB | 65 kB | 49/347 kB | 66/90 kBProgress (5): 139/237 kB | 131/392 kB | 65 kB | 49/347 kB | 70/90 kBProgress (5): 139/237 kB | 131/392 kB | 65 kB | 53/347 kB | 70/90 kBProgress (5): 139/237 kB | 131/392 kB | 65 kB | 57/347 kB | 70/90 kBProgress (5): 139/237 kB | 131/392 kB | 65 kB | 61/347 kB | 70/90 kBProgress (5): 139/237 kB | 131/392 kB | 65 kB | 65/347 kB | 70/90 kBProgress (5): 139/237 kB | 131/392 kB | 65 kB | 69/347 kB | 70/90 kBProgress (5): 139/237 kB | 131/392 kB | 65 kB | 73/347 kB | 70/90 kBProgress (5): 139/237 kB | 131/392 kB | 65 kB | 77/347 kB | 70/90 kBProgress (5): 139/237 kB | 131/392 kB | 65 kB | 81/347 kB | 70/90 kBProgress (5): 139/237 kB | 131/392 kB | 65 kB | 86/347 kB | 70/90 kB                                                                    Downloaded from central: https://repo.maven.apache.org/maven2/oro/oro/2.0.8/oro-2.0.8.jar (65 kB at 133 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/dom4j/dom4j/1.1/dom4j-1.1.jar
Progress (4): 139/237 kB | 131/392 kB | 86/347 kB | 74/90 kBProgress (4): 139/237 kB | 131/392 kB | 86/347 kB | 78/90 kBProgress (4): 139/237 kB | 131/392 kB | 86/347 kB | 82/90 kBProgress (4): 139/237 kB | 131/392 kB | 86/347 kB | 86/90 kBProgress (4): 139/237 kB | 131/392 kB | 86/347 kB | 90 kB   Progress (4): 139/237 kB | 131/392 kB | 90/347 kB | 90 kBProgress (4): 139/237 kB | 131/392 kB | 94/347 kB | 90 kBProgress (4): 139/237 kB | 131/392 kB | 98/347 kB | 90 kBProgress (4): 139/237 kB | 131/392 kB | 102/347 kB | 90 kBProgress (4): 139/237 kB | 131/392 kB | 106/347 kB | 90 kBProgress (4): 139/237 kB | 131/392 kB | 110/347 kB | 90 kBProgress (4): 139/237 kB | 131/392 kB | 114/347 kB | 90 kB                                                          Downloaded from central: https://repo.maven.apache.org/maven2/commons-chain/commons-chain/1.1/commons-chain-1.1.jar (90 kB at 181 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/sslext/sslext/1.2-0/sslext-1.2-0.jar
Progress (3): 143/237 kB | 131/392 kB | 114/347 kBProgress (3): 147/237 kB | 131/392 kB | 114/347 kBProgress (3): 151/237 kB | 131/392 kB | 114/347 kBProgress (3): 155/237 kB | 131/392 kB | 114/347 kBProgress (3): 159/237 kB | 131/392 kB | 114/347 kBProgress (3): 163/237 kB | 131/392 kB | 114/347 kBProgress (3): 167/237 kB | 131/392 kB | 114/347 kBProgress (3): 172/237 kB | 131/392 kB | 114/347 kBProgress (3): 176/237 kB | 131/392 kB | 114/347 kBProgress (3): 180/237 kB | 131/392 kB | 114/347 kBProgress (3): 184/237 kB | 131/392 kB | 114/347 kBProgress (3): 188/237 kB | 131/392 kB | 114/347 kBProgress (3): 192/237 kB | 131/392 kB | 114/347 kBProgress (3): 196/237 kB | 131/392 kB | 114/347 kBProgress (3): 200/237 kB | 131/392 kB | 114/347 kBProgress (3): 204/237 kB | 131/392 kB | 114/347 kBProgress (3): 204/237 kB | 131/392 kB | 118/347 kBProgress (3): 204/237 kB | 131/392 kB | 122/347 kBProgress (3): 204/237 kB | 131/392 kB | 126/347 kBProgress (3): 204/237 kB | 131/392 kB | 131/347 kBProgress (3): 204/237 kB | 131/392 kB | 135/347 kBProgress (3): 204/237 kB | 131/392 kB | 139/347 kBProgress (3): 204/237 kB | 131/392 kB | 143/347 kBProgress (3): 204/237 kB | 131/392 kB | 147/347 kBProgress (3): 204/237 kB | 131/392 kB | 151/347 kBProgress (3): 204/237 kB | 131/392 kB | 155/347 kBProgress (3): 204/237 kB | 131/392 kB | 159/347 kBProgress (3): 204/237 kB | 131/392 kB | 163/347 kBProgress (3): 204/237 kB | 131/392 kB | 167/347 kBProgress (3): 204/237 kB | 131/392 kB | 172/347 kBProgress (3): 204/237 kB | 131/392 kB | 176/347 kBProgress (3): 204/237 kB | 131/392 kB | 180/347 kBProgress (3): 204/237 kB | 131/392 kB | 184/347 kBProgress (3): 204/237 kB | 131/392 kB | 188/347 kBProgress (3): 204/237 kB | 131/392 kB | 192/347 kBProgress (3): 204/237 kB | 131/392 kB | 196/347 kBProgress (3): 204/237 kB | 135/392 kB | 196/347 kBProgress (3): 204/237 kB | 139/392 kB | 196/347 kBProgress (3): 204/237 kB | 143/392 kB | 196/347 kBProgress (3): 204/237 kB | 147/392 kB | 196/347 kBProgress (3): 204/237 kB | 151/392 kB | 196/347 kBProgress (3): 204/237 kB | 155/392 kB | 196/347 kBProgress (3): 204/237 kB | 159/392 kB | 196/347 kBProgress (3): 204/237 kB | 163/392 kB | 196/347 kBProgress (3): 204/237 kB | 167/392 kB | 196/347 kBProgress (3): 204/237 kB | 172/392 kB | 196/347 kBProgress (3): 204/237 kB | 176/392 kB | 196/347 kBProgress (3): 204/237 kB | 180/392 kB | 196/347 kBProgress (3): 204/237 kB | 184/392 kB | 196/347 kBProgress (3): 204/237 kB | 188/392 kB | 196/347 kBProgress (3): 204/237 kB | 192/392 kB | 196/347 kBProgress (3): 204/237 kB | 196/392 kB | 196/347 kBProgress (4): 204/237 kB | 196/392 kB | 196/347 kB | 4.1/26 kBProgress (4): 204/237 kB | 196/392 kB | 196/347 kB | 8.2/26 kBProgress (4): 204/237 kB | 196/392 kB | 196/347 kB | 12/26 kB Progress (4): 204/237 kB | 196/392 kB | 196/347 kB | 16/26 kBProgress (4): 204/237 kB | 196/392 kB | 196/347 kB | 20/26 kBProgress (4): 204/237 kB | 196/392 kB | 196/347 kB | 25/26 kBProgress (4): 204/237 kB | 196/392 kB | 196/347 kB | 26 kB   Progress (4): 204/237 kB | 200/392 kB | 196/347 kB | 26 kBProgress (4): 204/237 kB | 204/392 kB | 196/347 kB | 26 kBProgress (4): 204/237 kB | 208/392 kB | 196/347 kB | 26 kBProgress (4): 204/237 kB | 212/392 kB | 196/347 kB | 26 kBProgress (4): 204/237 kB | 217/392 kB | 196/347 kB | 26 kBProgress (4): 204/237 kB | 221/392 kB | 196/347 kB | 26 kBProgress (4): 204/237 kB | 225/392 kB | 196/347 kB | 26 kBProgress (4): 204/237 kB | 229/392 kB | 196/347 kB | 26 kBProgress (4): 204/237 kB | 233/392 kB | 196/347 kB | 26 kBProgress (4): 204/237 kB | 237/392 kB | 196/347 kB | 26 kBProgress (4): 204/237 kB | 241/392 kB | 196/347 kB | 26 kBProgress (4): 204/237 kB | 245/392 kB | 196/347 kB | 26 kBProgress (4): 208/237 kB | 245/392 kB | 196/347 kB | 26 kBProgress (4): 212/237 kB | 245/392 kB | 196/347 kB | 26 kBProgress (4): 217/237 kB | 245/392 kB | 196/347 kB | 26 kBProgress (4): 221/237 kB | 245/392 kB | 196/347 kB | 26 kBProgress (4): 225/237 kB | 245/392 kB | 196/347 kB | 26 kBProgress (4): 229/237 kB | 245/392 kB | 196/347 kB | 26 kBProgress (4): 233/237 kB | 245/392 kB | 196/347 kB | 26 kBProgress (4): 237/237 kB | 245/392 kB | 196/347 kB | 26 kBProgress (4): 237 kB | 245/392 kB | 196/347 kB | 26 kB                                                          Downloaded from central: https://repo.maven.apache.org/maven2/sslext/sslext/1.2-0/sslext-1.2-0.jar (26 kB at 48 kB/s)
Progress (3): 237 kB | 245/392 kB | 200/347 kBProgress (3): 237 kB | 245/392 kB | 204/347 kBProgress (3): 237 kB | 245/392 kB | 208/347 kBProgress (3): 237 kB | 245/392 kB | 212/347 kBProgress (3): 237 kB | 245/392 kB | 217/347 kBProgress (3): 237 kB | 245/392 kB | 221/347 kBProgress (3): 237 kB | 245/392 kB | 225/347 kBProgress (3): 237 kB | 245/392 kB | 229/347 kB                                              Downloading from central: https://repo.maven.apache.org/maven2/org/apache/struts/struts-core/1.3.8/struts-core-1.3.8.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/codehaus/plexus/plexus-container-default/1.0-alpha-30/plexus-container-default-1.0-alpha-30.jar (237 kB at 416 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/antlr/antlr/2.7.2/antlr-2.7.2.jar
Progress (2): 249/392 kB | 229/347 kBProgress (2): 253/392 kB | 229/347 kBProgress (2): 258/392 kB | 229/347 kBProgress (2): 262/392 kB | 229/347 kBProgress (2): 266/392 kB | 229/347 kBProgress (2): 270/392 kB | 229/347 kBProgress (2): 274/392 kB | 229/347 kBProgress (2): 278/392 kB | 229/347 kBProgress (2): 282/392 kB | 229/347 kBProgress (2): 286/392 kB | 229/347 kBProgress (2): 290/392 kB | 229/347 kBProgress (2): 294/392 kB | 229/347 kBProgress (2): 294/392 kB | 233/347 kBProgress (2): 294/392 kB | 237/347 kBProgress (2): 294/392 kB | 241/347 kBProgress (2): 294/392 kB | 245/347 kBProgress (2): 294/392 kB | 249/347 kBProgress (3): 294/392 kB | 249/347 kB | 4.1/329 kBProgress (3): 294/392 kB | 249/347 kB | 8.2/329 kBProgress (3): 294/392 kB | 249/347 kB | 12/329 kB Progress (3): 294/392 kB | 249/347 kB | 16/329 kBProgress (3): 294/392 kB | 249/347 kB | 20/329 kBProgress (3): 294/392 kB | 249/347 kB | 24/329 kBProgress (3): 294/392 kB | 249/347 kB | 28/329 kBProgress (3): 294/392 kB | 249/347 kB | 32/329 kBProgress (3): 294/392 kB | 253/347 kB | 32/329 kBProgress (3): 294/392 kB | 258/347 kB | 32/329 kBProgress (3): 294/392 kB | 262/347 kB | 32/329 kBProgress (4): 294/392 kB | 262/347 kB | 32/329 kB | 4.1/358 kBProgress (4): 294/392 kB | 262/347 kB | 32/329 kB | 8.2/358 kBProgress (4): 294/392 kB | 262/347 kB | 32/329 kB | 12/358 kB Progress (4): 294/392 kB | 262/347 kB | 32/329 kB | 16/358 kBProgress (4): 294/392 kB | 262/347 kB | 32/329 kB | 20/358 kBProgress (4): 294/392 kB | 262/347 kB | 32/329 kB | 24/358 kBProgress (4): 294/392 kB | 262/347 kB | 32/329 kB | 28/358 kBProgress (4): 294/392 kB | 262/347 kB | 32/329 kB | 32/358 kBProgress (4): 294/392 kB | 266/347 kB | 32/329 kB | 32/358 kBProgress (4): 294/392 kB | 270/347 kB | 32/329 kB | 32/358 kBProgress (4): 294/392 kB | 274/347 kB | 32/329 kB | 32/358 kBProgress (4): 294/392 kB | 278/347 kB | 32/329 kB | 32/358 kBProgress (4): 294/392 kB | 282/347 kB | 32/329 kB | 32/358 kBProgress (4): 294/392 kB | 286/347 kB | 32/329 kB | 32/358 kBProgress (4): 294/392 kB | 290/347 kB | 32/329 kB | 32/358 kBProgress (4): 294/392 kB | 294/347 kB | 32/329 kB | 32/358 kBProgress (4): 294/392 kB | 299/347 kB | 32/329 kB | 32/358 kBProgress (4): 294/392 kB | 303/347 kB | 32/329 kB | 32/358 kBProgress (4): 294/392 kB | 307/347 kB | 32/329 kB | 32/358 kBProgress (4): 294/392 kB | 311/347 kB | 32/329 kB | 32/358 kBProgress (4): 294/392 kB | 311/347 kB | 36/329 kB | 32/358 kBProgress (4): 294/392 kB | 311/347 kB | 40/329 kB | 32/358 kBProgress (4): 294/392 kB | 311/347 kB | 45/329 kB | 32/358 kBProgress (4): 294/392 kB | 311/347 kB | 49/329 kB | 32/358 kBProgress (4): 294/392 kB | 311/347 kB | 53/329 kB | 32/358 kBProgress (4): 294/392 kB | 311/347 kB | 57/329 kB | 32/358 kBProgress (4): 294/392 kB | 311/347 kB | 61/329 kB | 32/358 kBProgress (4): 294/392 kB | 311/347 kB | 65/329 kB | 32/358 kBProgress (4): 294/392 kB | 311/347 kB | 69/329 kB | 32/358 kBProgress (4): 294/392 kB | 311/347 kB | 73/329 kB | 32/358 kBProgress (4): 294/392 kB | 311/347 kB | 77/329 kB | 32/358 kBProgress (4): 294/392 kB | 311/347 kB | 81/329 kB | 32/358 kBProgress (4): 299/392 kB | 311/347 kB | 81/329 kB | 32/358 kBProgress (4): 303/392 kB | 311/347 kB | 81/329 kB | 32/358 kBProgress (4): 307/392 kB | 311/347 kB | 81/329 kB | 32/358 kBProgress (4): 311/392 kB | 311/347 kB | 81/329 kB | 32/358 kBProgress (4): 315/392 kB | 311/347 kB | 81/329 kB | 32/358 kBProgress (4): 319/392 kB | 311/347 kB | 81/329 kB | 32/358 kBProgress (4): 323/392 kB | 311/347 kB | 81/329 kB | 32/358 kBProgress (4): 327/392 kB | 311/347 kB | 81/329 kB | 32/358 kBProgress (4): 331/392 kB | 311/347 kB | 81/329 kB | 32/358 kBProgress (4): 335/392 kB | 311/347 kB | 81/329 kB | 32/358 kBProgress (4): 339/392 kB | 311/347 kB | 81/329 kB | 32/358 kBProgress (4): 344/392 kB | 311/347 kB | 81/329 kB | 32/358 kBProgress (4): 344/392 kB | 311/347 kB | 81/329 kB | 36/358 kBProgress (4): 344/392 kB | 311/347 kB | 81/329 kB | 40/358 kBProgress (4): 344/392 kB | 311/347 kB | 81/329 kB | 45/358 kBProgress (4): 344/392 kB | 311/347 kB | 81/329 kB | 49/358 kBProgress (4): 344/392 kB | 315/347 kB | 81/329 kB | 49/358 kBProgress (4): 344/392 kB | 319/347 kB | 81/329 kB | 49/358 kBProgress (4): 344/392 kB | 323/347 kB | 81/329 kB | 49/358 kB                                                             Downloaded from central: https://repo.maven.apache.org/maven2/dom4j/dom4j/1.1/dom4j-1.1.jar (0 B at 0 B/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/struts/struts-taglib/1.3.8/struts-taglib-1.3.8.jar
Progress (4): 344/392 kB | 323/347 kB | 81/329 kB | 53/358 kBProgress (4): 344/392 kB | 323/347 kB | 81/329 kB | 57/358 kBProgress (4): 344/392 kB | 323/347 kB | 81/329 kB | 61/358 kBProgress (4): 344/392 kB | 323/347 kB | 81/329 kB | 65/358 kBProgress (4): 344/392 kB | 323/347 kB | 86/329 kB | 65/358 kBProgress (4): 344/392 kB | 323/347 kB | 90/329 kB | 65/358 kBProgress (4): 344/392 kB | 323/347 kB | 94/329 kB | 65/358 kBProgress (4): 344/392 kB | 327/347 kB | 94/329 kB | 65/358 kBProgress (4): 344/392 kB | 327/347 kB | 98/329 kB | 65/358 kBProgress (4): 344/392 kB | 327/347 kB | 102/329 kB | 65/358 kBProgress (4): 344/392 kB | 327/347 kB | 106/329 kB | 65/358 kBProgress (4): 344/392 kB | 327/347 kB | 110/329 kB | 65/358 kBProgress (4): 344/392 kB | 327/347 kB | 114/329 kB | 65/358 kBProgress (5): 344/392 kB | 327/347 kB | 114/329 kB | 65/358 kB | 4.1/252 kBProgress (5): 344/392 kB | 327/347 kB | 118/329 kB | 65/358 kB | 4.1/252 kBProgress (5): 344/392 kB | 327/347 kB | 118/329 kB | 65/358 kB | 8.2/252 kBProgress (5): 344/392 kB | 327/347 kB | 122/329 kB | 65/358 kB | 8.2/252 kBProgress (5): 344/392 kB | 327/347 kB | 122/329 kB | 65/358 kB | 12/252 kB Progress (5): 344/392 kB | 327/347 kB | 126/329 kB | 65/358 kB | 12/252 kBProgress (5): 344/392 kB | 327/347 kB | 126/329 kB | 65/358 kB | 16/252 kBProgress (5): 344/392 kB | 327/347 kB | 131/329 kB | 65/358 kB | 16/252 kBProgress (5): 344/392 kB | 327/347 kB | 131/329 kB | 69/358 kB | 16/252 kBProgress (5): 344/392 kB | 327/347 kB | 131/329 kB | 73/358 kB | 16/252 kBProgress (5): 344/392 kB | 327/347 kB | 131/329 kB | 77/358 kB | 16/252 kBProgress (5): 344/392 kB | 327/347 kB | 131/329 kB | 81/358 kB | 16/252 kBProgress (5): 344/392 kB | 327/347 kB | 131/329 kB | 81/358 kB | 20/252 kBProgress (5): 344/392 kB | 327/347 kB | 131/329 kB | 81/358 kB | 24/252 kBProgress (5): 344/392 kB | 327/347 kB | 131/329 kB | 81/358 kB | 28/252 kBProgress (5): 344/392 kB | 327/347 kB | 131/329 kB | 81/358 kB | 32/252 kBProgress (5): 344/392 kB | 327/347 kB | 131/329 kB | 86/358 kB | 32/252 kBProgress (5): 344/392 kB | 327/347 kB | 131/329 kB | 90/358 kB | 32/252 kBProgress (5): 344/392 kB | 327/347 kB | 131/329 kB | 94/358 kB | 32/252 kBProgress (5): 344/392 kB | 327/347 kB | 131/329 kB | 98/358 kB | 32/252 kBProgress (5): 344/392 kB | 327/347 kB | 131/329 kB | 98/358 kB | 36/252 kBProgress (5): 344/392 kB | 327/347 kB | 131/329 kB | 98/358 kB | 40/252 kBProgress (5): 344/392 kB | 327/347 kB | 131/329 kB | 98/358 kB | 45/252 kBProgress (5): 344/392 kB | 327/347 kB | 131/329 kB | 98/358 kB | 49/252 kBProgress (5): 344/392 kB | 331/347 kB | 131/329 kB | 98/358 kB | 49/252 kBProgress (5): 344/392 kB | 335/347 kB | 131/329 kB | 98/358 kB | 49/252 kBProgress (5): 344/392 kB | 339/347 kB | 131/329 kB | 98/358 kB | 49/252 kBProgress (5): 344/392 kB | 344/347 kB | 131/329 kB | 98/358 kB | 49/252 kBProgress (5): 344/392 kB | 347 kB | 131/329 kB | 98/358 kB | 49/252 kB    Progress (5): 348/392 kB | 347 kB | 131/329 kB | 98/358 kB | 49/252 kBProgress (5): 352/392 kB | 347 kB | 131/329 kB | 98/358 kB | 49/252 kBProgress (5): 356/392 kB | 347 kB | 131/329 kB | 98/358 kB | 49/252 kBProgress (5): 360/392 kB | 347 kB | 131/329 kB | 98/358 kB | 49/252 kBProgress (5): 364/392 kB | 347 kB | 131/329 kB | 98/358 kB | 49/252 kBProgress (5): 368/392 kB | 347 kB | 131/329 kB | 98/358 kB | 49/252 kBProgress (5): 372/392 kB | 347 kB | 131/329 kB | 98/358 kB | 49/252 kBProgress (5): 376/392 kB | 347 kB | 131/329 kB | 98/358 kB | 49/252 kBProgress (5): 380/392 kB | 347 kB | 131/329 kB | 98/358 kB | 49/252 kBProgress (5): 385/392 kB | 347 kB | 131/329 kB | 98/358 kB | 49/252 kBProgress (5): 389/392 kB | 347 kB | 131/329 kB | 98/358 kB | 49/252 kBProgress (5): 392 kB | 347 kB | 131/329 kB | 98/358 kB | 49/252 kB    Progress (5): 392 kB | 347 kB | 131/329 kB | 102/358 kB | 49/252 kBProgress (5): 392 kB | 347 kB | 131/329 kB | 106/358 kB | 49/252 kBProgress (5): 392 kB | 347 kB | 131/329 kB | 110/358 kB | 49/252 kBProgress (5): 392 kB | 347 kB | 131/329 kB | 114/358 kB | 49/252 kBProgress (5): 392 kB | 347 kB | 131/329 kB | 118/358 kB | 49/252 kBProgress (5): 392 kB | 347 kB | 131/329 kB | 122/358 kB | 49/252 kBProgress (5): 392 kB | 347 kB | 131/329 kB | 126/358 kB | 49/252 kBProgress (5): 392 kB | 347 kB | 131/329 kB | 131/358 kB | 49/252 kBProgress (5): 392 kB | 347 kB | 131/329 kB | 131/358 kB | 53/252 kBProgress (5): 392 kB | 347 kB | 131/329 kB | 131/358 kB | 57/252 kBProgress (5): 392 kB | 347 kB | 131/329 kB | 131/358 kB | 61/252 kBProgress (5): 392 kB | 347 kB | 131/329 kB | 131/358 kB | 65/252 kBProgress (5): 392 kB | 347 kB | 135/329 kB | 131/358 kB | 65/252 kBProgress (5): 392 kB | 347 kB | 139/329 kB | 131/358 kB | 65/252 kBProgress (5): 392 kB | 347 kB | 143/329 kB | 131/358 kB | 65/252 kBProgress (5): 392 kB | 347 kB | 147/329 kB | 131/358 kB | 65/252 kBProgress (5): 392 kB | 347 kB | 147/329 kB | 131/358 kB | 69/252 kBProgress (5): 392 kB | 347 kB | 147/329 kB | 131/358 kB | 73/252 kBProgress (5): 392 kB | 347 kB | 147/329 kB | 131/358 kB | 77/252 kBProgress (5): 392 kB | 347 kB | 147/329 kB | 131/358 kB | 81/252 kBProgress (5): 392 kB | 347 kB | 151/329 kB | 131/358 kB | 81/252 kBProgress (5): 392 kB | 347 kB | 155/329 kB | 131/358 kB | 81/252 kBProgress (5): 392 kB | 347 kB | 159/329 kB | 131/358 kB | 81/252 kBProgress (5): 392 kB | 347 kB | 163/329 kB | 131/358 kB | 81/252 kBProgress (5): 392 kB | 347 kB | 163/329 kB | 131/358 kB | 86/252 kBProgress (5): 392 kB | 347 kB | 163/329 kB | 131/358 kB | 90/252 kBProgress (5): 392 kB | 347 kB | 163/329 kB | 131/358 kB | 94/252 kBProgress (5): 392 kB | 347 kB | 163/329 kB | 131/358 kB | 98/252 kB                                                                   Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/velocity/velocity-tools/2.0/velocity-tools-2.0.jar (347 kB at 529 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/struts/struts-tiles/1.3.8/struts-tiles-1.3.8.jar
Progress (4): 392 kB | 163/329 kB | 131/358 kB | 102/252 kBProgress (4): 392 kB | 163/329 kB | 131/358 kB | 106/252 kBProgress (4): 392 kB | 163/329 kB | 131/358 kB | 110/252 kBProgress (4): 392 kB | 163/329 kB | 131/358 kB | 114/252 kBProgress (4): 392 kB | 167/329 kB | 131/358 kB | 114/252 kBProgress (4): 392 kB | 172/329 kB | 131/358 kB | 114/252 kBProgress (4): 392 kB | 176/329 kB | 131/358 kB | 114/252 kBProgress (4): 392 kB | 180/329 kB | 131/358 kB | 114/252 kBProgress (4): 392 kB | 180/329 kB | 135/358 kB | 114/252 kBProgress (4): 392 kB | 180/329 kB | 139/358 kB | 114/252 kBProgress (4): 392 kB | 180/329 kB | 143/358 kB | 114/252 kBProgress (4): 392 kB | 180/329 kB | 147/358 kB | 114/252 kBProgress (4): 392 kB | 180/329 kB | 151/358 kB | 114/252 kBProgress (4): 392 kB | 180/329 kB | 155/358 kB | 114/252 kBProgress (4): 392 kB | 180/329 kB | 159/358 kB | 114/252 kBProgress (4): 392 kB | 180/329 kB | 163/358 kB | 114/252 kBProgress (4): 392 kB | 180/329 kB | 167/358 kB | 114/252 kBProgress (4): 392 kB | 180/329 kB | 172/358 kB | 114/252 kBProgress (4): 392 kB | 180/329 kB | 176/358 kB | 114/252 kBProgress (4): 392 kB | 180/329 kB | 180/358 kB | 114/252 kBProgress (4): 392 kB | 184/329 kB | 180/358 kB | 114/252 kBProgress (4): 392 kB | 188/329 kB | 180/358 kB | 114/252 kBProgress (4): 392 kB | 192/329 kB | 180/358 kB | 114/252 kBProgress (4): 392 kB | 196/329 kB | 180/358 kB | 114/252 kBProgress (4): 392 kB | 200/329 kB | 180/358 kB | 114/252 kBProgress (4): 392 kB | 204/329 kB | 180/358 kB | 114/252 kBProgress (4): 392 kB | 208/329 kB | 180/358 kB | 114/252 kBProgress (4): 392 kB | 212/329 kB | 180/358 kB | 114/252 kBProgress (4): 392 kB | 217/329 kB | 180/358 kB | 114/252 kBProgress (4): 392 kB | 217/329 kB | 180/358 kB | 118/252 kBProgress (4): 392 kB | 221/329 kB | 180/358 kB | 118/252 kBProgress (4): 392 kB | 221/329 kB | 180/358 kB | 122/252 kBProgress (4): 392 kB | 221/329 kB | 180/358 kB | 126/252 kBProgress (4): 392 kB | 221/329 kB | 180/358 kB | 131/252 kBProgress (4): 392 kB | 221/329 kB | 184/358 kB | 131/252 kBProgress (4): 392 kB | 221/329 kB | 188/358 kB | 131/252 kBProgress (4): 392 kB | 221/329 kB | 188/358 kB | 135/252 kBProgress (4): 392 kB | 221/329 kB | 188/358 kB | 139/252 kBProgress (4): 392 kB | 221/329 kB | 188/358 kB | 143/252 kBProgress (4): 392 kB | 221/329 kB | 188/358 kB | 147/252 kBProgress (4): 392 kB | 221/329 kB | 188/358 kB | 151/252 kBProgress (4): 392 kB | 221/329 kB | 188/358 kB | 155/252 kBProgress (4): 392 kB | 221/329 kB | 188/358 kB | 159/252 kBProgress (4): 392 kB | 221/329 kB | 188/358 kB | 163/252 kBProgress (4): 392 kB | 221/329 kB | 188/358 kB | 167/252 kBProgress (4): 392 kB | 221/329 kB | 188/358 kB | 172/252 kBProgress (4): 392 kB | 221/329 kB | 188/358 kB | 176/252 kBProgress (4): 392 kB | 221/329 kB | 188/358 kB | 180/252 kBProgress (4): 392 kB | 221/329 kB | 188/358 kB | 184/252 kBProgress (4): 392 kB | 221/329 kB | 188/358 kB | 188/252 kBProgress (4): 392 kB | 221/329 kB | 188/358 kB | 192/252 kBProgress (4): 392 kB | 221/329 kB | 188/358 kB | 196/252 kB                                                           Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/velocity/velocity/1.5/velocity-1.5.jar (392 kB at 569 kB/s)
Progress (4): 221/329 kB | 188/358 kB | 196/252 kB | 4.1/120 kB                                                               Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/file-management/1.2.1/file-management-1.2.1.jar
Progress (4): 221/329 kB | 188/358 kB | 196/252 kB | 8.2/120 kBProgress (4): 221/329 kB | 188/358 kB | 196/252 kB | 12/120 kB Progress (4): 221/329 kB | 188/358 kB | 196/252 kB | 16/120 kBProgress (4): 221/329 kB | 188/358 kB | 196/252 kB | 20/120 kBProgress (4): 221/329 kB | 188/358 kB | 196/252 kB | 25/120 kBProgress (4): 221/329 kB | 188/358 kB | 196/252 kB | 29/120 kBProgress (4): 221/329 kB | 188/358 kB | 196/252 kB | 33/120 kBProgress (4): 221/329 kB | 188/358 kB | 196/252 kB | 37/120 kBProgress (4): 221/329 kB | 188/358 kB | 196/252 kB | 41/120 kBProgress (4): 221/329 kB | 188/358 kB | 196/252 kB | 45/120 kBProgress (4): 221/329 kB | 188/358 kB | 196/252 kB | 49/120 kBProgress (4): 221/329 kB | 188/358 kB | 196/252 kB | 53/120 kBProgress (4): 221/329 kB | 188/358 kB | 196/252 kB | 57/120 kBProgress (4): 221/329 kB | 192/358 kB | 196/252 kB | 57/120 kBProgress (4): 221/329 kB | 196/358 kB | 196/252 kB | 57/120 kBProgress (4): 221/329 kB | 200/358 kB | 196/252 kB | 57/120 kBProgress (4): 221/329 kB | 204/358 kB | 196/252 kB | 57/120 kBProgress (4): 221/329 kB | 208/358 kB | 196/252 kB | 57/120 kBProgress (4): 221/329 kB | 212/358 kB | 196/252 kB | 57/120 kBProgress (4): 221/329 kB | 217/358 kB | 196/252 kB | 57/120 kBProgress (4): 221/329 kB | 221/358 kB | 196/252 kB | 57/120 kBProgress (4): 221/329 kB | 225/358 kB | 196/252 kB | 57/120 kBProgress (4): 221/329 kB | 229/358 kB | 196/252 kB | 57/120 kBProgress (4): 221/329 kB | 233/358 kB | 196/252 kB | 57/120 kBProgress (4): 221/329 kB | 237/358 kB | 196/252 kB | 57/120 kBProgress (4): 225/329 kB | 237/358 kB | 196/252 kB | 57/120 kBProgress (4): 229/329 kB | 237/358 kB | 196/252 kB | 57/120 kBProgress (5): 229/329 kB | 237/358 kB | 196/252 kB | 57/120 kB | 4.1/38 kBProgress (5): 229/329 kB | 237/358 kB | 196/252 kB | 57/120 kB | 8.2/38 kBProgress (5): 229/329 kB | 237/358 kB | 196/252 kB | 57/120 kB | 12/38 kB Progress (5): 229/329 kB | 237/358 kB | 196/252 kB | 57/120 kB | 16/38 kBProgress (5): 233/329 kB | 237/358 kB | 196/252 kB | 57/120 kB | 16/38 kBProgress (5): 237/329 kB | 237/358 kB | 196/252 kB | 57/120 kB | 16/38 kBProgress (5): 241/329 kB | 237/358 kB | 196/252 kB | 57/120 kB | 16/38 kBProgress (5): 245/329 kB | 237/358 kB | 196/252 kB | 57/120 kB | 16/38 kBProgress (5): 245/329 kB | 237/358 kB | 196/252 kB | 57/120 kB | 20/38 kBProgress (5): 245/329 kB | 237/358 kB | 196/252 kB | 57/120 kB | 24/38 kBProgress (5): 245/329 kB | 237/358 kB | 196/252 kB | 57/120 kB | 28/38 kBProgress (5): 245/329 kB | 237/358 kB | 196/252 kB | 57/120 kB | 32/38 kBProgress (5): 249/329 kB | 237/358 kB | 196/252 kB | 57/120 kB | 32/38 kBProgress (5): 249/329 kB | 237/358 kB | 196/252 kB | 57/120 kB | 36/38 kBProgress (5): 253/329 kB | 237/358 kB | 196/252 kB | 57/120 kB | 36/38 kBProgress (5): 253/329 kB | 237/358 kB | 196/252 kB | 57/120 kB | 38 kB   Progress (5): 258/329 kB | 237/358 kB | 196/252 kB | 57/120 kB | 38 kBProgress (5): 262/329 kB | 237/358 kB | 196/252 kB | 57/120 kB | 38 kBProgress (5): 262/329 kB | 237/358 kB | 196/252 kB | 61/120 kB | 38 kBProgress (5): 262/329 kB | 237/358 kB | 196/252 kB | 66/120 kB | 38 kBProgress (5): 262/329 kB | 237/358 kB | 196/252 kB | 70/120 kB | 38 kBProgress (5): 262/329 kB | 237/358 kB | 196/252 kB | 74/120 kB | 38 kBProgress (5): 262/329 kB | 237/358 kB | 196/252 kB | 78/120 kB | 38 kBProgress (5): 262/329 kB | 237/358 kB | 196/252 kB | 82/120 kB | 38 kBProgress (5): 262/329 kB | 237/358 kB | 196/252 kB | 86/120 kB | 38 kBProgress (5): 262/329 kB | 237/358 kB | 196/252 kB | 90/120 kB | 38 kBProgress (5): 262/329 kB | 237/358 kB | 196/252 kB | 94/120 kB | 38 kBProgress (5): 262/329 kB | 237/358 kB | 196/252 kB | 98/120 kB | 38 kBProgress (5): 266/329 kB | 237/358 kB | 196/252 kB | 98/120 kB | 38 kBProgress (5): 270/329 kB | 237/358 kB | 196/252 kB | 98/120 kB | 38 kBProgress (5): 274/329 kB | 237/358 kB | 196/252 kB | 98/120 kB | 38 kBProgress (5): 278/329 kB | 237/358 kB | 196/252 kB | 98/120 kB | 38 kBProgress (5): 278/329 kB | 237/358 kB | 196/252 kB | 102/120 kB | 38 kBProgress (5): 278/329 kB | 237/358 kB | 196/252 kB | 106/120 kB | 38 kBProgress (5): 278/329 kB | 237/358 kB | 196/252 kB | 111/120 kB | 38 kBProgress (5): 278/329 kB | 237/358 kB | 196/252 kB | 115/120 kB | 38 kB                                                                       Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/file-management/1.2.1/file-management-1.2.1.jar (38 kB at 53 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-io/1.1/maven-shared-io-1.1.jar
Progress (4): 282/329 kB | 237/358 kB | 196/252 kB | 115/120 kBProgress (4): 286/329 kB | 237/358 kB | 196/252 kB | 115/120 kBProgress (4): 290/329 kB | 237/358 kB | 196/252 kB | 115/120 kBProgress (4): 294/329 kB | 237/358 kB | 196/252 kB | 115/120 kBProgress (4): 294/329 kB | 237/358 kB | 200/252 kB | 115/120 kBProgress (4): 294/329 kB | 237/358 kB | 204/252 kB | 115/120 kBProgress (4): 294/329 kB | 237/358 kB | 208/252 kB | 115/120 kBProgress (4): 294/329 kB | 237/358 kB | 212/252 kB | 115/120 kBProgress (4): 299/329 kB | 237/358 kB | 212/252 kB | 115/120 kBProgress (4): 303/329 kB | 237/358 kB | 212/252 kB | 115/120 kBProgress (4): 307/329 kB | 237/358 kB | 212/252 kB | 115/120 kBProgress (4): 311/329 kB | 237/358 kB | 212/252 kB | 115/120 kBProgress (4): 311/329 kB | 237/358 kB | 212/252 kB | 119/120 kBProgress (4): 311/329 kB | 237/358 kB | 217/252 kB | 119/120 kBProgress (4): 311/329 kB | 237/358 kB | 217/252 kB | 120 kB    Progress (4): 311/329 kB | 241/358 kB | 217/252 kB | 120 kBProgress (4): 311/329 kB | 245/358 kB | 217/252 kB | 120 kBProgress (4): 311/329 kB | 245/358 kB | 221/252 kB | 120 kBProgress (4): 311/329 kB | 245/358 kB | 225/252 kB | 120 kBProgress (4): 311/329 kB | 249/358 kB | 225/252 kB | 120 kBProgress (4): 311/329 kB | 249/358 kB | 229/252 kB | 120 kBProgress (4): 311/329 kB | 253/358 kB | 229/252 kB | 120 kBProgress (4): 311/329 kB | 258/358 kB | 229/252 kB | 120 kBProgress (4): 311/329 kB | 262/358 kB | 229/252 kB | 120 kBProgress (4): 311/329 kB | 262/358 kB | 233/252 kB | 120 kBProgress (4): 311/329 kB | 266/358 kB | 233/252 kB | 120 kBProgress (4): 311/329 kB | 270/358 kB | 233/252 kB | 120 kBProgress (4): 311/329 kB | 274/358 kB | 233/252 kB | 120 kBProgress (4): 311/329 kB | 278/358 kB | 233/252 kB | 120 kBProgress (5): 311/329 kB | 278/358 kB | 233/252 kB | 120 kB | 4.1/39 kBProgress (5): 311/329 kB | 282/358 kB | 233/252 kB | 120 kB | 4.1/39 kBProgress (5): 311/329 kB | 282/358 kB | 233/252 kB | 120 kB | 8.2/39 kBProgress (5): 311/329 kB | 282/358 kB | 233/252 kB | 120 kB | 12/39 kB Progress (5): 311/329 kB | 282/358 kB | 233/252 kB | 120 kB | 16/39 kBProgress (5): 315/329 kB | 282/358 kB | 233/252 kB | 120 kB | 16/39 kBProgress (5): 319/329 kB | 282/358 kB | 233/252 kB | 120 kB | 16/39 kBProgress (5): 323/329 kB | 282/358 kB | 233/252 kB | 120 kB | 16/39 kBProgress (5): 323/329 kB | 282/358 kB | 233/252 kB | 120 kB | 20/39 kBProgress (5): 327/329 kB | 282/358 kB | 233/252 kB | 120 kB | 20/39 kBProgress (5): 327/329 kB | 282/358 kB | 233/252 kB | 120 kB | 25/39 kBProgress (5): 327/329 kB | 282/358 kB | 233/252 kB | 120 kB | 29/39 kBProgress (5): 327/329 kB | 282/358 kB | 233/252 kB | 120 kB | 33/39 kBProgress (5): 327/329 kB | 282/358 kB | 237/252 kB | 120 kB | 33/39 kBProgress (5): 327/329 kB | 282/358 kB | 241/252 kB | 120 kB | 33/39 kBProgress (5): 327/329 kB | 282/358 kB | 245/252 kB | 120 kB | 33/39 kBProgress (5): 327/329 kB | 282/358 kB | 249/252 kB | 120 kB | 33/39 kBProgress (5): 327/329 kB | 282/358 kB | 252 kB | 120 kB | 33/39 kB    Progress (5): 327/329 kB | 282/358 kB | 252 kB | 120 kB | 37/39 kBProgress (5): 327/329 kB | 282/358 kB | 252 kB | 120 kB | 39 kB   Progress (5): 327/329 kB | 286/358 kB | 252 kB | 120 kB | 39 kBProgress (5): 327/329 kB | 290/358 kB | 252 kB | 120 kB | 39 kBProgress (5): 327/329 kB | 294/358 kB | 252 kB | 120 kB | 39 kBProgress (5): 327/329 kB | 299/358 kB | 252 kB | 120 kB | 39 kBProgress (5): 327/329 kB | 303/358 kB | 252 kB | 120 kB | 39 kBProgress (5): 327/329 kB | 307/358 kB | 252 kB | 120 kB | 39 kBProgress (5): 327/329 kB | 311/358 kB | 252 kB | 120 kB | 39 kBProgress (5): 327/329 kB | 315/358 kB | 252 kB | 120 kB | 39 kBProgress (5): 327/329 kB | 319/358 kB | 252 kB | 120 kB | 39 kBProgress (5): 327/329 kB | 323/358 kB | 252 kB | 120 kB | 39 kBProgress (5): 327/329 kB | 327/358 kB | 252 kB | 120 kB | 39 kBProgress (5): 327/329 kB | 331/358 kB | 252 kB | 120 kB | 39 kBProgress (5): 327/329 kB | 335/358 kB | 252 kB | 120 kB | 39 kBProgress (5): 327/329 kB | 339/358 kB | 252 kB | 120 kB | 39 kBProgress (5): 327/329 kB | 344/358 kB | 252 kB | 120 kB | 39 kBProgress (5): 329 kB | 344/358 kB | 252 kB | 120 kB | 39 kB                                                               Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/struts/struts-tiles/1.3.8/struts-tiles-1.3.8.jar (120 kB at 162 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/wagon/wagon-provider-api/1.0-alpha-6/wagon-provider-api-1.0-alpha-6.jar
Progress (4): 329 kB | 348/358 kB | 252 kB | 39 kBProgress (4): 329 kB | 352/358 kB | 252 kB | 39 kBProgress (4): 329 kB | 356/358 kB | 252 kB | 39 kBProgress (4): 329 kB | 358 kB | 252 kB | 39 kB                                                  Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/struts/struts-taglib/1.3.8/struts-taglib-1.3.8.jar (252 kB at 339 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-dependency-analyzer/1.9/maven-dependency-analyzer-1.9.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-shared-io/1.1/maven-shared-io-1.1.jar (39 kB at 53 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/6.1/asm-6.1.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/struts/struts-core/1.3.8/struts-core-1.3.8.jar (329 kB at 442 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-dependency-tree/3.0.1/maven-dependency-tree-3.0.1.jar
Progress (2): 358 kB | 4.1/43 kBProgress (2): 358 kB | 8.2/43 kBProgress (2): 358 kB | 12/43 kB Progress (2): 358 kB | 16/43 kBProgress (2): 358 kB | 20/43 kBProgress (2): 358 kB | 25/43 kBProgress (2): 358 kB | 29/43 kBProgress (2): 358 kB | 33/43 kB                               Downloaded from central: https://repo.maven.apache.org/maven2/antlr/antlr/2.7.2/antlr-2.7.2.jar (358 kB at 478 kB/s)
Progress (1): 37/43 kBProgress (1): 41/43 kBProgress (1): 43 kB   Progress (2): 43 kB | 4.1/37 kBProgress (2): 43 kB | 8.2/37 kBProgress (2): 43 kB | 12/37 kB Progress (2): 43 kB | 16/37 kB                              Downloading from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether-util/0.9.0.M2/aether-util-0.9.0.M2.jar
Progress (2): 43 kB | 20/37 kBProgress (3): 43 kB | 20/37 kB | 4.1/108 kBProgress (3): 43 kB | 20/37 kB | 8.2/108 kBProgress (3): 43 kB | 20/37 kB | 12/108 kB Progress (3): 43 kB | 20/37 kB | 16/108 kBProgress (3): 43 kB | 25/37 kB | 16/108 kBProgress (3): 43 kB | 29/37 kB | 16/108 kBProgress (3): 43 kB | 33/37 kB | 16/108 kBProgress (3): 43 kB | 37 kB | 16/108 kB   Progress (4): 43 kB | 37 kB | 16/108 kB | 4.1/35 kBProgress (4): 43 kB | 37 kB | 16/108 kB | 8.2/35 kBProgress (4): 43 kB | 37 kB | 16/108 kB | 12/35 kB Progress (4): 43 kB | 37 kB | 16/108 kB | 16/35 kB                                                  Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/wagon/wagon-provider-api/1.0-alpha-6/wagon-provider-api-1.0-alpha-6.jar (43 kB at 56 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-common-artifact-filters/3.0.1/maven-common-artifact-filters-3.0.1.jar
Progress (3): 37 kB | 20/108 kB | 16/35 kBProgress (3): 37 kB | 24/108 kB | 16/35 kBProgress (3): 37 kB | 28/108 kB | 16/35 kBProgress (3): 37 kB | 32/108 kB | 16/35 kBProgress (4): 37 kB | 32/108 kB | 16/35 kB | 4.1/134 kBProgress (4): 37 kB | 32/108 kB | 16/35 kB | 8.2/134 kBProgress (4): 37 kB | 32/108 kB | 16/35 kB | 12/134 kB Progress (4): 37 kB | 32/108 kB | 16/35 kB | 16/134 kBProgress (4): 37 kB | 32/108 kB | 16/35 kB | 20/134 kBProgress (4): 37 kB | 32/108 kB | 16/35 kB | 25/134 kBProgress (4): 37 kB | 32/108 kB | 16/35 kB | 29/134 kBProgress (4): 37 kB | 32/108 kB | 16/35 kB | 33/134 kBProgress (4): 37 kB | 32/108 kB | 16/35 kB | 37/134 kBProgress (4): 37 kB | 32/108 kB | 16/35 kB | 41/134 kBProgress (4): 37 kB | 32/108 kB | 16/35 kB | 45/134 kBProgress (4): 37 kB | 32/108 kB | 16/35 kB | 49/134 kBProgress (5): 37 kB | 32/108 kB | 16/35 kB | 49/134 kB | 4.1/61 kBProgress (5): 37 kB | 32/108 kB | 16/35 kB | 49/134 kB | 8.2/61 kBProgress (5): 37 kB | 32/108 kB | 16/35 kB | 49/134 kB | 12/61 kB Progress (5): 37 kB | 32/108 kB | 16/35 kB | 49/134 kB | 16/61 kBProgress (5): 37 kB | 32/108 kB | 16/35 kB | 49/134 kB | 20/61 kBProgress (5): 37 kB | 32/108 kB | 16/35 kB | 49/134 kB | 25/61 kBProgress (5): 37 kB | 32/108 kB | 16/35 kB | 49/134 kB | 29/61 kBProgress (5): 37 kB | 32/108 kB | 16/35 kB | 49/134 kB | 33/61 kBProgress (5): 37 kB | 32/108 kB | 16/35 kB | 49/134 kB | 37/61 kBProgress (5): 37 kB | 32/108 kB | 16/35 kB | 49/134 kB | 41/61 kBProgress (5): 37 kB | 32/108 kB | 16/35 kB | 49/134 kB | 45/61 kBProgress (5): 37 kB | 32/108 kB | 16/35 kB | 49/134 kB | 49/61 kBProgress (5): 37 kB | 32/108 kB | 16/35 kB | 53/134 kB | 49/61 kBProgress (5): 37 kB | 32/108 kB | 16/35 kB | 57/134 kB | 49/61 kBProgress (5): 37 kB | 32/108 kB | 16/35 kB | 61/134 kB | 49/61 kBProgress (5): 37 kB | 32/108 kB | 16/35 kB | 66/134 kB | 49/61 kBProgress (5): 37 kB | 32/108 kB | 16/35 kB | 70/134 kB | 49/61 kBProgress (5): 37 kB | 32/108 kB | 16/35 kB | 74/134 kB | 49/61 kBProgress (5): 37 kB | 32/108 kB | 16/35 kB | 78/134 kB | 49/61 kBProgress (5): 37 kB | 32/108 kB | 16/35 kB | 82/134 kB | 49/61 kBProgress (5): 37 kB | 32/108 kB | 16/35 kB | 86/134 kB | 49/61 kBProgress (5): 37 kB | 32/108 kB | 16/35 kB | 90/134 kB | 49/61 kBProgress (5): 37 kB | 32/108 kB | 16/35 kB | 94/134 kB | 49/61 kBProgress (5): 37 kB | 32/108 kB | 16/35 kB | 98/134 kB | 49/61 kBProgress (5): 37 kB | 32/108 kB | 16/35 kB | 102/134 kB | 49/61 kBProgress (5): 37 kB | 32/108 kB | 16/35 kB | 106/134 kB | 49/61 kBProgress (5): 37 kB | 32/108 kB | 16/35 kB | 111/134 kB | 49/61 kBProgress (5): 37 kB | 32/108 kB | 16/35 kB | 115/134 kB | 49/61 kBProgress (5): 37 kB | 32/108 kB | 20/35 kB | 115/134 kB | 49/61 kBProgress (5): 37 kB | 32/108 kB | 25/35 kB | 115/134 kB | 49/61 kBProgress (5): 37 kB | 32/108 kB | 29/35 kB | 115/134 kB | 49/61 kBProgress (5): 37 kB | 32/108 kB | 33/35 kB | 115/134 kB | 49/61 kBProgress (5): 37 kB | 32/108 kB | 35 kB | 115/134 kB | 49/61 kB   Progress (5): 37 kB | 32/108 kB | 35 kB | 115/134 kB | 53/61 kBProgress (5): 37 kB | 32/108 kB | 35 kB | 115/134 kB | 57/61 kBProgress (5): 37 kB | 32/108 kB | 35 kB | 115/134 kB | 61/61 kBProgress (5): 37 kB | 32/108 kB | 35 kB | 115/134 kB | 61 kB   Progress (5): 37 kB | 36/108 kB | 35 kB | 115/134 kB | 61 kB                                                            Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-dependency-tree/3.0.1/maven-dependency-tree-3.0.1.jar (37 kB at 47 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-artifact-transfer/0.9.1/maven-artifact-transfer-0.9.1.jar
Progress (4): 40/108 kB | 35 kB | 115/134 kB | 61 kBProgress (4): 45/108 kB | 35 kB | 115/134 kB | 61 kBProgress (4): 49/108 kB | 35 kB | 115/134 kB | 61 kBProgress (4): 53/108 kB | 35 kB | 115/134 kB | 61 kBProgress (4): 57/108 kB | 35 kB | 115/134 kB | 61 kBProgress (4): 61/108 kB | 35 kB | 115/134 kB | 61 kBProgress (4): 65/108 kB | 35 kB | 115/134 kB | 61 kBProgress (4): 69/108 kB | 35 kB | 115/134 kB | 61 kBProgress (4): 73/108 kB | 35 kB | 115/134 kB | 61 kBProgress (4): 77/108 kB | 35 kB | 115/134 kB | 61 kBProgress (4): 81/108 kB | 35 kB | 115/134 kB | 61 kBProgress (4): 86/108 kB | 35 kB | 115/134 kB | 61 kBProgress (4): 90/108 kB | 35 kB | 115/134 kB | 61 kBProgress (4): 94/108 kB | 35 kB | 115/134 kB | 61 kBProgress (4): 98/108 kB | 35 kB | 115/134 kB | 61 kBProgress (4): 102/108 kB | 35 kB | 115/134 kB | 61 kBProgress (4): 106/108 kB | 35 kB | 115/134 kB | 61 kBProgress (4): 108 kB | 35 kB | 115/134 kB | 61 kB    Progress (5): 108 kB | 35 kB | 115/134 kB | 61 kB | 4.1/123 kBProgress (5): 108 kB | 35 kB | 115/134 kB | 61 kB | 8.2/123 kBProgress (5): 108 kB | 35 kB | 115/134 kB | 61 kB | 12/123 kB Progress (5): 108 kB | 35 kB | 115/134 kB | 61 kB | 16/123 kBProgress (5): 108 kB | 35 kB | 115/134 kB | 61 kB | 20/123 kBProgress (5): 108 kB | 35 kB | 115/134 kB | 61 kB | 24/123 kBProgress (5): 108 kB | 35 kB | 115/134 kB | 61 kB | 28/123 kBProgress (5): 108 kB | 35 kB | 115/134 kB | 61 kB | 32/123 kBProgress (5): 108 kB | 35 kB | 115/134 kB | 61 kB | 36/123 kBProgress (5): 108 kB | 35 kB | 115/134 kB | 61 kB | 40/123 kBProgress (5): 108 kB | 35 kB | 115/134 kB | 61 kB | 45/123 kBProgress (5): 108 kB | 35 kB | 115/134 kB | 61 kB | 49/123 kBProgress (5): 108 kB | 35 kB | 115/134 kB | 61 kB | 53/123 kBProgress (5): 108 kB | 35 kB | 115/134 kB | 61 kB | 57/123 kB                                                             Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-dependency-analyzer/1.9/maven-dependency-analyzer-1.9.jar (35 kB at 44 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/commons-codec/commons-codec/1.6/commons-codec-1.6.jar
Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-common-artifact-filters/3.0.1/maven-common-artifact-filters-3.0.1.jar (61 kB at 77 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-api/1.7.5/slf4j-api-1.7.5.jar
Progress (3): 108 kB | 115/134 kB | 61/123 kBProgress (3): 108 kB | 115/134 kB | 65/123 kBProgress (3): 108 kB | 115/134 kB | 69/123 kBProgress (3): 108 kB | 115/134 kB | 73/123 kBProgress (3): 108 kB | 119/134 kB | 73/123 kBProgress (3): 108 kB | 123/134 kB | 73/123 kBProgress (3): 108 kB | 127/134 kB | 73/123 kBProgress (3): 108 kB | 127/134 kB | 77/123 kBProgress (3): 108 kB | 131/134 kB | 77/123 kBProgress (3): 108 kB | 131/134 kB | 81/123 kBProgress (3): 108 kB | 134 kB | 81/123 kB                                             Downloaded from central: https://repo.maven.apache.org/maven2/org/ow2/asm/asm/6.1/asm-6.1.jar (108 kB at 134 kB/s)
Downloading from central: https://repo.maven.apache.org/maven2/commons-lang/commons-lang/2.6/commons-lang-2.6.jar
Progress (3): 134 kB | 81/123 kB | 4.1/26 kBProgress (3): 134 kB | 81/123 kB | 8.2/26 kBProgress (3): 134 kB | 81/123 kB | 12/26 kB Progress (3): 134 kB | 81/123 kB | 16/26 kBProgress (4): 134 kB | 81/123 kB | 16/26 kB | 4.1/233 kBProgress (4): 134 kB | 81/123 kB | 16/26 kB | 8.2/233 kBProgress (4): 134 kB | 81/123 kB | 16/26 kB | 12/233 kB Progress (4): 134 kB | 81/123 kB | 20/26 kB | 12/233 kBProgress (4): 134 kB | 81/123 kB | 25/26 kB | 12/233 kBProgress (4): 134 kB | 81/123 kB | 26 kB | 12/233 kB   Progress (4): 134 kB | 86/123 kB | 26 kB | 12/233 kBProgress (4): 134 kB | 90/123 kB | 26 kB | 12/233 kBProgress (4): 134 kB | 94/123 kB | 26 kB | 12/233 kBProgress (4): 134 kB | 94/123 kB | 26 kB | 16/233 kBProgress (4): 134 kB | 94/123 kB | 26 kB | 20/233 kBProgress (4): 134 kB | 94/123 kB | 26 kB | 25/233 kBProgress (4): 134 kB | 94/123 kB | 26 kB | 29/233 kBProgress (4): 134 kB | 94/123 kB | 26 kB | 33/233 kB                                                    Downloaded from central: https://repo.maven.apache.org/maven2/org/eclipse/aether/aether-util/0.9.0.M2/aether-util-0.9.0.M2.jar (134 kB at 164 kB/s)
Progress (3): 98/123 kB | 26 kB | 33/233 kBProgress (3): 102/123 kB | 26 kB | 33/233 kBProgress (3): 106/123 kB | 26 kB | 33/233 kBProgress (3): 110/123 kB | 26 kB | 33/233 kBProgress (3): 114/123 kB | 26 kB | 33/233 kBProgress (3): 118/123 kB | 26 kB | 33/233 kBProgress (3): 122/123 kB | 26 kB | 33/233 kBProgress (3): 123 kB | 26 kB | 33/233 kB                                            Downloading from central: https://repo.maven.apache.org/maven2/commons-collections/commons-collections/3.2.2/commons-collections-3.2.2.jar
Progress (4): 123 kB | 26 kB | 33/233 kB | 4.1/284 kBProgress (4): 123 kB | 26 kB | 33/233 kB | 8.2/284 kBProgress (4): 123 kB | 26 kB | 33/233 kB | 12/284 kB Progress (4): 123 kB | 26 kB | 33/233 kB | 16/284 kBProgress (4): 123 kB | 26 kB | 37/233 kB | 16/284 kBProgress (4): 123 kB | 26 kB | 41/233 kB | 16/284 kBProgress (4): 123 kB | 26 kB | 45/233 kB | 16/284 kBProgress (4): 123 kB | 26 kB | 49/233 kB | 16/284 kB                                                    Downloaded from central: https://repo.maven.apache.org/maven2/org/slf4j/slf4j-api/1.7.5/slf4j-api-1.7.5.jar (26 kB at 32 kB/s)
Progress (3): 123 kB | 53/233 kB | 16/284 kBProgress (3): 123 kB | 57/233 kB | 16/284 kBProgress (3): 123 kB | 61/233 kB | 16/284 kBProgress (3): 123 kB | 66/233 kB | 16/284 kBProgress (3): 123 kB | 70/233 kB | 16/284 kBProgress (3): 123 kB | 74/233 kB | 16/284 kBProgress (3): 123 kB | 78/233 kB | 16/284 kBProgress (3): 123 kB | 82/233 kB | 16/284 kBProgress (4): 123 kB | 82/233 kB | 16/284 kB | 4.1/588 kBProgress (4): 123 kB | 82/233 kB | 16/284 kB | 8.2/588 kBProgress (4): 123 kB | 82/233 kB | 16/284 kB | 12/588 kB Progress (4): 123 kB | 82/233 kB | 16/284 kB | 16/588 kBProgress (4): 123 kB | 82/233 kB | 16/284 kB | 20/588 kBProgress (4): 123 kB | 82/233 kB | 16/284 kB | 24/588 kBProgress (4): 123 kB | 82/233 kB | 16/284 kB | 28/588 kBProgress (4): 123 kB | 82/233 kB | 16/284 kB | 32/588 kBProgress (4): 123 kB | 82/233 kB | 16/284 kB | 36/588 kBProgress (4): 123 kB | 82/233 kB | 16/284 kB | 40/588 kBProgress (4): 123 kB | 82/233 kB | 16/284 kB | 45/588 kBProgress (4): 123 kB | 82/233 kB | 16/284 kB | 49/588 kBProgress (4): 123 kB | 82/233 kB | 16/284 kB | 53/588 kBProgress (4): 123 kB | 82/233 kB | 16/284 kB | 57/588 kBProgress (4): 123 kB | 82/233 kB | 16/284 kB | 61/588 kBProgress (4): 123 kB | 82/233 kB | 16/284 kB | 65/588 kBProgress (4): 123 kB | 82/233 kB | 16/284 kB | 69/588 kBProgress (4): 123 kB | 82/233 kB | 16/284 kB | 73/588 kBProgress (4): 123 kB | 82/233 kB | 16/284 kB | 77/588 kBProgress (4): 123 kB | 82/233 kB | 16/284 kB | 81/588 kBProgress (4): 123 kB | 82/233 kB | 16/284 kB | 86/588 kBProgress (4): 123 kB | 82/233 kB | 20/284 kB | 86/588 kBProgress (4): 123 kB | 82/233 kB | 25/284 kB | 86/588 kBProgress (4): 123 kB | 82/233 kB | 29/284 kB | 86/588 kBProgress (4): 123 kB | 82/233 kB | 33/284 kB | 86/588 kBProgress (4): 123 kB | 82/233 kB | 37/284 kB | 86/588 kBProgress (4): 123 kB | 82/233 kB | 41/284 kB | 86/588 kBProgress (4): 123 kB | 82/233 kB | 45/284 kB | 86/588 kBProgress (4): 123 kB | 82/233 kB | 49/284 kB | 86/588 kBProgress (4): 123 kB | 82/233 kB | 53/284 kB | 86/588 kBProgress (4): 123 kB | 82/233 kB | 57/284 kB | 86/588 kBProgress (4): 123 kB | 82/233 kB | 61/284 kB | 86/588 kBProgress (4): 123 kB | 82/233 kB | 66/284 kB | 86/588 kBProgress (4): 123 kB | 86/233 kB | 66/284 kB | 86/588 kBProgress (4): 123 kB | 90/233 kB | 66/284 kB | 86/588 kBProgress (4): 123 kB | 94/233 kB | 66/284 kB | 86/588 kBProgress (4): 123 kB | 98/233 kB | 66/284 kB | 86/588 kBProgress (4): 123 kB | 102/233 kB | 66/284 kB | 86/588 kBProgress (4): 123 kB | 106/233 kB | 66/284 kB | 86/588 kBProgress (4): 123 kB | 111/233 kB | 66/284 kB | 86/588 kBProgress (4): 123 kB | 115/233 kB | 66/284 kB | 86/588 kBProgress (4): 123 kB | 119/233 kB | 66/284 kB | 86/588 kBProgress (4): 123 kB | 123/233 kB | 66/284 kB | 86/588 kBProgress (4): 123 kB | 127/233 kB | 66/284 kB | 86/588 kBProgress (4): 123 kB | 131/233 kB | 66/284 kB | 86/588 kBProgress (4): 123 kB | 135/233 kB | 66/284 kB | 86/588 kBProgress (4): 123 kB | 139/233 kB | 66/284 kB | 86/588 kBProgress (4): 123 kB | 143/233 kB | 66/284 kB | 86/588 kBProgress (4): 123 kB | 147/233 kB | 66/284 kB | 86/588 kBProgress (4): 123 kB | 152/233 kB | 66/284 kB | 86/588 kBProgress (4): 123 kB | 156/233 kB | 66/284 kB | 86/588 kBProgress (4): 123 kB | 160/233 kB | 66/284 kB | 86/588 kBProgress (4): 123 kB | 164/233 kB | 66/284 kB | 86/588 kB                                                         Downloaded from central: https://repo.maven.apache.org/maven2/org/apache/maven/shared/maven-artifact-transfer/0.9.1/maven-artifact-transfer-0.9.1.jar (123 kB at 146 kB/s)
Progress (3): 164/233 kB | 70/284 kB | 86/588 kBProgress (3): 164/233 kB | 74/284 kB | 86/588 kBProgress (3): 164/233 kB | 78/284 kB | 86/588 kBProgress (3): 164/233 kB | 82/284 kB | 86/588 kBProgress (3): 164/233 kB | 86/284 kB | 86/588 kBProgress (3): 164/233 kB | 90/284 kB | 86/588 kBProgress (3): 164/233 kB | 94/284 kB | 86/588 kBProgress (3): 164/233 kB | 98/284 kB | 86/588 kBProgress (3): 164/233 kB | 102/284 kB | 86/588 kBProgress (3): 164/233 kB | 106/284 kB | 86/588 kBProgress (3): 164/233 kB | 111/284 kB | 86/588 kBProgress (3): 164/233 kB | 115/284 kB | 86/588 kBProgress (3): 164/233 kB | 115/284 kB | 90/588 kBProgress (3): 164/233 kB | 115/284 kB | 94/588 kBProgress (3): 164/233 kB | 115/284 kB | 98/588 kBProgress (3): 164/233 kB | 115/284 kB | 102/588 kBProgress (3): 164/233 kB | 115/284 kB | 106/588 kBProgress (3): 164/233 kB | 115/284 kB | 110/588 kBProgress (3): 164/233 kB | 115/284 kB | 114/588 kBProgress (3): 164/233 kB | 115/284 kB | 118/588 kBProgress (3): 164/233 kB | 115/284 kB | 122/588 kBProgress (3): 164/233 kB | 115/284 kB | 126/588 kBProgress (3): 164/233 kB | 115/284 kB | 131/588 kBProgress (3): 164/233 kB | 115/284 kB | 135/588 kBProgress (3): 164/233 kB | 115/284 kB | 139/588 kBProgress (3): 164/233 kB | 115/284 kB | 143/588 kBProgress (3): 164/233 kB | 115/284 kB | 147/588 kBProgress (3): 164/233 kB | 115/284 kB | 151/588 kBProgress (3): 168/233 kB | 115/284 kB | 151/588 kBProgress (3): 172/233 kB | 115/284 kB | 151/588 kBProgress (3): 176/233 kB | 115/284 kB | 151/588 kBProgress (3): 180/233 kB | 115/284 kB | 151/588 kBProgress (3): 184/233 kB | 115/284 kB | 151/588 kBProgress (3): 188/233 kB | 115/284 kB | 151/588 kBProgress (3): 193/233 kB | 115/284 kB | 151/588 kBProgress (3): 197/233 kB | 115/284 kB | 151/588 kBProgress (3): 201/233 kB | 115/284 kB | 151/588 kBProgress (3): 205/233 kB | 115/284 kB | 151/588 kBProgress (3): 209/233 kB | 115/284 kB | 151/588 kBProgress (3): 213/233 kB | 115/284 kB | 151/588 kBProgress (3): 217/233 kB | 115/284 kB | 151/588 kBProgress (3): 221/233 kB | 115/284 kB | 151/588 kBProgress (3): 225/233 kB | 115/284 kB | 151/588 kBProgress (3): 229/233 kB | 115/284 kB | 151/588 kBProgress (3): 229/233 kB | 119/284 kB | 151/588 kBProgress (3): 229/233 kB | 123/284 kB | 151/588 kBProgress (3): 229/233 kB | 127/284 kB | 151/588 kBProgress (3): 229/233 kB | 131/284 kB | 151/588 kBProgress (3): 229/233 kB | 135/284 kB | 151/588 kBProgress (3): 229/233 kB | 139/284 kB | 151/588 kBProgress (3): 229/233 kB | 143/284 kB | 151/588 kBProgress (3): 229/233 kB | 147/284 kB | 151/588 kBProgress (3): 229/233 kB | 152/284 kB | 151/588 kBProgress (3): 229/233 kB | 156/284 kB | 151/588 kBProgress (3): 229/233 kB | 160/284 kB | 151/588 kBProgress (3): 229/233 kB | 164/284 kB | 151/588 kBProgress (3): 229/233 kB | 164/284 kB | 155/588 kBProgress (3): 229/233 kB | 164/284 kB | 159/588 kBProgress (3): 229/233 kB | 164/284 kB | 163/588 kBProgress (3): 229/233 kB | 164/284 kB | 167/588 kBProgress (3): 233 kB | 164/284 kB | 167/588 kB    Progress (3): 233 kB | 164/284 kB | 172/588 kBProgress (3): 233 kB | 164/284 kB | 176/588 kBProgress (3): 233 kB | 164/284 kB | 180/588 kBProgress (3): 233 kB | 168/284 kB | 180/588 kBProgress (3): 233 kB | 172/284 kB | 180/588 kBProgress (3): 233 kB | 176/284 kB | 180/588 kBProgress (3): 233 kB | 180/284 kB | 180/588 kBProgress (3): 233 kB | 180/284 kB | 184/588 kBProgress (3): 233 kB | 180/284 kB | 188/588 kBProgress (3): 233 kB | 180/284 kB | 192/588 kBProgress (3): 233 kB | 180/284 kB | 196/588 kBProgress (3): 233 kB | 184/284 kB | 196/588 kBProgress (3): 233 kB | 188/284 kB | 196/588 kBProgress (3): 233 kB | 193/284 kB | 196/588 kBProgress (3): 233 kB | 197/284 kB | 196/588 kBProgress (3): 233 kB | 197/284 kB | 200/588 kBProgress (3): 233 kB | 197/284 kB | 204/588 kBProgress (3): 233 kB | 197/284 kB | 208/588 kBProgress (3): 233 kB | 197/284 kB | 212/588 kBProgress (3): 233 kB | 197/284 kB | 217/588 kBProgress (3): 233 kB | 197/284 kB | 221/588 kBProgress (3): 233 kB | 197/284 kB | 225/588 kBProgress (3): 233 kB | 197/284 kB | 229/588 kBProgress (3): 233 kB | 197/284 kB | 233/588 kBProgress (3): 233 kB | 197/284 kB | 237/588 kBProgress (3): 233 kB | 197/284 kB | 241/588 kBProgress (3): 233 kB | 197/284 kB | 245/588 kB                                              Downloaded from central: https://repo.maven.apache.org/maven2/commons-codec/commons-codec/1.6/commons-codec-1.6.jar (233 kB at 263 kB/s)
Progress (2): 201/284 kB | 245/588 kBProgress (2): 201/284 kB | 249/588 kBProgress (2): 205/284 kB | 249/588 kBProgress (2): 205/284 kB | 253/588 kBProgress (2): 209/284 kB | 253/588 kBProgress (2): 209/284 kB | 258/588 kBProgress (2): 213/284 kB | 258/588 kBProgress (2): 213/284 kB | 262/588 kBProgress (2): 213/284 kB | 266/588 kBProgress (2): 213/284 kB | 270/588 kBProgress (2): 213/284 kB | 274/588 kBProgress (2): 213/284 kB | 278/588 kBProgress (2): 213/284 kB | 282/588 kBProgress (2): 213/284 kB | 286/588 kBProgress (2): 213/284 kB | 290/588 kBProgress (2): 213/284 kB | 294/588 kBProgress (2): 213/284 kB | 299/588 kBProgress (2): 213/284 kB | 303/588 kBProgress (2): 213/284 kB | 307/588 kBProgress (2): 213/284 kB | 311/588 kBProgress (2): 213/284 kB | 315/588 kBProgress (2): 213/284 kB | 319/588 kBProgress (2): 213/284 kB | 323/588 kBProgress (2): 213/284 kB | 327/588 kBProgress (2): 213/284 kB | 331/588 kBProgress (2): 213/284 kB | 335/588 kBProgress (2): 213/284 kB | 339/588 kBProgress (2): 213/284 kB | 344/588 kBProgress (2): 213/284 kB | 348/588 kBProgress (2): 217/284 kB | 348/588 kBProgress (2): 221/284 kB | 348/588 kBProgress (2): 225/284 kB | 348/588 kBProgress (2): 229/284 kB | 348/588 kBProgress (2): 233/284 kB | 348/588 kBProgress (2): 238/284 kB | 348/588 kBProgress (2): 242/284 kB | 348/588 kBProgress (2): 246/284 kB | 348/588 kBProgress (2): 250/284 kB | 348/588 kBProgress (2): 254/284 kB | 348/588 kBProgress (2): 254/284 kB | 352/588 kBProgress (2): 254/284 kB | 356/588 kBProgress (2): 254/284 kB | 360/588 kBProgress (2): 254/284 kB | 364/588 kBProgress (2): 254/284 kB | 368/588 kBProgress (2): 254/284 kB | 372/588 kBProgress (2): 254/284 kB | 376/588 kBProgress (2): 254/284 kB | 380/588 kBProgress (2): 254/284 kB | 385/588 kBProgress (2): 254/284 kB | 389/588 kBProgress (2): 254/284 kB | 393/588 kBProgress (2): 254/284 kB | 397/588 kBProgress (2): 254/284 kB | 401/588 kBProgress (2): 254/284 kB | 405/588 kBProgress (2): 254/284 kB | 409/588 kBProgress (2): 254/284 kB | 413/588 kBProgress (2): 254/284 kB | 417/588 kBProgress (2): 258/284 kB | 417/588 kBProgress (2): 262/284 kB | 417/588 kBProgress (2): 266/284 kB | 417/588 kBProgress (2): 270/284 kB | 417/588 kBProgress (2): 274/284 kB | 417/588 kBProgress (2): 279/284 kB | 417/588 kBProgress (2): 283/284 kB | 417/588 kBProgress (2): 284 kB | 417/588 kB    Progress (2): 284 kB | 421/588 kBProgress (2): 284 kB | 425/588 kBProgress (2): 284 kB | 430/588 kBProgress (2): 284 kB | 434/588 kBProgress (2): 284 kB | 438/588 kBProgress (2): 284 kB | 442/588 kBProgress (2): 284 kB | 446/588 kBProgress (2): 284 kB | 450/588 kBProgress (2): 284 kB | 454/588 kBProgress (2): 284 kB | 458/588 kBProgress (2): 284 kB | 462/588 kBProgress (2): 284 kB | 466/588 kBProgress (2): 284 kB | 471/588 kBProgress (2): 284 kB | 475/588 kBProgress (2): 284 kB | 479/588 kBProgress (2): 284 kB | 483/588 kBProgress (2): 284 kB | 487/588 kBProgress (2): 284 kB | 491/588 kBProgress (2): 284 kB | 495/588 kB                                 Downloaded from central: https://repo.maven.apache.org/maven2/commons-lang/commons-lang/2.6/commons-lang-2.6.jar (284 kB at 302 kB/s)
Progress (1): 499/588 kBProgress (1): 503/588 kBProgress (1): 507/588 kBProgress (1): 511/588 kBProgress (1): 516/588 kBProgress (1): 520/588 kBProgress (1): 524/588 kBProgress (1): 528/588 kBProgress (1): 532/588 kBProgress (1): 536/588 kBProgress (1): 540/588 kBProgress (1): 544/588 kBProgress (1): 548/588 kBProgress (1): 552/588 kBProgress (1): 557/588 kBProgress (1): 561/588 kBProgress (1): 565/588 kBProgress (1): 569/588 kBProgress (1): 573/588 kBProgress (1): 577/588 kBProgress (1): 581/588 kBProgress (1): 585/588 kBProgress (1): 588 kB                        Downloaded from central: https://repo.maven.apache.org/maven2/commons-collections/commons-collections/3.2.2/commons-collections-3.2.2.jar (588 kB at 613 kB/s)
[INFO] Copying client-base-1.0-SNAPSHOT.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/client-base-1.0-SNAPSHOT.jar
[INFO] Copying benchmark-base-1.0-SNAPSHOT.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/benchmark-base-1.0-SNAPSHOT.jar
[INFO] Copying protobuf-java-3.11.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/protobuf-java-3.11.0.jar
[INFO] Copying protobuf-java-util-3.11.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/protobuf-java-util-3.11.0.jar
[INFO] Copying guava-28.1-android.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/guava-28.1-android.jar
[INFO] Copying failureaccess-1.0.1.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/failureaccess-1.0.1.jar
[INFO] Copying listenablefuture-9999.0-empty-to-avoid-conflict-with-guava.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/listenablefuture-9999.0-empty-to-avoid-conflict-with-guava.jar
[INFO] Copying checker-compat-qual-2.5.5.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/checker-compat-qual-2.5.5.jar
[INFO] Copying j2objc-annotations-1.3.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/j2objc-annotations-1.3.jar
[INFO] Copying animal-sniffer-annotations-1.18.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/animal-sniffer-annotations-1.18.jar
[INFO] Copying error_prone_annotations-2.3.3.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/error_prone_annotations-2.3.3.jar
[INFO] Copying grpc-netty-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/grpc-netty-1.44.0.jar
[INFO] Copying grpc-core-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/grpc-core-1.44.0.jar
[INFO] Copying annotations-4.1.1.4.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/annotations-4.1.1.4.jar
[INFO] Copying netty-codec-http2-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-codec-http2-4.1.72.Final.jar
[INFO] Copying netty-common-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-common-4.1.72.Final.jar
[INFO] Copying netty-buffer-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-buffer-4.1.72.Final.jar
[INFO] Copying netty-transport-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-transport-4.1.72.Final.jar
[INFO] Copying netty-resolver-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-resolver-4.1.72.Final.jar
[INFO] Copying netty-codec-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-codec-4.1.72.Final.jar
[INFO] Copying netty-handler-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-handler-4.1.72.Final.jar
[INFO] Copying netty-tcnative-classes-2.0.46.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-tcnative-classes-2.0.46.Final.jar
[INFO] Copying netty-codec-http-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-codec-http-4.1.72.Final.jar
[INFO] Copying netty-handler-proxy-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-handler-proxy-4.1.72.Final.jar
[INFO] Copying netty-codec-socks-4.1.72.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-codec-socks-4.1.72.Final.jar
[INFO] Copying perfmark-api-0.23.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/perfmark-api-0.23.0.jar
[INFO] Copying grpc-netty-shaded-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/grpc-netty-shaded-1.44.0.jar
[INFO] Copying grpc-protobuf-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/grpc-protobuf-1.44.0.jar
[INFO] Copying grpc-api-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/grpc-api-1.44.0.jar
[INFO] Copying grpc-context-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/grpc-context-1.44.0.jar
[INFO] Copying jsr305-3.0.2.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/jsr305-3.0.2.jar
[INFO] Copying proto-google-common-protos-2.0.1.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/proto-google-common-protos-2.0.1.jar
[INFO] Copying grpc-protobuf-lite-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/grpc-protobuf-lite-1.44.0.jar
[INFO] Copying grpc-stub-1.44.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/grpc-stub-1.44.0.jar
[INFO] Copying jmh-core-1.21.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/jmh-core-1.21.jar
[INFO] Copying jopt-simple-4.6.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/jopt-simple-4.6.jar
[INFO] Copying commons-math3-3.2.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/commons-math3-3.2.jar
[INFO] Copying jmh-generator-annprocess-1.21.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/jmh-generator-annprocess-1.21.jar
[INFO] Copying dubbo-3.1.0.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/dubbo-3.1.0.jar
[INFO] Copying spring-context-5.2.20.RELEASE.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/spring-context-5.2.20.RELEASE.jar
[INFO] Copying spring-aop-5.2.20.RELEASE.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/spring-aop-5.2.20.RELEASE.jar
[INFO] Copying spring-beans-5.2.20.RELEASE.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/spring-beans-5.2.20.RELEASE.jar
[INFO] Copying spring-core-5.2.20.RELEASE.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/spring-core-5.2.20.RELEASE.jar
[INFO] Copying spring-jcl-5.2.20.RELEASE.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/spring-jcl-5.2.20.RELEASE.jar
[INFO] Copying spring-expression-5.2.20.RELEASE.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/spring-expression-5.2.20.RELEASE.jar
[INFO] Copying spring-context-support-1.0.8.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/spring-context-support-1.0.8.jar
[INFO] Copying javassist-3.28.0-GA.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/javassist-3.28.0-GA.jar
[INFO] Copying gson-2.8.9.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/gson-2.8.9.jar
[INFO] Copying snakeyaml-1.29.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/snakeyaml-1.29.jar
[INFO] Copying fastjson-1.2.83.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/fastjson-1.2.83.jar
[INFO] Copying fastjson2-2.0.7.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/fastjson2-2.0.7.jar
[INFO] Copying netty-all-4.1.25.Final.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/netty-all-4.1.25.Final.jar
[INFO] Copying slf4j-api-1.7.25.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/slf4j-api-1.7.25.jar
[INFO] Copying logback-classic-1.2.3.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/logback-classic-1.2.3.jar
[INFO] Copying logback-core-1.2.3.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/logback-core-1.2.3.jar
[INFO] Copying commons-cli-1.4.jar to /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/libs/commons-cli-1.4.jar
[INFO] 
[INFO] --- maven-jar-plugin:3.1.0:jar (default-jar) @ dubbo-hessianlite-client ---
[INFO] Building jar: /home/runner/work/dubbo-awesome/dubbo-awesome/dubbo-hessianlite-client/target/dubbo-hessianlite-client-1.0-SNAPSHOT.jar
[INFO] ------------------------------------------------------------------------
[INFO] Reactor Summary for benchmark-base 1.0-SNAPSHOT:
[INFO] 
[INFO] benchmark-base ..................................... SUCCESS [  3.664 s]
[INFO] server-base ........................................ SUCCESS [  0.381 s]
[INFO] client-base ........................................ SUCCESS [  0.680 s]
[INFO] dubbo-hessianlite-client ........................... SUCCESS [  7.278 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  12.390 s
[INFO] Finished at: 2023-02-09T18:08:24Z
[INFO] ------------------------------------------------------------------------

RUN dubbo-hessianlite-client IN benchmark MODE
command is: java -server -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output= -jar dubbo-hessianlite-client/target/dubbo-hessianlite-client-1.0-SNAPSHOT.jar --warmupIterations=1 --warmupTime=1 --measurementIterations=1 --measurementTime=1

[Ljava.lang.String;@6d03e736
# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 18:08:26.897 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:26.908 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:27.014 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:27.015 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:27.045 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:27.046 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:27.133 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.109
18:08:27.134 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:27.134 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:27.159 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:27.160 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:27.185 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.109
18:08:27.186 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:27.190 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:27.197 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:27.198 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@13f69e38, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:27.521 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
18:08:27.619 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
18:08:27.714 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
18:08:27.910 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:27.921 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:27.922 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:28.357 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
18:08:28.384 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:28.385 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:28.385 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:28.387 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:28.410 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-hessianlite-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:28.633 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.109
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
18:08:28.633 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.109
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
18:08:28.805 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.109:8080 from NettyClient 10.1.0.109 using dubbo version 3.1.0, channel is NettyChannel [channel=[id: 0x7fd10c36, L:/10.1.0.109:54026 - R:/10.1.0.109:8080]], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:28.806 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.109 connect to the server /10.1.0.109:8080, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:28.809 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.109:54026 -> /10.1.0.109:8080 is established., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:28.847 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:28.848 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:28.857 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:28.863 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:28.864 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:28.914 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:29.000 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=1997&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966108909&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:29.001 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=1997&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966108909&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:29.012 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:29.014 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=1997&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966108909&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:29.014 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:29.026 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.109
1.029 ops/ms
Iteration   1: 18:08:31.123 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:31.125 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x7fd10c36, L:/10.1.0.109:54026 - R:/10.1.0.109:8080], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:31.127 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:31.128 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:31.128 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:31.128 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:31.130 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:31.130 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:31.131 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.109:54026 -> /10.1.0.109:8080 is disconnected., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:31.140 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:33.153 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Close dubbo connect: 10.1.0.109:0-->localhost:8080, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:33.153 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] WARN  o.a.d.r.p.d.ReferenceCountExchangeClient -  [DUBBO] localhost:8080 org.apache.dubbo.benchmark.service.UserService safe guard client , should not be called ,must have a bug., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:33.154 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=1997&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966108909&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:33.154 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:33.155 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=1997&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966108909&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:33.155 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:33.155 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:33.155 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:33.157 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:33.157 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:33.158 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:33.158 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:33.158 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:33.158 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:33.158 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:33.160 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:33.160 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:33.160 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:33.161 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:33.161 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:33.161 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:33.166 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:33.166 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:33.168 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@13f69e38, dubbo version: 3.1.0, current host: 10.1.0.109
2.165 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.165 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:38
# Fork: 1 of 1
# Warmup Iteration   1: 18:08:34.974 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:34.979 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:35.035 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:35.037 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:35.062 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:35.063 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:35.113 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.109
18:08:35.113 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:35.113 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:35.117 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:35.118 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:35.126 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.109
18:08:35.126 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:35.128 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:35.131 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:35.131 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5c4f4e57, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:35.287 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
18:08:35.326 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
18:08:35.353 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
18:08:35.462 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:35.468 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:35.469 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:35.666 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
18:08:35.684 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:35.685 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:35.685 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:35.686 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:35.711 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-hessianlite-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:35.844 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.109
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
18:08:35.844 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.109
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
18:08:35.978 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.109:8080 from NettyClient 10.1.0.109 using dubbo version 3.1.0, channel is NettyChannel [channel=[id: 0x9cabe596, L:/10.1.0.109:54860 - R:/10.1.0.109:8080]], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:35.979 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.109 connect to the server /10.1.0.109:8080, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:35.980 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.109:54860 -> /10.1.0.109:8080 is established., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:35.998 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:35.999 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:36.009 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:36.014 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:36.015 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:36.045 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:36.134 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2287&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966116040&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:36.134 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2287&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966116040&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:36.144 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:36.146 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2287&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966116040&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:36.147 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:36.164 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.109
2.316 ops/ms
Iteration   1: 18:08:38.233 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:38.235 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x9cabe596, L:/10.1.0.109:54860 - R:/10.1.0.109:8080], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:38.239 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:38.240 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:38.246 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:38.247 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:38.248 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:38.251 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:38.251 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.109:54860 -> /10.1.0.109:8080 is disconnected., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:38.253 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:40.267 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Close dubbo connect: 10.1.0.109:0-->localhost:8080, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:40.268 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] WARN  o.a.d.r.p.d.ReferenceCountExchangeClient -  [DUBBO] localhost:8080 org.apache.dubbo.benchmark.service.UserService safe guard client , should not be called ,must have a bug., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:40.268 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2287&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966116040&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:40.269 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:40.269 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2287&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966116040&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:40.270 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:40.270 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:40.270 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:40.271 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:40.272 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:40.273 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:40.273 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:40.273 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:40.273 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:40.273 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:40.273 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:40.274 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:40.274 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:40.274 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:40.274 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:40.274 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:40.278 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:40.278 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:40.279 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-30] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5c4f4e57, dubbo version: 3.1.0, current host: 10.1.0.109
5.735 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.735 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 18:08:42.119 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:42.122 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:42.165 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:42.166 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:42.185 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:42.185 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:42.231 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.109
18:08:42.231 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:42.232 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:42.236 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:42.236 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:42.244 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.109
18:08:42.244 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:42.246 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:42.249 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:42.249 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5f9888b9, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:42.417 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
18:08:42.483 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
18:08:42.530 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
18:08:42.625 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:42.631 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:42.637 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:42.876 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
18:08:42.894 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:42.894 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:42.895 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:42.895 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:42.915 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-hessianlite-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:43.048 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.109
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
18:08:43.048 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.109
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
18:08:43.144 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.109:54876 -> /10.1.0.109:8080 is established., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:43.146 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.109:8080 from NettyClient 10.1.0.109 using dubbo version 3.1.0, channel is NettyChannel [channel=[id: 0x17c6199c, L:/10.1.0.109:54876 - R:/10.1.0.109:8080]], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:43.147 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.109 connect to the server /10.1.0.109:8080, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:43.172 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:43.173 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:43.183 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:43.188 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:43.189 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:43.240 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:43.328 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2369&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966123231&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:43.329 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2369&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966123231&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:43.340 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:43.343 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2369&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966123231&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:43.344 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:43.360 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.109
1.459 ops/ms
Iteration   1: 18:08:45.447 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:45.449 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x17c6199c, L:/10.1.0.109:54876 - R:/10.1.0.109:8080], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:45.450 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.109:54876 -> /10.1.0.109:8080 is disconnected., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:45.453 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:45.453 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:45.454 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:45.459 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:45.461 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:45.461 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:45.462 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:47.488 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Close dubbo connect: 10.1.0.109:0-->localhost:8080, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:47.489 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] WARN  o.a.d.r.p.d.ReferenceCountExchangeClient -  [DUBBO] localhost:8080 org.apache.dubbo.benchmark.service.UserService safe guard client , should not be called ,must have a bug., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:47.489 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2369&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966123231&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:47.490 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:47.491 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2369&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966123231&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:47.491 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:47.491 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:47.491 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:47.492 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:47.493 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:47.494 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:47.494 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:47.494 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:47.494 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:47.494 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:47.495 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:47.495 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:47.495 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:47.495 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:47.496 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:47.496 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:47.499 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:47.499 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:47.500 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-13] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5f9888b9, dubbo version: 3.1.0, current host: 10.1.0.109
3.861 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.861 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 18:08:49.299 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:49.303 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:49.354 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:49.356 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:49.379 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:49.379 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:49.433 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.109
18:08:49.433 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:49.433 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:49.437 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:49.438 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:49.445 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.109
18:08:49.446 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:49.448 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:49.451 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:49.451 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@13f69e38, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:49.614 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
18:08:49.668 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
18:08:49.714 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
18:08:49.841 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:49.846 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:49.848 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:50.089 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
18:08:50.107 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:50.109 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:50.109 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:50.110 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:50.137 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-hessianlite-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:50.280 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.109
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
18:08:50.280 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.109
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
18:08:50.365 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.109:8080 from NettyClient 10.1.0.109 using dubbo version 3.1.0, channel is NettyChannel [channel=[id: 0xd3b865b3, L:/10.1.0.109:58090 - R:/10.1.0.109:8080]], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:50.365 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.109 connect to the server /10.1.0.109:8080, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:50.369 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.109:58090 -> /10.1.0.109:8080 is established., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:50.404 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:50.406 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:50.426 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:50.434 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:50.435 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:50.490 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:50.542 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2449&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966130466&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:50.542 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2449&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966130466&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:50.552 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:50.553 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2449&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966130466&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:50.554 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:50.560 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.109
0.813 ops/ms
Iteration   1: 18:08:52.748 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:52.750 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xd3b865b3, L:/10.1.0.109:58090 - R:/10.1.0.109:8080], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:52.751 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.109:58090 -> /10.1.0.109:8080 is disconnected., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:52.754 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:52.755 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:52.755 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:52.755 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:52.757 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:52.758 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:52.759 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:54.788 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Close dubbo connect: 10.1.0.109:0-->localhost:8080, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:54.789 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] WARN  o.a.d.r.p.d.ReferenceCountExchangeClient -  [DUBBO] localhost:8080 org.apache.dubbo.benchmark.service.UserService safe guard client , should not be called ,must have a bug., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:54.789 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2449&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966130466&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:54.790 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:54.791 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2449&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966130466&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:54.791 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:54.791 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:54.791 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:54.792 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:54.793 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:54.794 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:54.794 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:54.794 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:54.794 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:54.794 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:54.794 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:54.794 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:54.794 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:54.795 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:54.795 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:54.795 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:54.799 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:54.799 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:54.800 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-8] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@13f69e38, dubbo version: 3.1.0, current host: 10.1.0.109
1.315 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.315 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 18:08:56.634 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:56.638 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:56.704 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:56.706 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:56.725 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:56.726 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:56.774 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.109
18:08:56.774 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:56.774 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:56.778 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:56.779 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:56.787 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.109
18:08:56.787 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:56.789 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:56.792 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:56.792 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@30df9794, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:56.968 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
18:08:57.006 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
18:08:57.035 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
18:08:57.166 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:57.175 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:57.178 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:57.401 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
18:08:57.423 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:57.424 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:57.424 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:57.424 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:57.456 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-hessianlite-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:57.600 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.109
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
18:08:57.600 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.109
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
18:08:57.710 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.109:60720 -> /10.1.0.109:8080 is established., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:57.712 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.109:8080 from NettyClient 10.1.0.109 using dubbo version 3.1.0, channel is NettyChannel [channel=[id: 0xe85b1c21, L:/10.1.0.109:60720 - R:/10.1.0.109:8080]], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:57.714 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.109 connect to the server /10.1.0.109:8080, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:57.738 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:57.740 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:57.749 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:57.756 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:57.757 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:57.785 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:57.871 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2531&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966137780&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:57.872 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2531&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966137780&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:57.881 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:08:57.882 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2531&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966137780&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.109
18:08:57.883 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.109
18:08:57.890 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.109
21.990 ±(99.9%) 0.331 ms/op
Iteration   1: 18:08:59.997 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:00.000 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xe85b1c21, L:/10.1.0.109:60720 - R:/10.1.0.109:8080], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:00.004 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:00.006 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:00.007 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:00.011 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:00.015 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:00.018 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:00.019 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:00.017 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.109:60720 -> /10.1.0.109:8080 is disconnected., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:02.032 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Close dubbo connect: 10.1.0.109:0-->localhost:8080, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:02.032 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.r.p.d.ReferenceCountExchangeClient -  [DUBBO] localhost:8080 org.apache.dubbo.benchmark.service.UserService safe guard client , should not be called ,must have a bug., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:02.033 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2531&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966137780&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:02.033 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:02.034 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2531&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966137780&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:02.034 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:02.034 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:02.034 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:02.035 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:02.036 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:02.037 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:02.037 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:02.037 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:02.037 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:02.038 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:02.039 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:02.039 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:02.039 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:02.040 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:02.040 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:02.040 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:02.044 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:02.045 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:02.045 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@30df9794, dubbo version: 3.1.0, current host: 10.1.0.109
11.125 ±(99.9%) 0.033 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  11.125 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:53
# Fork: 1 of 1
# Warmup Iteration   1: 18:09:03.869 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:03.872 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:03.917 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:03.919 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:03.937 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:03.938 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:03.982 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.109
18:09:03.983 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:03.983 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:03.987 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:03.988 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:03.995 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.109
18:09:03.995 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:03.998 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:04.000 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:04.000 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5f9888b9, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:04.158 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
18:09:04.218 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
18:09:04.268 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
18:09:04.384 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:04.393 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:04.400 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:04.597 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
18:09:04.616 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:04.617 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:04.617 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:04.618 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:04.638 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-hessianlite-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:04.776 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.109
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
18:09:04.776 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.109
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
18:09:04.867 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.109:8080 from NettyClient 10.1.0.109 using dubbo version 3.1.0, channel is NettyChannel [channel=[id: 0xadcac816, L:/10.1.0.109:53126 - R:/10.1.0.109:8080]], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:04.869 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.109 connect to the server /10.1.0.109:8080, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:04.869 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.109:53126 -> /10.1.0.109:8080 is established., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:04.891 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:04.893 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:04.903 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:04.909 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:04.910 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:04.939 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:05.013 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2673&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966144934&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:05.014 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2673&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966144934&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:05.020 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:05.022 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2673&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966144934&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:05.023 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:05.028 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.109
8.759 ±(99.9%) 0.127 ms/op
Iteration   1: 18:09:07.234 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:07.237 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xadcac816, L:/10.1.0.109:53126 - R:/10.1.0.109:8080], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:07.239 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:07.241 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:07.241 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:07.245 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:07.248 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.109:53126 -> /10.1.0.109:8080 is disconnected., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:07.248 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:07.250 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:07.251 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:09.260 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Close dubbo connect: 10.1.0.109:0-->localhost:8080, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:09.261 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] WARN  o.a.d.r.p.d.ReferenceCountExchangeClient -  [DUBBO] localhost:8080 org.apache.dubbo.benchmark.service.UserService safe guard client , should not be called ,must have a bug., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:09.261 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2673&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966144934&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:09.261 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:09.263 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,exportInstanceMetadata,getExportedServiceURLs,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2673&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966144934&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:09.263 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:09.263 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:09.264 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:09.265 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:09.265 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:09.266 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:09.266 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:09.266 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:09.266 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:09.266 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:09.267 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:09.267 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:09.267 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:09.268 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:09.268 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:09.268 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:09.272 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:09.272 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:09.272 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-23] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5f9888b9, dubbo version: 3.1.0, current host: 10.1.0.109
4.163 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.163 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:45
# Fork: 1 of 1
# Warmup Iteration   1: 18:09:11.054 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:11.057 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:11.106 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:11.107 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:11.125 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:11.126 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:11.170 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.109
18:09:11.171 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:11.171 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:11.175 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:11.175 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:11.183 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.109
18:09:11.183 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:11.185 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:11.187 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:11.188 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@13f69e38, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:11.339 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
18:09:11.374 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
18:09:11.401 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
18:09:11.506 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:11.518 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:11.520 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:11.731 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
18:09:11.748 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:11.748 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:11.749 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:11.749 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:11.767 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-hessianlite-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:11.891 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.109
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
18:09:11.892 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.109
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
18:09:11.974 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.109:8080 from NettyClient 10.1.0.109 using dubbo version 3.1.0, channel is NettyChannel [channel=[id: 0xac44c27b, L:/10.1.0.109:53132 - R:/10.1.0.109:8080]], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:11.974 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.109 connect to the server /10.1.0.109:8080, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:11.977 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.109:53132 -> /10.1.0.109:8080 is established., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:11.994 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:11.996 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:12.005 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:12.010 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:12.011 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:12.037 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:12.105 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2754&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966152032&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:12.106 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2754&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966152032&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:12.113 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:12.114 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2754&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966152032&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:12.115 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:12.124 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.109
9.185 ±(99.9%) 0.129 ms/op
Iteration   1: 18:09:14.172 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:14.174 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xac44c27b, L:/10.1.0.109:53132 - R:/10.1.0.109:8080], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:14.177 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:14.182 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:14.182 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:14.182 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:14.183 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.109:53132 -> /10.1.0.109:8080 is disconnected., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:14.185 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:14.185 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:14.186 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:16.194 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Close dubbo connect: 10.1.0.109:0-->localhost:8080, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:16.194 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] WARN  o.a.d.r.p.d.ReferenceCountExchangeClient -  [DUBBO] localhost:8080 org.apache.dubbo.benchmark.service.UserService safe guard client , should not be called ,must have a bug., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:16.195 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2754&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966152032&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:16.195 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:16.196 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2754&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966152032&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:16.196 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:16.196 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:16.197 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:16.198 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:16.198 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:16.199 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:16.199 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:16.199 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:16.199 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:16.199 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:16.200 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:16.200 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:16.200 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:16.200 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:16.201 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:16.201 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:16.204 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:16.204 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:16.205 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-24] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@13f69e38, dubbo version: 3.1.0, current host: 10.1.0.109
4.319 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.319 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:37
# Fork: 1 of 1
# Warmup Iteration   1: 18:09:18.041 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:18.045 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:18.089 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:18.090 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:18.108 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:18.109 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:18.152 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.109
18:09:18.153 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:18.153 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:18.158 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:18.158 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:18.167 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.109
18:09:18.168 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:18.170 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:18.172 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:18.172 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5f9888b9, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:18.327 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
18:09:18.362 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
18:09:18.390 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
18:09:18.481 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:18.491 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:18.495 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:18.709 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
18:09:18.727 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:18.728 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:18.728 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:18.728 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:18.747 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-hessianlite-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:18.884 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.109
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
18:09:18.884 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.109
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
18:09:18.994 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.109:49034 -> /10.1.0.109:8080 is established., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:19.001 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.109:8080 from NettyClient 10.1.0.109 using dubbo version 3.1.0, channel is NettyChannel [channel=[id: 0x454de143, L:/10.1.0.109:49034 - R:/10.1.0.109:8080]], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:19.002 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.109 connect to the server /10.1.0.109:8080, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:19.022 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:19.024 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:19.033 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:19.039 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:19.040 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:19.069 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:19.137 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2835&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966159063&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:19.138 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2835&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966159063&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:19.144 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:19.145 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2835&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966159063&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:19.146 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:19.152 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.109
28.445 ±(99.9%) 0.811 ms/op
Iteration   1: 18:09:21.278 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:21.280 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x454de143, L:/10.1.0.109:49034 - R:/10.1.0.109:8080], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:21.283 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:21.284 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:21.283 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.109:49034 -> /10.1.0.109:8080 is disconnected., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:21.287 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:21.288 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:21.289 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:21.289 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:21.290 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:23.298 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Close dubbo connect: 10.1.0.109:0-->localhost:8080, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:23.298 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] WARN  o.a.d.r.p.d.ReferenceCountExchangeClient -  [DUBBO] localhost:8080 org.apache.dubbo.benchmark.service.UserService safe guard client , should not be called ,must have a bug., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:23.299 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2835&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966159063&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:23.299 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:23.301 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2835&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966159063&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:23.301 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:23.301 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:23.301 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:23.302 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:23.303 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:23.303 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:23.304 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:23.304 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:23.304 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:23.304 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:23.304 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:23.304 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:23.304 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:23.305 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:23.305 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:23.305 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:23.316 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:23.317 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:23.317 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-27] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5f9888b9, dubbo version: 3.1.0, current host: 10.1.0.109
17.311 ±(99.9%) 0.071 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.311 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:29
# Fork: 1 of 1
# Warmup Iteration   1: 18:09:25.158 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:25.162 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:25.209 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:25.211 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:25.229 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:25.230 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:25.279 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.109
18:09:25.280 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:25.280 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:25.284 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:25.284 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:25.292 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.109
18:09:25.292 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:25.294 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:25.297 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:25.297 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5f9888b9, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:25.450 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
18:09:25.502 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
18:09:25.558 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
18:09:25.638 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:25.644 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:25.645 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:25.835 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
18:09:25.857 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:25.857 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:25.857 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:25.858 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:25.883 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-hessianlite-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:26.011 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.109
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
18:09:26.012 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.109
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
18:09:26.093 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.109:8080 from NettyClient 10.1.0.109 using dubbo version 3.1.0, channel is NettyChannel [channel=[id: 0xb845640b, L:/10.1.0.109:46506 - R:/10.1.0.109:8080]], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:26.095 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.109:46506 -> /10.1.0.109:8080 is established., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:26.095 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.109 connect to the server /10.1.0.109:8080, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:26.134 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:26.136 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:26.149 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:26.155 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:26.156 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:26.188 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:26.261 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2916&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966166182&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:26.262 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2916&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966166182&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:26.271 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:26.272 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2916&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966166182&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:26.273 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:26.279 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.109
15.578 ±(99.9%) 0.502 ms/op
Iteration   1: 18:09:28.421 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:28.423 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xb845640b, L:/10.1.0.109:46506 - R:/10.1.0.109:8080], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:28.425 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:28.425 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:28.425 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:28.425 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:28.427 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:28.427 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:28.428 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.109:46506 -> /10.1.0.109:8080 is disconnected., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:28.429 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:30.437 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Close dubbo connect: 10.1.0.109:0-->localhost:8080, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:30.438 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] WARN  o.a.d.r.p.d.ReferenceCountExchangeClient -  [DUBBO] localhost:8080 org.apache.dubbo.benchmark.service.UserService safe guard client , should not be called ,must have a bug., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:30.438 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2916&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966166182&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:30.438 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:30.439 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getAndListenInstanceMetadata,getExportedURLs,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2916&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966166182&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:30.439 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:30.439 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:30.440 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:30.441 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:30.441 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:30.442 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:30.442 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:30.442 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:30.442 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:30.443 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:30.443 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:30.443 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:30.443 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:30.444 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:30.447 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:30.447 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:30.452 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:30.453 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:30.455 [org.apache.dubbo.benchmark.Client.createUser-jmh-worker-12] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5f9888b9, dubbo version: 3.1.0, current host: 10.1.0.109
7.511 ±(99.9%) 0.159 ms/op
                 createUser·p0.00:   1.346 ms/op
                 createUser·p0.50:   7.717 ms/op
                 createUser·p0.90:   8.684 ms/op
                 createUser·p0.95:   11.176 ms/op
                 createUser·p0.99:   13.469 ms/op
                 createUser·p0.999:  39.715 ms/op
                 createUser·p0.9999: 40.174 ms/op
                 createUser·p1.00:   40.174 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4296
  mean =      7.511 ±(99.9%) 0.159 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 521 
    [ 5.000, 10.000) = 3497 
    [10.000, 15.000) = 246 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 20 
    [35.000, 40.000) = 11 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.346 ms/op
     p(50.0000) =      7.717 ms/op
     p(90.0000) =      8.684 ms/op
     p(95.0000) =     11.176 ms/op
     p(99.0000) =     13.469 ms/op
     p(99.9000) =     39.715 ms/op
     p(99.9900) =     40.174 ms/op
     p(99.9990) =     40.174 ms/op
     p(99.9999) =     40.174 ms/op
    p(100.0000) =     40.174 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 18:09:32.380 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:32.384 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:32.449 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:32.452 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:32.472 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:32.473 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:32.516 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.109
18:09:32.517 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:32.517 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:32.521 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:32.522 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:32.529 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.109
18:09:32.530 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:32.532 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:32.534 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:32.535 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5c4f4e57, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:32.688 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
18:09:32.722 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
18:09:32.759 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
18:09:32.859 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:32.865 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:32.866 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:33.053 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
18:09:33.071 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:33.072 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:33.072 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:33.073 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:33.093 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-hessianlite-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:33.224 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.109
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
18:09:33.224 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.109
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
18:09:33.310 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.109:8080 from NettyClient 10.1.0.109 using dubbo version 3.1.0, channel is NettyChannel [channel=[id: 0xf4cf19a5, L:/10.1.0.109:46522 - R:/10.1.0.109:8080]], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:33.313 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.109 connect to the server /10.1.0.109:8080, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:33.313 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.109:46522 -> /10.1.0.109:8080 is established., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:33.336 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:33.337 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:33.347 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:33.352 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:33.353 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:33.406 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:33.476 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2997&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966173376&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:33.477 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2997&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966173376&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:33.487 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:33.488 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2997&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966173376&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:33.489 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:33.496 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.109
8.246 ±(99.9%) 0.260 ms/op
Iteration   1: 18:09:35.639 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:35.642 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xf4cf19a5, L:/10.1.0.109:46522 - R:/10.1.0.109:8080], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:35.646 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:35.647 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:35.647 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:35.647 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:35.648 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.109:46522 -> /10.1.0.109:8080 is disconnected., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:35.649 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:35.656 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:35.657 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:37.664 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Close dubbo connect: 10.1.0.109:0-->localhost:8080, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:37.665 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] WARN  o.a.d.r.p.d.ReferenceCountExchangeClient -  [DUBBO] localhost:8080 org.apache.dubbo.benchmark.service.UserService safe guard client , should not be called ,must have a bug., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:37.665 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2997&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966173376&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:37.666 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:37.669 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=2997&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966173376&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:37.669 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:37.669 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:37.670 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:37.671 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:37.671 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:37.672 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:37.672 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:37.672 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:37.673 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:37.673 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:37.673 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:37.673 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:37.673 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:37.674 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:37.674 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:37.674 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:37.678 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:37.678 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:37.679 [org.apache.dubbo.benchmark.Client.existUser-jmh-worker-21] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@5c4f4e57, dubbo version: 3.1.0, current host: 10.1.0.109
4.717 ±(99.9%) 0.078 ms/op
                 existUser·p0.00:   0.999 ms/op
                 existUser·p0.50:   4.473 ms/op
                 existUser·p0.90:   5.382 ms/op
                 existUser·p0.95:   8.794 ms/op
                 existUser·p0.99:   14.549 ms/op
                 existUser·p0.999:  15.295 ms/op
                 existUser·p0.9999: 16.073 ms/op
                 existUser·p1.00:   16.073 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 6784
  mean =      4.717 ±(99.9%) 0.078 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 23 
    [ 1.250,  2.500) = 210 
    [ 2.500,  3.750) = 1329 
    [ 3.750,  5.000) = 4136 
    [ 5.000,  6.250) = 564 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 106 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 78 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.999 ms/op
     p(50.0000) =      4.473 ms/op
     p(90.0000) =      5.382 ms/op
     p(95.0000) =      8.794 ms/op
     p(99.0000) =     14.549 ms/op
     p(99.9000) =     15.295 ms/op
     p(99.9900) =     16.073 ms/op
     p(99.9990) =     16.073 ms/op
     p(99.9999) =     16.073 ms/op
    p(100.0000) =     16.073 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 18:09:39.533 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:39.537 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:39.603 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:39.604 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:39.626 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:39.626 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:39.669 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.109
18:09:39.670 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:39.670 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:39.674 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:39.674 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:39.687 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.109
18:09:39.687 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:39.689 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:39.692 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:39.692 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4708873a, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:39.855 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
18:09:39.915 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
18:09:39.956 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
18:09:40.077 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:40.091 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:40.097 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:40.288 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
18:09:40.306 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:40.307 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:40.307 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:40.308 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:40.326 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-hessianlite-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:40.451 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.109
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
18:09:40.452 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.109
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
18:09:40.559 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.109:8080 from NettyClient 10.1.0.109 using dubbo version 3.1.0, channel is NettyChannel [channel=[id: 0xb455cb95, L:/10.1.0.109:41208 - R:/10.1.0.109:8080]], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:40.560 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.109 connect to the server /10.1.0.109:8080, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:40.562 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.109:41208 -> /10.1.0.109:8080 is established., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:40.588 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:40.589 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:40.601 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:40.607 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:40.608 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:40.659 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:40.727 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3077&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966180654&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:40.727 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3077&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966180654&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:40.736 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:40.737 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3077&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966180654&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:40.738 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:40.744 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-2] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.109
10.266 ±(99.9%) 0.324 ms/op
Iteration   1: 18:09:42.882 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:42.884 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0xb455cb95, L:/10.1.0.109:41208 - R:/10.1.0.109:8080], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:42.885 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.109:41208 -> /10.1.0.109:8080 is disconnected., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:42.890 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:42.890 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:42.890 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:42.891 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:42.892 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:42.895 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:42.896 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:44.904 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Close dubbo connect: 10.1.0.109:0-->localhost:8080, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:44.905 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] WARN  o.a.d.r.p.d.ReferenceCountExchangeClient -  [DUBBO] localhost:8080 org.apache.dubbo.benchmark.service.UserService safe guard client , should not be called ,must have a bug., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:44.906 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3077&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966180654&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:44.906 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:44.907 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3077&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966180654&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:44.908 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:44.908 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:44.908 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:44.909 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:44.910 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:44.910 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:44.910 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:44.911 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:44.911 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:44.911 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:44.911 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:44.911 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:44.911 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:44.912 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:44.912 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:44.912 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:44.924 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:44.925 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:44.926 [org.apache.dubbo.benchmark.Client.getUser-jmh-worker-10] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@4708873a, dubbo version: 3.1.0, current host: 10.1.0.109
4.347 ±(99.9%) 0.061 ms/op
                 getUser·p0.00:   2.013 ms/op
                 getUser·p0.50:   4.047 ms/op
                 getUser·p0.90:   5.399 ms/op
                 getUser·p0.95:   5.857 ms/op
                 getUser·p0.99:   8.405 ms/op
                 getUser·p0.999:  24.969 ms/op
                 getUser·p0.9999: 25.002 ms/op
                 getUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7359
  mean =      4.347 ±(99.9%) 0.061 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 6096 
    [ 5.000,  7.500) = 1148 
    [ 7.500, 10.000) = 58 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.013 ms/op
     p(50.0000) =      4.047 ms/op
     p(90.0000) =      5.399 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      8.405 ms/op
     p(99.9000) =     24.969 ms/op
     p(99.9900) =     25.002 ms/op
     p(99.9990) =     25.002 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 18:09:46.891 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from null to Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:46.894 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:46.951 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.0](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:46.952 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.0.0] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:46.973 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:46.974 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:47.019 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from null to Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.109
18:09:47.019 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.rpc.model.ApplicationModel -  [DUBBO] Dubbo Application[1.1](unknown) is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:47.019 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.0] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:47.024 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:47.024 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:47.035 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default application: Dubbo Application[1.1](unknown), dubbo version: 3.1.0, current host: 10.1.0.109
18:09:47.035 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.rpc.model.ScopeModel -  [DUBBO] Dubbo Module[1.1.1] is created, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:47.043 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.c.AbstractConfigManager -  [DUBBO] Config settings: {dubbo.config.mode=STRICT, dubbo.config.ignore-duplicated-interface=false}, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:47.046 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Use default module model of target application: Dubbo Module[1.1.1], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:47.046 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Bind Dubbo Module[1.1.1] to spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@13f69e38, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:47.200 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.b.f.a.ReferenceAnnotationBeanPostProcessor - class org.apache.dubbo.config.spring.beans.factory.annotation.ReferenceAnnotationBeanPostProcessor was destroying!
18:09:47.235 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - loading dubbo config beans ...
18:09:47.281 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.c.DubboConfigBeanInitializer - dubbo config beans are loaded.
18:09:47.379 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:47.389 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:47.390 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has been initialized!, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:47.645 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.s.reference.ReferenceCreator - The configBean[type:ReferenceConfig] has been built.
18:09:47.673 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:47.674 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:47.674 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is starting., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:47.675 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has started., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:47.710 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.metadata.MappingCacheManager -  [DUBBO] Successfully loaded mapping cache from file .mapping.dubbo-hessianlite-client, entries 0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:47.867 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] ERROR org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server can not bind localhost:22222, dubbo version: 3.1.0, current host: 10.1.0.109
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
18:09:47.868 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.q.protocol.QosProtocolWrapper -  [DUBBO] Fail to start qos server: , dubbo version: 3.1.0, current host: 10.1.0.109
java.net.BindException: Address already in use
	at sun.nio.ch.Net.bind0(Native Method)
	at sun.nio.ch.Net.bind(Net.java:461)
	at sun.nio.ch.Net.bind(Net.java:453)
	at sun.nio.ch.ServerSocketChannelImpl.bind(ServerSocketChannelImpl.java:222)
	at io.netty.channel.socket.nio.NioServerSocketChannel.doBind(NioServerSocketChannel.java:134)
	at io.netty.channel.AbstractChannel$AbstractUnsafe.bind(AbstractChannel.java:562)
	at io.netty.channel.DefaultChannelPipeline$HeadContext.bind(DefaultChannelPipeline.java:1334)
	at io.netty.channel.AbstractChannelHandlerContext.invokeBind(AbstractChannelHandlerContext.java:506)
	at io.netty.channel.AbstractChannelHandlerContext.bind(AbstractChannelHandlerContext.java:491)
	at io.netty.channel.DefaultChannelPipeline.bind(DefaultChannelPipeline.java:973)
	at io.netty.channel.AbstractChannel.bind(AbstractChannel.java:260)
	at io.netty.bootstrap.AbstractBootstrap$2.run(AbstractBootstrap.java:356)
	at io.netty.util.concurrent.AbstractEventExecutor.safeExecute(AbstractEventExecutor.java:164)
	at io.netty.util.concurrent.SingleThreadEventExecutor.runAllTasks(SingleThreadEventExecutor.java:469)
	at io.netty.channel.nio.NioEventLoop.run(NioEventLoop.java:503)
	at io.netty.util.concurrent.SingleThreadEventExecutor$4.run(SingleThreadEventExecutor.java:986)
	at io.netty.util.internal.ThreadExecutorMap$2.run(ThreadExecutorMap.java:74)
	at io.netty.util.concurrent.FastThreadLocalRunnable.run(FastThreadLocalRunnable.java:30)
	at java.lang.Thread.run(Thread.java:750)
18:09:47.951 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Successfully connect to server /10.1.0.109:8080 from NettyClient 10.1.0.109 using dubbo version 3.1.0, channel is NettyChannel [channel=[id: 0x08841d54, L:/10.1.0.109:49042 - R:/10.1.0.109:8080]], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:47.954 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractClient -  [DUBBO] Start NettyClient /10.1.0.109 connect to the server /10.1.0.109:8080, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:47.954 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.109:49042 -> /10.1.0.109:8080 is established., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:47.979 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.dubbo.config.ReferenceConfig -  [DUBBO] Referred dubbo service: [org.apache.dubbo.benchmark.service.UserService]. it's not GenericService reference, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:47.981 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.a.d.r.c.metadata.MetadataUtils -  [DUBBO] Remote Metadata Report Server is not provided or unavailable, will stop registering service definition to remote center!, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:48.002 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has started., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:48.009 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Metadata Service Port hasn't been set will use default protocol defined in protocols., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:48.011 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] Using dubbo protocol to export metadata service on port -1, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:48.089 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] WARN  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Use random available port(20880) for protocol dubbo, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:48.175 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to local registry url : injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3156&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966188077&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:48.176 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.apache.dubbo.config.ServiceConfig -  [DUBBO] Export dubbo service org.apache.dubbo.metadata.MetadataService to url dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3156&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966188077&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:48.184 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Start NettyServer bind /0.0.0.0:20880, export /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:48.185 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.m.ConfigurableMetadataServiceExporter -  [DUBBO] The MetadataService exports urls : [dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3156&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966188077&version=1.0.0], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:48.186 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.r.c.m.ServiceInstanceMetadataUtils -  [DUBBO] Start registering instance address to registry., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:48.196 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-1] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is ready., dubbo version: 3.1.0, current host: 10.1.0.109
28.361 ±(99.9%) 1.098 ms/op
Iteration   1: 18:09:50.361 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:50.364 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  o.a.d.r.t.netty4.NettyChannel -  [DUBBO] Close netty channel [id: 0x08841d54, L:/10.1.0.109:49042 - R:/10.1.0.109:8080], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:50.365 [NettyClientWorker-4-1] INFO  o.a.d.r.t.netty4.NettyClientHandler -  [DUBBO] The connection of /10.1.0.109:49042 -> /10.1.0.109:8080 is disconnected., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:50.366 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.1] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:50.367 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default application from Dubbo Application[1.1](dubbo-hessianlite-client) to null, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:50.367 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:50.367 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:50.368 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Destroying protocol [DubboProtocol] ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:50.369 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Closing dubbo server: /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:50.369 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  o.a.d.r.transport.AbstractServer -  [DUBBO] Close NettyServer bind /0.0.0.0:20880, export /10.1.0.109:20880, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:52.377 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Close dubbo connect: 10.1.0.109:0-->localhost:8080, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:52.377 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] WARN  o.a.d.r.p.d.ReferenceCountExchangeClient -  [DUBBO] localhost:8080 org.apache.dubbo.benchmark.service.UserService safe guard client , should not be called ,must have a bug., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:52.378 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  o.a.d.r.protocol.dubbo.DubboProtocol -  [DUBBO] Unexport service: dubbo://10.1.0.109:20880/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3156&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966188077&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:52.378 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:52.379 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  o.a.d.r.protocol.injvm.InjvmProtocol -  [DUBBO] Unexport service: injvm://127.0.0.1/org.apache.dubbo.metadata.MetadataService?anyhost=true&application=dubbo-hessianlite-client&background=false&bind.ip=10.1.0.109&bind.port=20880&connections=1&corethreads=2&delay=0&deprecated=false&dubbo=2.0.2&dynamic=true&executes=100&generic=false&getAndListenInstanceMetadata.1.callback=true&getAndListenInstanceMetadata.return=true&getAndListenInstanceMetadata.sent=true&group=dubbo-hessianlite-client&interface=org.apache.dubbo.metadata.MetadataService&methods=getMetadataURL,isMetadataService,getExportedURLs,getAndListenInstanceMetadata,serviceName,getSubscribedURLs,version,getExportedServiceURLs,exportInstanceMetadata,getMetadataInfo,toSortedStrings,getMetadataInfos,getServiceDefinition,getInstanceMetadataChangedListenerMap&pid=3156&register=false&release=3.1.0&revision=3.1.0&side=provider&threadpool=cached&threads=100&timestamp=1675966188077&version=1.0.0, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:52.379 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  org.apache.dubbo.qos.server.Server -  [DUBBO] qos-server stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:52.379 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:52.380 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.1.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:52.381 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:52.381 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.1](dubbo-hessianlite-client) has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:52.382 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Destroying default framework model: Dubbo Framework[1], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:52.382 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroying ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:52.382 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:52.382 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  o.a.d.r.support.RegistryManager -  [DUBBO] Close all registries [], dubbo version: 3.1.0, current host: 10.1.0.109
18:09:52.382 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] is stopping., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:52.382 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  o.a.d.c.deploy.DefaultModuleDeployer -  [DUBBO] Dubbo Module[1.0.0] has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:52.383 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  o.a.d.c.t.m.DefaultExecutorRepository -  [DUBBO] destroying application executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:52.383 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  o.a.d.c.d.DefaultApplicationDeployer -  [DUBBO] Dubbo Application[1.0](DUBBO_INTERNAL_APPLICATION) has stopped., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:52.383 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Dubbo Framework[1] is destroyed, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:52.383 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  o.a.dubbo.rpc.model.FrameworkModel -  [DUBBO] Reset global default framework from Dubbo Framework[1] to null, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:52.383 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Destroying global resources ..., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:52.388 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  o.a.d.c.r.GlobalResourcesRepository -  [DUBBO] Dubbo is completely destroyed, dubbo version: 3.1.0, current host: 10.1.0.109
18:09:52.389 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  o.a.d.c.t.m.FrameworkExecutorRepository -  [DUBBO] destroying framework executor repository .., dubbo version: 3.1.0, current host: 10.1.0.109
18:09:52.389 [org.apache.dubbo.benchmark.Client.listUser-jmh-worker-10] INFO  o.a.d.c.s.c.DubboSpringInitializer -  [DUBBO] Unbind Dubbo Module[1.1.1] from spring container: org.springframework.beans.factory.support.DefaultListableBeanFactory@13f69e38, dubbo version: 3.1.0, current host: 10.1.0.109
20.541 ±(99.9%) 0.335 ms/op
                 listUser·p0.00:   5.767 ms/op
                 listUser·p0.50:   20.316 ms/op
                 listUser·p0.90:   25.526 ms/op
                 listUser·p0.95:   26.247 ms/op
                 listUser·p0.99:   30.091 ms/op
                 listUser·p0.999:  35.346 ms/op
                 listUser·p0.9999: 35.848 ms/op
                 listUser·p1.00:   35.848 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1589
  mean =     20.541 ±(99.9%) 0.335 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 6 
    [ 7.500, 10.000) = 42 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 517 
    [20.000, 22.500) = 467 
    [22.500, 25.000) = 192 
    [25.000, 27.500) = 144 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      5.767 ms/op
     p(50.0000) =     20.316 ms/op
     p(90.0000) =     25.526 ms/op
     p(95.0000) =     26.247 ms/op
     p(99.0000) =     30.091 ms/op
     p(99.9000) =     35.346 ms/op
     p(99.9900) =     35.848 ms/op
     p(99.9990) =     35.848 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


# Run complete. Total time: 00:01:28

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.165          ops/ms
Client.existUser                       thrpt         5.735          ops/ms
Client.getUser                         thrpt         3.861          ops/ms
Client.listUser                        thrpt         1.315          ops/ms
Client.createUser                       avgt        11.125           ms/op
Client.existUser                        avgt         4.163           ms/op
Client.getUser                          avgt         4.319           ms/op
Client.listUser                         avgt        17.311           ms/op
Client.createUser                     sample  4296   7.511 ± 0.159   ms/op
Client.createUser:createUser·p0.00    sample         1.346           ms/op
Client.createUser:createUser·p0.50    sample         7.717           ms/op
Client.createUser:createUser·p0.90    sample         8.684           ms/op
Client.createUser:createUser·p0.95    sample        11.176           ms/op
Client.createUser:createUser·p0.99    sample        13.469           ms/op
Client.createUser:createUser·p0.999   sample        39.715           ms/op
Client.createUser:createUser·p0.9999  sample        40.174           ms/op
Client.createUser:createUser·p1.00    sample        40.174           ms/op
Client.existUser                      sample  6784   4.717 ± 0.078   ms/op
Client.existUser:existUser·p0.00      sample         0.999           ms/op
Client.existUser:existUser·p0.50      sample         4.473           ms/op
Client.existUser:existUser·p0.90      sample         5.382           ms/op
Client.existUser:existUser·p0.95      sample         8.794           ms/op
Client.existUser:existUser·p0.99      sample        14.549           ms/op
Client.existUser:existUser·p0.999     sample        15.295           ms/op
Client.existUser:existUser·p0.9999    sample        16.073           ms/op
Client.existUser:existUser·p1.00      sample        16.073           ms/op
Client.getUser                        sample  7359   4.347 ± 0.061   ms/op
Client.getUser:getUser·p0.00          sample         2.013           ms/op
Client.getUser:getUser·p0.50          sample         4.047           ms/op
Client.getUser:getUser·p0.90          sample         5.399           ms/op
Client.getUser:getUser·p0.95          sample         5.857           ms/op
Client.getUser:getUser·p0.99          sample         8.405           ms/op
Client.getUser:getUser·p0.999         sample        24.969           ms/op
Client.getUser:getUser·p0.9999        sample        25.002           ms/op
Client.getUser:getUser·p1.00          sample        25.002           ms/op
Client.listUser                       sample  1589  20.541 ± 0.335   ms/op
Client.listUser:listUser·p0.00        sample         5.767           ms/op
Client.listUser:listUser·p0.50        sample        20.316           ms/op
Client.listUser:listUser·p0.90        sample        25.526           ms/op
Client.listUser:listUser·p0.95        sample        26.247           ms/op
Client.listUser:listUser·p0.99        sample        30.091           ms/op
Client.listUser:listUser·p0.999       sample        35.346           ms/op
Client.listUser:listUser·p0.9999      sample        35.848           ms/op
Client.listUser:listUser·p1.00        sample        35.848           ms/op
```
