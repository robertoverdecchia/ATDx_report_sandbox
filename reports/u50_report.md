# ATDx Report Summary
Our ATDx analysis targets a portfolio of software projects and identifies the pain points of each project in terms of Architectural Technical Debt (ATD). This evaluation is based on a statistical analysis of the violations of SonarCloud rules.

ATDx provides an overview of the architectural technical debt in a project  in 6 distinct dimensions:
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

## Radar charts
||||
|-|-|-|
|<p align="center">Project 1</p><img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_ccsdk-features.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/ccsdk-features) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_ccsdk-features) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_ccsdk-features.json)</p>|<p align="center">Project 2</p><img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_ccsdk-sli-adaptors.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/ccsdk-sli-adaptors) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_ccsdk-sli-adaptors) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_ccsdk-sli-adaptors.json)</p>|<p align="center">Project 3</p><img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_ccsdk-sli-core.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/ccsdk-sli-core) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_ccsdk-sli-core) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_ccsdk-sli-core.json)</p>
 | |
|<p align="center">Project 4</p><img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_ccsdk-sli-plugins.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/ccsdk-sli-plugins) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_ccsdk-sli-plugins) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_ccsdk-sli-plugins.json)</p>|<p align="center">Project 5</p><img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_logging-analytics.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/logging-analytics) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_logging-analytics) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_logging-analytics.json)</p>
# Project report summaries
## Project 1: _onap/ccsdk-features_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_ccsdk-features.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/ccsdk-features) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_ccsdk-features) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_ccsdk-features.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name          |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified class name                                                                                               |
|:--------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-------------------------------------------------------------------------------------------------------------------------|
| Program.java        |             12 |             0 |          12 |      0 |           0 |           0 |            0 | sdnr/wt/data-provider/setup/src/main/java/org/onap/ccsdk/features/sdnr/wt/dataprovider/setup/Program.java                |
| MessageDaoImpl.java |              8 |             0 |           8 |      0 |           0 |           0 |            0 | lib/doorman/src/main/java/org/onap/ccsdk/features/lib/doorman/dao/MessageDaoImpl.java                                    |
| MyOdluxBundle.java  |              8 |             8 |           0 |      0 |           0 |           0 |            0 | sdnr/wt/odlux/apps/maintenanceApp/src2/main/java/org/onap/ccsdk/features/sdnr/wt/odlux/bundles/MyOdluxBundle.java        |
| MyOdluxBundle.java  |              8 |             8 |           0 |      0 |           0 |           0 |            0 | sdnr/wt/odlux/apps/apiDemo/src2/main/java/org/onap/ccsdk/features/sdnr/wt/odlux/bundles/MyOdluxBundle.java               |
| MyOdluxBundle.java  |              8 |             8 |           0 |      0 |           0 |           0 |            0 | sdnr/wt/odlux/apps/mediatorApp/src2/main/java/org/onap/ccsdk/features/sdnr/wt/odlux/bundles/MyOdluxBundle.java           |
| MyOdluxBundle.java  |              8 |             8 |           0 |      0 |           0 |           0 |            0 | sdnr/wt/odlux/apps/performanceHistoryApp/src2/main/java/org/onap/ccsdk/features/sdnr/wt/odlux/bundles/MyOdluxBundle.java |
| MyOdluxBundle.java  |              8 |             8 |           0 |      0 |           0 |           0 |            0 | sdnr/wt/odlux/apps/configurationApp/src2/main/java/org/onap/ccsdk/features/sdnr/wt/odlux/bundles/MyOdluxBundle.java      |
| MyOdluxBundle.java  |              8 |             8 |           0 |      0 |           0 |           0 |            0 | sdnr/wt/odlux/apps/connectApp/src2/main/java/org/onap/ccsdk/features/sdnr/wt/odlux/bundles/MyOdluxBundle.java            |
| MyOdluxBundle.java  |              8 |             8 |           0 |      0 |           0 |           0 |            0 | sdnr/wt/odlux/apps/inventoryApp/src2/main/java/org/onap/ccsdk/features/sdnr/wt/odlux/bundles/MyOdluxBundle.java          |
| MyOdluxBundle.java  |              8 |             8 |           0 |      0 |           0 |           0 |            0 | sdnr/wt/odlux/apps/minimumApp/src2/main/java/org/onap/ccsdk/features/sdnr/wt/odlux/bundles/MyOdluxBundle.java            |

