
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_incubator-ratis.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/incubator-ratis) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_incubator-ratis) <br> [Complete issue report (JSON)](./json/apache_incubator-ratis.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_isis.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/isis) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_isis) <br> [Complete issue report (JSON)](./json/apache_isis.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/servicecomb-toolkit.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/servicecomb-toolkit) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=servicecomb-toolkit) <br> [Complete issue report (JSON)](./json/servicecomb-toolkit.json)</p>
 | |

# Project report summaries
## Project: _apache/incubator-ratis_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_incubator-ratis.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/incubator-ratis) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_incubator-ratis) <br> [Complete issue report (JSON)](./json/apache_incubator-ratis.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name            |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                    |
|:----------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------------------------------|
| NativeIO.java         |             40 |             3 |           1 |      0 |          36 |           0 |            0 | ratis-common/src/main/java/org/apache/ratis/io/nativeio/NativeIO.java                   |
| VerificationTool.java |              6 |             0 |           6 |      0 |           0 |           0 |            0 | ratis-logservice/src/main/java/org/apache/ratis/logservice/tool/VerificationTool.java   |
| RaftProperties.java   |              6 |             0 |           6 |      0 |           0 |           0 |            0 | ratis-common/src/main/java/org/apache/ratis/conf/RaftProperties.java                    |
| MetaStateMachine.java |              5 |             5 |           0 |      0 |           0 |           0 |            0 | ratis-logservice/src/main/java/org/apache/ratis/logservice/server/MetaStateMachine.java |
| NativeCrc32.java      |              5 |             0 |           2 |      0 |           3 |           0 |            0 | ratis-common/src/main/java/org/apache/ratis/util/NativeCrc32.java                       |
| ServerProtoUtils.java |              3 |             0 |           0 |      0 |           3 |           0 |            0 | ratis-server/src/main/java/org/apache/ratis/server/impl/ServerProtoUtils.java           |
| LogServiceClient.java |              3 |             0 |           3 |      0 |           0 |           0 |            0 | ratis-logservice/src/main/java/org/apache/ratis/logservice/api/LogServiceClient.java    |
| LogStateMachine.java  |              3 |             0 |           3 |      0 |           0 |           0 |            0 | ratis-logservice/src/main/java/org/apache/ratis/logservice/server/LogStateMachine.java  |
| LogAppender.java      |              3 |             0 |           3 |      0 |           0 |           0 |            0 | ratis-server/src/main/java/org/apache/ratis/server/impl/LogAppender.java                |

## Project: _apache/isis_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_isis.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/isis) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_isis) <br> [Complete issue report (JSON)](./json/apache_isis.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                         |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                                                      |
|:-----------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:------------------------------------------------------------------------------------------------------------------------------------------|
| CommonDtoUtils.java                |             29 |             0 |           1 |      0 |           1 |           0 |           27 | api/applib/src/main/java/org/apache/isis/applib/util/schema/CommonDtoUtils.java                                                           |
| IsisConfiguration.java             |             26 |             0 |           0 |      0 |          26 |           0 |            0 | core/config/src/main/java/org/apache/isis/core/config/IsisConfiguration.java                                                              |
| PojoTester.java                    |             21 |            21 |           0 |      0 |           0 |           0 |            0 | testing/unittestsupport/applib/src/main/java/org/apache/isis/testing/unittestsupport/applib/bean/PojoTester.java                          |
| _Json.java                         |             17 |             0 |          16 |      0 |           1 |           0 |            0 | core/commons/src/main/java/org/apache/isis/core/commons/internal/resources/_Json.java                                                     |
| ExcelService.java                  |             16 |             0 |          16 |      0 |           0 |           0 |            0 | subdomains/excel/applib/src/main/java/org/apache/isis/subdomains/excel/applib/dom/ExcelService.java                                       |
| ValueTypeContractTestAbstract.java |             12 |             0 |          12 |      0 |           0 |           0 |            0 | core/internaltestsupport/src/main/java/org/apache/isis/core/internaltestsupport/value/ValueTypeContractTestAbstract.java                  |
| ValueTypeContractTestAbstract.java |             12 |             0 |          12 |      0 |           0 |           0 |            0 | testing/unittestsupport/applib/src/main/java/org/apache/isis/testing/unittestsupport/applib/core/value/ValueTypeContractTestAbstract.java |
| JsonMapper.java                    |              9 |             0 |           9 |      0 |           0 |           0 |            0 | viewers/restfulobjects/applib/src/main/java/org/apache/isis/viewer/restfulobjects/applib/util/JsonMapper.java                             |
| Parent.java                        |              8 |             0 |           8 |      0 |           0 |           0 |            0 | testing/unittestsupport/applib/src/main/java/org/apache/isis/testing/unittestsupport/applib/core/bidir/Parent.java                        |
| DomainEventHelper.java             |              7 |             0 |           6 |      0 |           1 |           0 |            0 | core/metamodel/src/main/java/org/apache/isis/core/metamodel/facets/DomainEventHelper.java                                                 |

## Project: _apache/servicecomb-toolkit_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/servicecomb-toolkit.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/servicecomb-toolkit) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=servicecomb-toolkit) <br> [Complete issue report (JSON)](./json/servicecomb-toolkit.json)</p>
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

