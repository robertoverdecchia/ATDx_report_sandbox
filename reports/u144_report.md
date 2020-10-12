# ATDx Report Summary
Following the overview of the ATDx analysis of your projects.

In short, the ATDx analysis is based on software metrics aggregation, and statistical severity evaluation of the aggregated values across a portfolio of software projects.

ATDx provides an overview of the project Architectural Technical Debt (ATD) in 6 distinct dimensions:
* **Inheritance**: flaws concerning inheritance mechanisms between classes, such as overrides and inheritance of methods or fields
* **Exception**: flaws regarding the Java throwable class “Exception” and its subclasses
* **JVMS**: potential misuse of the Java Virtual Machine, e.g., the incorrect usage of the specific Java class “Serializable”
* **Threading**: flaws arising from the implementation of multiple execution threads, which could potentially lead to concurrency problems
* **Interface**: flaws related to the usage of Java interfaces
* **Complexity**: flaws derived from prominent complexity measures, such as McCabe’s cyclomatic complexity

For each project, an overview of the ATDx values is presented, followed by the top classes of the project contributing to the ATDx values.

Note that if numerous classes with 1 violation are reported, this might point to a widespread problematics (only a maximum of 10 classes are provided per project). Similarly, empty rows may indicate that only few classes are affected by ATDx violations.
|||
|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/servicecomb-pack.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/servicecomb-pack) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=servicecomb-pack) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/servicecomb-pack.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/servicecomb-toolkit.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/servicecomb-toolkit) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=servicecomb-toolkit) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/servicecomb-toolkit.json)</p>
# Project report summaries
## Project: _apache/servicecomb-pack_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/servicecomb-pack.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/servicecomb-pack) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=servicecomb-pack) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/servicecomb-pack.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                          |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified class name                                                                                                        |
|:------------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------------------------------------------------------------------------|
| TxEvent.java                        |              5 |             0 |           0 |      0 |           5 |           0 |            0 | alpha/alpha-core/src/main/java/org/apache/servicecomb/pack/alpha/core/TxEvent.java                                                |
| TransactionRepository.java          |              4 |             0 |           4 |      0 |           0 |           0 |            0 | alpha/alpha-fsm/src/main/java/org/apache/servicecomb/pack/alpha/fsm/repository/TransactionRepository.java                         |
| AlphaClusterConfig.java             |              2 |             0 |           0 |      0 |           2 |           0 |            0 | omega/omega-connector/omega-connector-grpc/src/main/java/org/apache/servicecomb/pack/omega/connector/grpc/AlphaClusterConfig.java |
| OmegaCallbacksRegistry.java         |              2 |             0 |           1 |      0 |           1 |           0 |            0 | alpha/alpha-server/src/main/java/org/apache/servicecomb/pack/alpha/server/tcc/callback/OmegaCallbacksRegistry.java                |
| Command.java                        |              2 |             0 |           0 |      0 |           2 |           0 |            0 | alpha/alpha-core/src/main/java/org/apache/servicecomb/pack/alpha/core/Command.java                                                |
| MessageSerializer.java              |              2 |             0 |           2 |      0 |           0 |           0 |            0 | alpha/alpha-fsm/src/main/java/org/apache/servicecomb/pack/alpha/fsm/channel/redis/MessageSerializer.java                          |
| ParticipateAnnotationProcessor.java |              2 |             0 |           2 |      0 |           0 |           0 |            0 | omega/omega-spring-tx/src/main/java/org/apache/servicecomb/pack/omega/transaction/spring/ParticipateAnnotationProcessor.java      |
| CompensableAnnotationProcessor.java |              2 |             0 |           2 |      0 |           0 |           0 |            0 | omega/omega-spring-tx/src/main/java/org/apache/servicecomb/pack/omega/transaction/spring/CompensableAnnotationProcessor.java      |
| ParticipatedEvent.java              |              2 |             0 |           0 |      0 |           2 |           0 |            0 | alpha/alpha-server/src/main/java/org/apache/servicecomb/pack/alpha/server/tcc/jpa/ParticipatedEvent.java                          |
| APIv1.java                          |              2 |             0 |           2 |      0 |           0 |           0 |            0 | alpha/alpha-core/src/main/java/org/apache/servicecomb/pack/alpha/core/api/APIv1.java                                              |

## Project: _apache/servicecomb-toolkit_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/servicecomb-toolkit.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/servicecomb-toolkit) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=servicecomb-toolkit) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/servicecomb-toolkit.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                                  |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified class name                                                                                                                       |
|:--------------------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------|
| GenerateMojo.java                           |              6 |             0 |           6 |      0 |           0 |           0 |            0 | toolkit-maven-plugin/src/main/java/org/apache/servicecomb/toolkit/plugin/GenerateMojo.java                                                       |
| DefaultContractsGenerator.java              |              4 |             0 |           4 |      0 |           0 |           0 |            0 | contractgen/src/main/java/org/apache/servicecomb/toolkit/contractgen/DefaultContractsGenerator.java                                              |
| GenerateUtil.java                           |              4 |             0 |           3 |      0 |           1 |           0 |            0 | toolkit-maven-plugin/src/main/java/org/apache/servicecomb/toolkit/plugin/GenerateUtil.java                                                       |
| ParameterContext.java                       |              4 |             0 |           0 |      0 |           0 |           0 |            4 | oas-generator/oas-generator-core/src/main/java/org/apache/servicecomb/toolkit/generator/context/ParameterContext.java                            |
| VerifyMojo.java                             |              3 |             0 |           3 |      0 |           0 |           0 |            0 | toolkit-maven-plugin/src/main/java/org/apache/servicecomb/toolkit/plugin/VerifyMojo.java                                                         |
| CheckStyleBase.java                         |              3 |             0 |           3 |      0 |           0 |           0 |            0 | cli/src/main/java/org/apache/servicecomb/toolkit/cli/CheckStyleBase.java                                                                         |
| RequestMappingClassAnnotationProcessor.java |              2 |             0 |           2 |      0 |           0 |           0 |            0 | oas-generator/oas-generator-spring/src/main/java/org/apache/servicecomb/toolkit/generator/annotation/RequestMappingClassAnnotationProcessor.java |
| ClassMaker.java                             |              2 |             0 |           1 |      0 |           1 |           0 |            0 | common/src/main/java/org/apache/servicecomb/toolkit/common/ClassMaker.java                                                                       |
| OasObjectDiffValidatorUtils.java            |              2 |             0 |           0 |      0 |           2 |           0 |            0 | oas-validator/oas-validator-core/src/main/java/org/apache/servicecomb/toolkit/oasv/diffvalidation/util/OasObjectDiffValidatorUtils.java          |
| ParameterUtils.java                         |              2 |             0 |           0 |      0 |           2 |           0 |            0 | oas-validator/oas-validator-core/src/main/java/org/apache/servicecomb/toolkit/oasv/diffvalidation/util/ParameterUtils.java                       |