## Project 2: _onap/ccsdk-sli-adaptors_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_ccsdk-sli-adaptors.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/ccsdk-sli-adaptors) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_ccsdk-sli-adaptors) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_ccsdk-sli-adaptors.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                  |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified class name                                                                                 |
|:----------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------------------------------------------------|
| ResourceRequest.java        |             23 |             0 |           0 |      0 |          23 |           0 |            0 | resource-assignment/provider/src/main/java/org/onap/ccsdk/sli/adaptors/ra/comp/ResourceRequest.java        |
| ResourceRule.java           |             11 |             0 |           0 |      0 |          11 |           0 |            0 | resource-assignment/provider/src/main/java/org/onap/ccsdk/sli/adaptors/ra/rule/data/ResourceRule.java      |
| RangeAllocationRequest.java |             10 |             0 |           0 |      0 |          10 |           0 |            0 | resource-assignment/provider/src/main/java/org/onap/ccsdk/sli/adaptors/rm/data/RangeAllocationRequest.java |
| AllocationItem.java         |             10 |             0 |           0 |      0 |          10 |           0 |            0 | resource-assignment/provider/src/main/java/org/onap/ccsdk/sli/adaptors/rm/dao/jdbc/AllocationItem.java     |
| ResourceResponse.java       |              9 |             0 |           0 |      0 |           9 |           0 |            0 | resource-assignment/provider/src/main/java/org/onap/ccsdk/sli/adaptors/ra/comp/ResourceResponse.java       |
| AllocationRequest.java      |              9 |             0 |           0 |      0 |           9 |           0 |            0 | resource-assignment/provider/src/main/java/org/onap/ccsdk/sli/adaptors/rm/data/AllocationRequest.java      |
| Resource.java               |              8 |             0 |           0 |      0 |           8 |           0 |            0 | resource-assignment/provider/src/main/java/org/onap/ccsdk/sli/adaptors/rm/dao/jdbc/Resource.java           |
| ResourceData.java           |              8 |             0 |           0 |      0 |           8 |           0 |            0 | resource-assignment/provider/src/main/java/org/onap/ccsdk/sli/adaptors/ra/comp/ResourceData.java           |
| ResourceAllocator.java      |              8 |             0 |           8 |      0 |           0 |           0 |            0 | resource-assignment/provider/src/main/java/org/onap/ccsdk/sli/adaptors/ra/ResourceAllocator.java           |
| AAIDeclarations.java        |              7 |             0 |           4 |      0 |           0 |           0 |            3 | aai-service/provider/src/main/java/org/onap/ccsdk/sli/adaptors/aai/AAIDeclarations.java                    |

## Project 3: _onap/ccsdk-sli-core_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_ccsdk-sli-core.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/ccsdk-sli-core) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_ccsdk-sli-core) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_ccsdk-sli-core.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name               |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified class name                                                                       |
|:-------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-------------------------------------------------------------------------------------------------|
| MdsalHelper.java         |              6 |             0 |           0 |      0 |           6 |           0 |            0 | sli/provider/src/main/java/org/onap/ccsdk/sli/core/sli/provider/MdsalHelper.java                 |
| MessageWriter.java       |              3 |             0 |           0 |      0 |           2 |           1 |            0 | sli/common/src/main/java/org/onap/ccsdk/sli/core/sli/MessageWriter.java                          |
| DBConfigFactory.java     |              3 |             0 |           2 |      0 |           1 |           0 |            0 | dblib/provider/src/main/java/org/onap/ccsdk/sli/core/dblib/factory/DBConfigFactory.java          |
| SliStringUtils.java      |              3 |             0 |           3 |      0 |           0 |           0 |            0 | sliPluginUtils/provider/src/main/java/org/onap/ccsdk/sli/core/slipluginutils/SliStringUtils.java |
| BaseDBConfiguration.java |              3 |             0 |           3 |      0 |           0 |           0 |            0 | dblib/provider/src/main/java/org/onap/ccsdk/sli/core/dblib/config/BaseDBConfiguration.java       |
| MetricLogger.java        |              3 |             0 |           0 |      0 |           3 |           0 |            0 | sli/common/src/main/java/org/onap/ccsdk/sli/core/sli/MetricLogger.java                           |
| SliPluginUtils.java      |              2 |             0 |           1 |      0 |           1 |           0 |            0 | sliPluginUtils/provider/src/main/java/org/onap/ccsdk/sli/core/slipluginutils/SliPluginUtils.java |
| PrintYangToProp.java     |              2 |             0 |           0 |      0 |           2 |           0 |            0 | sli/provider/src/main/java/org/onap/ccsdk/sli/core/sli/provider/PrintYangToProp.java             |
| DBResourceManager.java   |              2 |             0 |           2 |      0 |           0 |           0 |            0 | dblib/provider/src/main/java/org/onap/ccsdk/sli/core/dblib/DBResourceManager.java                |
| CachedDataSource.java    |              2 |             0 |           2 |      0 |           0 |           0 |            0 | dblib/provider/src/main/java/org/onap/ccsdk/sli/core/dblib/CachedDataSource.java                 |

