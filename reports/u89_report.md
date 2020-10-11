
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-services-prh.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-services-prh) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-services-prh) <br> [Complete issue report (JSON)](./json/onap_dcaegen2-services-prh.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-services-sdk.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-services-sdk) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-services-sdk) <br> [Complete issue report (JSON)](./json/onap_dcaegen2-services-sdk.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vid.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/vid) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vid) <br> [Complete issue report (JSON)](./json/onap_vid.json)</p>
 | |

# Project report summaries
## Project: _onap/dcaegen2-services-prh_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-services-prh.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-services-prh) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-services-prh) <br> [Complete issue report (JSON)](./json/onap_dcaegen2-services-prh.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                                          |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:---------------------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| prh-commons/src/main/java/org/onap/dcaegen2/services/prh/model/utils/PrhModelAwareGsonBuilder.java |             0 |           0 |         0 |           1 |           0 |            0 |     1 |

## Project: _onap/dcaegen2-services-sdk_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-services-sdk.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-services-sdk) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-services-sdk) <br> [Complete issue report (JSON)](./json/onap_dcaegen2-services-sdk.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                  |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                                             |
|:----------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------------------------------------------------------|
| CbsClientConfiguration.java |              5 |             0 |           0 |      0 |           5 |           0 |            0 | rest-services/cbs-client/src/main/java/org/onap/dcaegen2/services/sdk/rest/services/cbs/client/model/CbsClientConfiguration.java |
| MdcVariables.java           |              3 |             0 |           0 |      0 |           3 |           0 |            0 | rest-services/http-client/src/main/java/org/onap/dcaegen2/services/sdk/rest/services/adapters/http/logging/MdcVariables.java     |

## Project: _onap/vid_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_vid.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/vid) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_vid) <br> [Complete issue report (JSON)](./json/onap_vid.json)</p>
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

