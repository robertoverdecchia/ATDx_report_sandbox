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
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-collectors-ves.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-collectors-ves) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-collectors-ves) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dcaegen2-collectors-ves.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vid.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/vid) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vid) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_vid.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vnfsdk-refrepo.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/vnfsdk-refrepo) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vnfsdk-refrepo) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_vnfsdk-refrepo.json)</p>
 | |
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vnfsdk-validation.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/vnfsdk-validation) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vnfsdk-validation) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_vnfsdk-validation.json)</p>
# Project report summaries
## Project: _onap/dcaegen2-collectors-ves_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-collectors-ves.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-collectors-ves) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-collectors-ves) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dcaegen2-collectors-ves.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                    | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                                  |
|:------------------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:----------------------------------------------------------------------------|
| DMaaPPublishersBuilder.java   | 1              | 0             | 0           | 0      | 1           | 0           | 0            | src/main/java/org/onap/dcae/common/publishing/DMaaPPublishersBuilder.java   |
| DMaaPConfigurationParser.java | 1              | 0             | 0           | 0      | 1           | 0           | 0            | src/main/java/org/onap/dcae/common/publishing/DMaaPConfigurationParser.java |
| ConfigSource.java             | 1              | 0             | 0           | 0      | 1           | 0           | 0            | src/main/java/org/onap/dcae/controller/ConfigSource.java                    |
| VESLogger.java                | 1              | 0             | 0           | 0      | 1           | 0           | 0            | src/main/java/org/onap/dcae/common/VESLogger.java                           |
| CLIUtils.java                 | 1              | 0             | 0           | 0      | 1           | 0           | 0            | src/main/java/org/onap/dcae/CLIUtils.java                                   |
| EnvPropertiesReader.java      | 1              | 0             | 0           | 0      | 1           | 0           | 0            | src/main/java/org/onap/dcae/controller/EnvPropertiesReader.java             |
| -                             | -              | -             | -           | -      | -           | -           | -            | -                                                                           |
| -                             | -              | -             | -           | -      | -           | -           | -            | -                                                                           |
| -                             | -              | -             | -           | -      | -           | -           | -            | -                                                                           |
| -                             | -              | -             | -           | -      | -           | -           | -            | -                                                                           |

## Project: _onap/vid_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vid.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/vid) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vid) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_vid.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                       |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified class name                                                                |
|:---------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:------------------------------------------------------------------------------------------|
| ServiceRelationships.java        |             11 |             0 |           0 |      0 |          11 |           0 |            0 | vid-app-common/src/main/java/org/onap/vid/aai/model/ServiceRelationships.java             |
| AsyncRequestStatus.java          |             11 |             0 |           0 |      0 |          11 |           0 |            0 | vid-app-common/src/main/java/org/onap/vid/mso/rest/AsyncRequestStatus.java                |
| LogicalLinkResponse.java         |              6 |             0 |           0 |      0 |           6 |           0 |            0 | vid-app-common/src/main/java/org/onap/vid/aai/model/LogicalLinkResponse.java              |
| PnfProperties.java               |              6 |             0 |           0 |      0 |           6 |           0 |            0 | vid-app-common/src/main/java/org/onap/vid/aai/model/PnfProperties.java                    |
| MsoRequestDetails.java           |              5 |             0 |           0 |      0 |           5 |           0 |            0 | vid-app-common/src/main/java/org/onap/vid/changeManagement/MsoRequestDetails.java         |
| Relationship.java                |              5 |             0 |           0 |      0 |           5 |           0 |            0 | vid-app-common/src/main/java/org/onap/vid/aai/model/Relationship.java                     |
| ChangeManagementServiceImpl.java |              5 |             0 |           0 |      0 |           0 |           0 |            5 | vid-app-common/src/main/java/org/onap/vid/services/ChangeManagementServiceImpl.java       |
| GetTenantsResponse.java          |              5 |             0 |           0 |      0 |           5 |           0 |            0 | vid-app-common/src/main/java/org/onap/vid/aai/model/AaiGetTenatns/GetTenantsResponse.java |
| PnfResult.java                   |              5 |             0 |           0 |      0 |           5 |           0 |            0 | vid-app-common/src/main/java/org/onap/vid/aai/model/PnfResult.java                        |
| MsoExceptionResponse.java        |              4 |             0 |           1 |      0 |           3 |           0 |            0 | vid-app-common/src/main/java/org/onap/vid/model/MsoExceptionResponse.java                 |