## Project 4: _onap/ccsdk-sli-plugins_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_ccsdk-sli-plugins.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/ccsdk-sli-plugins) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_ccsdk-sli-plugins) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_ccsdk-sli-plugins.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name              |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified class name                                                                                         |
|:------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-------------------------------------------------------------------------------------------------------------------|
| Parameters.java         |             31 |             0 |           0 |      0 |          31 |           0 |            0 | restapi-call-node/provider/src/main/java/org/onap/ccsdk/sli/plugins/restapicall/Parameters.java                    |
| RestapiCallNode.java    |             17 |             0 |           0 |      0 |          17 |           0 |            0 | restapi-call-node/provider/src/main/java/org/onap/ccsdk/sli/plugins/restapicall/RestapiCallNode.java               |
| Parameters.java         |             15 |             0 |           0 |      0 |          15 |           0 |            0 | sshapi-call-node/provider/src/main/java/org/onap/ccsdk/sli/plugins/sshapicall/model/Parameters.java                |
| HttpResponse.java       |              5 |             0 |           0 |      0 |           5 |           0 |            0 | restapi-call-node/provider/src/main/java/org/onap/ccsdk/sli/plugins/restapicall/HttpResponse.java                  |
| Parameters.java         |              4 |             0 |           0 |      0 |           4 |           0 |            0 | properties-node/provider/src/main/java/org/onap/ccsdk/sli/plugins/prop/Parameters.java                             |
| GrToolkitProvider.java  |              3 |             0 |           0 |      0 |           3 |           0 |            0 | grToolkit/provider/src/main/java/org/onap/ccsdk/sli/plugins/grtoolkit/GrToolkitProvider.java                       |
| ConnectionResponse.java |              2 |             0 |           0 |      0 |           2 |           0 |            0 | grToolkit/provider/src/main/java/org/onap/ccsdk/sli/plugins/grtoolkit/connection/ConnectionResponse.java           |
| ParseParam.java         |              2 |             0 |           2 |      0 |           0 |           0 |            0 | sshapi-call-node/provider/src/main/java/org/onap/ccsdk/sli/plugins/sshapicall/model/ParseParam.java                |
| RetryPolicy.java        |              1 |             0 |           1 |      0 |           0 |           0 |            0 | restapi-call-node/provider/src/main/java/org/onap/ccsdk/sli/plugins/restapicall/RetryPolicy.java                   |
| YangParameters.java     |              1 |             0 |           0 |      0 |           1 |           0 |            0 | restconf-client/provider/src/main/java/org/onap/ccsdk/sli/plugins/yangserializers/dfserializer/YangParameters.java |

## Project 5: _onap/logging-analytics_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_logging-analytics.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/logging-analytics) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_logging-analytics) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_logging-analytics.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                         | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                                                                                 |
|:-----------------------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:---------------------------------------------------------------------------------------------------------------------------|
| Constants.java                     | 4              | 0             | 0           | 0      | 4           | 0           | 0            | reference/logging-filter/logging-filter-base/src/main/java/org/onap/logging/filter/base/Constants.java                     |
| FilteredMetricLogClientFilter.java | 4              | 4             | 0           | 0      | 0           | 0           | 0            | reference/logging-filter/logging-filter-base/src/main/java/org/onap/logging/filter/base/FilteredMetricLogClientFilter.java |
| AbstractMDCSetupAspect.java        | 1              | 0             | 1           | 0      | 0           | 0           | 0            | reference/logging-filter/logging-filter-base/src/main/java/org/onap/logging/filter/base/AbstractMDCSetupAspect.java        |
| ScheduledTaskException.java        | 1              | 0             | 1           | 0      | 0           | 0           | 0            | reference/logging-filter/logging-filter-base/src/main/java/org/onap/logging/filter/base/ScheduledTaskException.java        |
| SLF4JRefApplication.java           | 1              | 0             | 1           | 0      | 0           | 0           | 0            | reference/logging-slf4j-demo/src/main/java/org/onap/logging/ref/slf4j/demo/SLF4JRefApplication.java                        |
| SpringClientPayloadFilter.java     | 1              | 0             | 1           | 0      | 0           | 0           | 0            | reference/logging-filter/logging-filter-spring/src/main/java/org/onap/logging/filter/spring/SpringClientPayloadFilter.java |
| PayloadLoggingClientFilter.java    | 1              | 0             | 1           | 0      | 0           | 0           | 0            | reference/logging-filter/logging-filter-base/src/main/java/org/onap/logging/filter/base/PayloadLoggingClientFilter.java    |
| -                                  | -              | -             | -           | -      | -           | -           | -            | -                                                                                                                          |
| -                                  | -              | -             | -           | -      | -           | -           | -            | -                                                                                                                          |
| -                                  | -              | -             | -           | -      | -           | -           | -            | -                                                                                                                          |

