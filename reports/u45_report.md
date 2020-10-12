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
|<p align="center">Project 1</p><img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_sdc.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/sdc) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdc) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_sdc.json)</p>|<p align="center">Project 2</p><img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vfc-nfvo-driver-sfc.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/vfc-nfvo-driver-sfc) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vfc-nfvo-driver-sfc) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_vfc-nfvo-driver-sfc.json)</p>|<p align="center">Project 3</p><img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vfc-nfvo-resmanagement.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/vfc-nfvo-resmanagement) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vfc-nfvo-resmanagement) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_vfc-nfvo-resmanagement.json)</p>
 | |

# Project report summaries
## Project 1: _onap/sdc_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_sdc.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/sdc) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdc) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_sdc.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                         |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified class name                                                                                |
|:-----------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------------------------------------------------|
| ArtifactsBusinessLogic.java        |             31 |             0 |           0 |      0 |          31 |           0 |            0 | catalog-be/src/main/java/org/openecomp/sdc/be/components/impl/ArtifactsBusinessLogic.java                 |
| ResourceBusinessLogic.java         |             22 |             3 |           0 |      0 |          19 |           0 |            0 | catalog-be/src/main/java/org/openecomp/sdc/be/components/impl/ResourceBusinessLogic.java                  |
| Logger.java                        |             21 |             0 |           0 |      0 |          21 |           0 |            0 | common-app-logging/src/main/java/org/openecomp/sdc/common/log/wrappers/Logger.java                        |
| DistributionNotificationEvent.java |             11 |            10 |           0 |      0 |           1 |           0 |            0 | catalog-dao/src/main/java/org/openecomp/sdc/be/resources/data/auditing/DistributionNotificationEvent.java |
| ResourceAdminEvent.java            |             11 |            10 |           0 |      0 |           1 |           0 |            0 | catalog-dao/src/main/java/org/openecomp/sdc/be/resources/data/auditing/ResourceAdminEvent.java            |
| CategoryEvent.java                 |             10 |            10 |           0 |      0 |           0 |           0 |            0 | catalog-dao/src/main/java/org/openecomp/sdc/be/resources/data/auditing/CategoryEvent.java                 |
| CompositionBusinessLogic.java      |             10 |             0 |           0 |      0 |           0 |           0 |           10 | catalog-be/src/main/java/org/openecomp/sdc/be/components/impl/CompositionBusinessLogic.java               |
| AuditingGetUebClusterEvent.java    |             10 |            10 |           0 |      0 |           0 |           0 |            0 | catalog-dao/src/main/java/org/openecomp/sdc/be/resources/data/auditing/AuditingGetUebClusterEvent.java    |
| UserAdminEvent.java                |             10 |            10 |           0 |      0 |           0 |           0 |            0 | catalog-dao/src/main/java/org/openecomp/sdc/be/resources/data/auditing/UserAdminEvent.java                |
| DistributionStatusEvent.java       |             10 |            10 |           0 |      0 |           0 |           0 |            0 | catalog-dao/src/main/java/org/openecomp/sdc/be/resources/data/auditing/DistributionStatusEvent.java       |

## Project 2: _onap/vfc-nfvo-driver-sfc_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vfc-nfvo-driver-sfc.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/vfc-nfvo-driver-sfc) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vfc-nfvo-driver-sfc) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_vfc-nfvo-driver-sfc.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name              | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                            |
|:------------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:----------------------------------------------------------------------|
| DriverResource.java     | 8              | 0             | 8           | 0      | 0           | 0           | 0            | sfc-driver/src/main/java/org/onap/sfc/resources/DriverResource.java   |
| SdnServiceConsumer.java | 3              | 0             | 2           | 0      | 1           | 0           | 0            | sfc-driver/src/main/java/org/onap/sfc/service/SdnServiceConsumer.java |
| N2sReqWrapper.java      | 1              | 0             | 0           | 0      | 1           | 0           | 0            | sfc-driver/src/main/java/org/onap/sfc/wrapper/N2sReqWrapper.java      |
| ConfigInfo.java         | 1              | 0             | 0           | 0      | 1           | 0           | 0            | sfc-driver/src/main/java/org/onap/sfc/service/ConfigInfo.java         |
| SfcDriverUtil.java      | 1              | 0             | 0           | 0      | 1           | 0           | 0            | sfc-driver/src/main/java/org/onap/sfc/utils/SfcDriverUtil.java        |
| -                       | -              | -             | -           | -      | -           | -           | -            | -                                                                     |
| -                       | -              | -             | -           | -      | -           | -           | -            | -                                                                     |
| -                       | -              | -             | -           | -      | -           | -           | -            | -                                                                     |
| -                       | -              | -             | -           | -      | -           | -           | -            | -                                                                     |
| -                       | -              | -             | -           | -      | -           | -           | -            | -                                                                     |

## Project 3: _onap/vfc-nfvo-resmanagement_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vfc-nfvo-resmanagement.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/vfc-nfvo-resmanagement) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vfc-nfvo-resmanagement) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_vfc-nfvo-resmanagement.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                                                                                 |
|:--------------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:---------------------------------------------------------------------------------------------------------------------------|
| ServiceException.java     | 3              | 0             | 3           | 0      | 0           | 0           | 0            | ResmanagementService/service/src/main/java/org/onap/vfc/nfvo/resmanagement/common/util/restclient/ServiceException.java    |
| SitesRoa.java             | 2              | 0             | 2           | 0      | 0           | 0           | 0            | ResmanagementService/service/src/main/java/org/onap/vfc/nfvo/resmanagement/service/rest/SitesRoa.java                      |
| LocationBusinessImpl.java | 1              | 0             | 1           | 0      | 0           | 0           | 0            | ResmanagementService/service/src/main/java/org/onap/vfc/nfvo/resmanagement/service/business/impl/LocationBusinessImpl.java |
| NsRoa.java                | 1              | 0             | 1           | 0      | 0           | 0           | 0            | ResmanagementService/service/src/main/java/org/onap/vfc/nfvo/resmanagement/service/rest/NsRoa.java                         |
| VnfRoa.java               | 1              | 0             | 1           | 0      | 0           | 0           | 0            | ResmanagementService/service/src/main/java/org/onap/vfc/nfvo/resmanagement/service/rest/VnfRoa.java                        |
| VmServiceImpl.java        | 1              | 0             | 1           | 0      | 0           | 0           | 0            | ResmanagementService/service/src/main/java/org/onap/vfc/nfvo/resmanagement/service/group/impl/VmServiceImpl.java           |
| -                         | -              | -             | -           | -      | -           | -           | -            | -                                                                                                                          |
| -                         | -              | -             | -           | -      | -           | -           | -            | -                                                                                                                          |
| -                         | -              | -             | -           | -      | -           | -           | -            | -                                                                                                                          |
| -                         | -              | -             | -           | -      | -           | -           | -            | -                                                                                                                          |

