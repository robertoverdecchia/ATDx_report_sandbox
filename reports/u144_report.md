# ATDx Report Summary
Our ATDx analysis targets a portfolio of software projects and identifies the pain points of each project in terms of Architectural Technical Debt (ATD). This evaluation is based on a statistical analysis of the violations of SonarCloud rules.

## ATDx in a nutshell
![ATDx in a nutshell](https://raw.githubusercontent.com/robertoverdecchia/ATDx_report_sandbox/master/plots/atdx_in_a_nutshell.jpg)

ATDx works by comparing architectural debt metrics across the projects of a software portfolio. Intuitively, it ensures that measurements across different projects are comparable, and then evaluates the severity of Architectural Technical Debt by confronting the measurements across the projects.

The ATDx approach is by itself tool-independent, and can be customized according the analysis tools available, and the portfolio considered.
In the case of this report, we used an instance of ATDx based on the static analysis tool [SonarQube](https://www.sonarqube.org/).

The instance of ATDx used to analyze your projects provides an overview of the architectural technical debt in a project in 6 distinct dimensions:
* **Inheritance**: flaws concerning inheritance mechanisms between classes, such as overrides and inheritance of methods or fields
* **Exception**: flaws regarding the management of Java exceptions and the subclassing of the “Exception” Java class.
* **JVMS**: potential misuses of the Java Virtual Machine, e.g., the incorrect usage of the specific Java class “Serializable”
* **Threading**: flaws arising from the implementation of multiple execution threads, which could potentially lead to concurrency problems
* **Interface**: flaws related to the usage of Java interfaces
* **Complexity**: flaws derived from prominent complexity measures, such as McCabe’s cyclomatic complexity

For each project, the dimensions assume a value between 0 and 5, where 0 denotes minimum architectural debt of the project in that dimension, and 5 maximum architectural debt.

In the reminder of this report, we firstly provide a set of radar charts (one for each project). Then for each project we give:
1. The same radar chart as shown at the beginning
2. A table showing the top-10 classes of the project with the highest architectural technical debt.

Note that if numerous classes with 1 violation are reported, this might point to a widespread problem (only a maximum of 10 classes are provided per project for the sake of readability). Similarly, empty rows indicate that only a few classes are affected by ATDx violations.

If you are corious about more theoretical background on ATDx, you can have a look at [this scientific publication](https://robertoverdecchia.github.io/papers/ENASE_2020.pdf).

## ATDx radar charts of your projects
|||
|-|-|
|<p align="center">Project 1</p><img src="https://github.com/S2-group/ATDx_reports/blob/master/plots/servicecomb-pack.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/servicecomb-pack) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=servicecomb-pack) <br> [Complete issue report (JSON)](https://github.com/S2-group/ATDx_reports/blob/master/jsons/servicecomb-pack.json)</p>|<p align="center">Project 2</p><img src="https://github.com/S2-group/ATDx_reports/blob/master/plots/servicecomb-toolkit.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/servicecomb-toolkit) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=servicecomb-toolkit) <br> [Complete issue report (JSON)](https://github.com/S2-group/ATDx_reports/blob/master/jsons/servicecomb-toolkit.json)</p>
# ATDx project report summaries
## Project 1: _apache/servicecomb-pack_
|<img src="https://github.com/S2-group/ATDx_reports/blob/master/plots/servicecomb-pack.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/servicecomb-pack) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=servicecomb-pack) <br> [Complete issue report (JSON)](https://github.com/S2-group/ATDx_reports/blob/master/jsons/servicecomb-pack.json)</p>
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

## Project 2: _apache/servicecomb-toolkit_
|<img src="https://github.com/S2-group/ATDx_reports/blob/master/plots/servicecomb-toolkit.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/servicecomb-toolkit) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=servicecomb-toolkit) <br> [Complete issue report (JSON)](https://github.com/S2-group/ATDx_reports/blob/master/jsons/servicecomb-toolkit.json)</p>
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