## Project: _onap/vnfsdk-refrepo_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vnfsdk-refrepo.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/vnfsdk-refrepo) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vnfsdk-refrepo) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_vnfsdk-refrepo.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                                                             |
|:--------------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:-------------------------------------------------------------------------------------------------------|
| VTPExecutionResource.java | 2              | 0             | 2           | 0      | 0           | 0           | 0            | vnfmarket-be/vnf-sdk-marketplace/src/main/java/org/onap/vtp/execution/VTPExecutionResource.java        |
| BaseHandler.java          | 1              | 0             | 1           | 0      | 0           | 0           | 0            | vnfmarket-be/vnf-sdk-marketplace/src/main/java/org/onap/vnfsdk/marketplace/db/wrapper/BaseHandler.java |
| VTPResource.java          | 1              | 0             | 1           | 0      | 0           | 0           | 0            | vnfmarket-be/vnf-sdk-marketplace/src/main/java/org/onap/vtp/VTPResource.java                           |
| -                         | -              | -             | -           | -      | -           | -           | -            | -                                                                                                      |
| -                         | -              | -             | -           | -      | -           | -           | -            | -                                                                                                      |
| -                         | -              | -             | -           | -      | -           | -           | -            | -                                                                                                      |
| -                         | -              | -             | -           | -      | -           | -           | -            | -                                                                                                      |
| -                         | -              | -             | -           | -      | -           | -           | -            | -                                                                                                      |
| -                         | -              | -             | -           | -      | -           | -           | -            | -                                                                                                      |
| -                         | -              | -             | -           | -      | -           | -           | -            | -                                                                                                      |

## Project: _onap/vnfsdk-validation_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vnfsdk-validation.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/vnfsdk-validation) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vnfsdk-validation) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_vnfsdk-validation.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                 | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                                       |
|:---------------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:---------------------------------------------------------------------------------|
| ValidationException.java   | 3              | 1             | 2           | 0      | 0           | 0           | 0            | csarvalidation/src/main/java/org/onap/validation/csar/ValidationException.java   |
| ValidatorSchemaLoader.java | 2              | 0             | 2           | 0      | 0           | 0           | 0            | csarvalidation/src/main/java/org/onap/validation/csar/ValidatorSchemaLoader.java |
| VTPValidateCSARBase.java   | 1              | 0             | 1           | 0      | 0           | 0           | 0            | csarvalidation/src/main/java/org/onap/cvc/csar/cc/VTPValidateCSARBase.java       |
| CsarUtil.java              | 1              | 0             | 0           | 0      | 1           | 0           | 0            | csarvalidation/src/main/java/org/onap/validation/csar/CsarUtil.java              |
| ManifestFileSplitter.java  | 1              | 0             | 0           | 0      | 0           | 0           | 1            | csarvalidation/src/main/java/org/onap/cvc/csar/parser/ManifestFileSplitter.java  |
| CsarValidator.java         | 1              | 0             | 0           | 0      | 1           | 0           | 0            | csarvalidation/src/main/java/org/onap/validation/csar/CsarValidator.java         |
| -                          | -              | -             | -           | -      | -           | -           | -            | -                                                                                |
| -                          | -              | -             | -           | -      | -           | -           | -            | -                                                                                |
| -                          | -              | -             | -           | -      | -           | -           | -            | -                                                                                |
| -                          | -              | -             | -           | -      | -           | -           | -            | -                                                                                |

