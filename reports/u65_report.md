
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
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
| component                                                                   |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:----------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| src/main/java/org/onap/dcae/common/publishing/DMaaPPublishersBuilder.java   |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/onap/dcae/common/publishing/DMaaPConfigurationParser.java |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/onap/dcae/controller/ConfigSource.java                    |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/onap/dcae/common/VESLogger.java                           |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/onap/dcae/CLIUtils.java                                   |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/onap/dcae/controller/EnvPropertiesReader.java             |             0 |           0 |         0 |           1 |           0 |            0 |     1 |

## Project: _onap/vid_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vid.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/vid) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vid) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_vid.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                       |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                      |
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
| component                                                                                              |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:-------------------------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| vnfmarket-be/vnf-sdk-marketplace/src/main/java/org/onap/vnfsdk/marketplace/db/wrapper/BaseHandler.java |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| vnfmarket-be/vnf-sdk-marketplace/src/main/java/org/onap/vtp/VTPResource.java                           |             0 |           1 |         0 |           0 |           0 |            0 |     1 |

## Project: _onap/vnfsdk-validation_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vnfsdk-validation.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/vnfsdk-validation) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vnfsdk-validation) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_vnfsdk-validation.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name               |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                           |
|:-------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-------------------------------------------------------------------------------|
| ValidationException.java |              3 |             1 |           2 |      0 |           0 |           0 |            0 | csarvalidation/src/main/java/org/onap/validation/csar/ValidationException.java |

