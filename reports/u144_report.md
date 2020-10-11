
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
|||
|-|-|
|<img src="./plots/servicecomb-pack.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/servicecomb-pack) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=servicecomb-pack) <br> [Complete issue report (JSON)](./json/servicecomb-pack.json)</p>|<img src="./plots/servicecomb-toolkit.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/servicecomb-toolkit) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=servicecomb-toolkit) <br> [Complete issue report (JSON)](./json/servicecomb-toolkit.json)</p>
# Project report summaries
## Project: _apache/servicecomb-pack_
|./plots/servicecomb-pack.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/servicecomb-pack) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=servicecomb-pack) <br> [Complete issue report (JSON)](./json/servicecomb-pack.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                 |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                      |
|:---------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------------------------------------------------|
| TxEvent.java               |              5 |             0 |           0 |      0 |           5 |           0 |            0 | alpha/alpha-core/src/main/java/org/apache/servicecomb/pack/alpha/core/TxEvent.java                        |
| TransactionRepository.java |              4 |             0 |           4 |      0 |           0 |           0 |            0 | alpha/alpha-fsm/src/main/java/org/apache/servicecomb/pack/alpha/fsm/repository/TransactionRepository.java |

## Project: _apache/servicecomb-toolkit_
|./plots/servicecomb-toolkit.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/servicecomb-toolkit) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=servicecomb-toolkit) <br> [Complete issue report (JSON)](./json/servicecomb-toolkit.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                     |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                                  |
|:-------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------------------------------------------------------------|
| GenerateMojo.java              |              6 |             0 |           6 |      0 |           0 |           0 |            0 | toolkit-maven-plugin/src/main/java/org/apache/servicecomb/toolkit/plugin/GenerateMojo.java                            |
| DefaultContractsGenerator.java |              4 |             0 |           4 |      0 |           0 |           0 |            0 | contractgen/src/main/java/org/apache/servicecomb/toolkit/contractgen/DefaultContractsGenerator.java                   |
| GenerateUtil.java              |              4 |             0 |           3 |      0 |           1 |           0 |            0 | toolkit-maven-plugin/src/main/java/org/apache/servicecomb/toolkit/plugin/GenerateUtil.java                            |
| ParameterContext.java          |              4 |             0 |           0 |      0 |           0 |           0 |            4 | oas-generator/oas-generator-core/src/main/java/org/apache/servicecomb/toolkit/generator/context/ParameterContext.java |
| VerifyMojo.java                |              3 |             0 |           3 |      0 |           0 |           0 |            0 | toolkit-maven-plugin/src/main/java/org/apache/servicecomb/toolkit/plugin/VerifyMojo.java                              |
| CheckStyleBase.java            |              3 |             0 |           3 |      0 |           0 |           0 |            0 | cli/src/main/java/org/apache/servicecomb/toolkit/cli/CheckStyleBase.java                                              |

