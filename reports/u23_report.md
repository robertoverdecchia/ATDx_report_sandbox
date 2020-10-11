
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-collectors-restconf.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-collectors-restconf) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-collectors-restconf) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dcaegen2-collectors-restconf.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-collectors-ves.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-collectors-ves) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-collectors-ves) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dcaegen2-collectors-ves.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-platform-inventory-api.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-platform-inventory-api) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-platform-inventory-api) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dcaegen2-platform-inventory-api.json)</p>
 | |
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-services-mapper.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-services-mapper) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-services-mapper) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dcaegen2-services-mapper.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-services-prh.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-services-prh) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-services-prh) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dcaegen2-services-prh.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-services-sdk.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-services-sdk) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-services-sdk) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dcaegen2-services-sdk.json)</p>
 | |
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-services-son-handler.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-services-son-handler) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-services-son-handler) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dcaegen2-services-son-handler.json)</p>
# Project report summaries
## Project: _onap/dcaegen2-collectors-restconf_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-collectors-restconf.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-collectors-restconf) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-collectors-restconf) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dcaegen2-collectors-restconf.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name               |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                        |
|:-------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:------------------------------------------------------------|
| Parameters.java          |             27 |             0 |           0 |      0 |          27 |           0 |            0 | src/main/java/org/onap/dcae/common/Parameters.java          |
| RestapiCallNode.java     |              7 |             0 |           7 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dcae/common/RestapiCallNode.java     |
| HttpResponse.java        |              4 |             0 |           0 |      0 |           4 |           0 |            0 | src/main/java/org/onap/dcae/common/HttpResponse.java        |
| RestapiCallNodeUtil.java |              4 |             0 |           4 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dcae/common/RestapiCallNodeUtil.java |
| JsonParser.java          |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dcae/common/JsonParser.java          |
| RestConfCollector.java   |              2 |             0 |           1 |      0 |           1 |           0 |            0 | src/main/java/org/onap/dcae/RestConfCollector.java          |

## Project: _onap/dcaegen2-collectors-ves_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-collectors-ves.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-collectors-ves) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-collectors-ves) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dcaegen2-collectors-ves.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                    |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                        |
|:------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------------------|
| DMaaPPublishersBuilder.java   |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/onap/dcae/common/publishing/DMaaPPublishersBuilder.java   |
| DMaaPConfigurationParser.java |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/onap/dcae/common/publishing/DMaaPConfigurationParser.java |
| ConfigSource.java             |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/onap/dcae/controller/ConfigSource.java                    |
| VESLogger.java                |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/onap/dcae/common/VESLogger.java                           |
| CLIUtils.java                 |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/onap/dcae/CLIUtils.java                                   |
| EnvPropertiesReader.java      |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/onap/dcae/controller/EnvPropertiesReader.java             |

## Project: _onap/dcaegen2-platform-inventory-api_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-platform-inventory-api.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-platform-inventory-api) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-platform-inventory-api) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dcaegen2-platform-inventory-api.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                           |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                       |
|:-------------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------|
| DcaeServiceTypesQueryStatement.java  |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/io/swagger/api/impl/DcaeServiceTypesQueryStatement.java      |
| DCAEServiceTransactionDAO.java       |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/onap/dcae/inventory/daos/DCAEServiceTransactionDAO.java  |
| DatabusControllerClient.java         |              1 |             0 |           1 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dcae/inventory/clients/DatabusControllerClient.java |
| DcaeServiceTypeObjectRepository.java |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/io/swagger/api/impl/DcaeServiceTypeObjectRepository.java     |

## Project: _onap/dcaegen2-services-mapper_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-services-mapper.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-services-mapper) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-services-mapper) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dcaegen2-services-mapper.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name              |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                         |
|:------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------------------|
| VesService.java         |              2 |             0 |           1 |      0 |           0 |           1 |            0 | UniversalVesAdapter/src/main/java/org/onap/universalvesadapter/service/VesService.java       |
| FetchDynamicConfig.java |              2 |             0 |           0 |      0 |           2 |           0 |            0 | UniversalVesAdapter/src/main/java/org/onap/universalvesadapter/utils/FetchDynamicConfig.java |

## Project: _onap/dcaegen2-services-prh_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-services-prh.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-services-prh) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-services-prh) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dcaegen2-services-prh.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                  |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                  |
|:----------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:------------------------------------------------------------------------------------------------------|
| AaiClientConfiguration.java |              2 |             0 |           0 |      0 |           2 |           0 |            0 | prh-commons/src/main/java/org/onap/dcaegen2/services/prh/adapter/aai/main/AaiClientConfiguration.java |

## Project: _onap/dcaegen2-services-sdk_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-services-sdk.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-services-sdk) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-services-sdk) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dcaegen2-services-sdk.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                  |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                                             |
|:----------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------------------------------------------------------|
| CbsClientConfiguration.java |              5 |             0 |           0 |      0 |           5 |           0 |            0 | rest-services/cbs-client/src/main/java/org/onap/dcaegen2/services/sdk/rest/services/cbs/client/model/CbsClientConfiguration.java |
| MdcVariables.java           |              3 |             0 |           0 |      0 |           3 |           0 |            0 | rest-services/http-client/src/main/java/org/onap/dcaegen2/services/sdk/rest/services/adapters/http/logging/MdcVariables.java     |

## Project: _onap/dcaegen2-services-son-handler_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-services-son-handler.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-services-son-handler) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-services-son-handler) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dcaegen2-services-son-handler.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                       |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                   |
|:---------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------------|
| AppConfig.java                   |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/onap/dcaegen2/services/sonhms/utils/AppConfig.java                   |
| EventHandler.java                |              1 |             0 |           1 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dcaegen2/services/sonhms/EventHandler.java                      |
| LteNeighborListInUseLteCell.java |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/onap/dcaegen2/services/sonhms/model/LteNeighborListInUseLteCell.java |
| OofRestClient.java               |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/onap/dcaegen2/services/sonhms/restclient/OofRestClient.java          |
| NotificationCallback.java        |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/onap/dcaegen2/services/sonhms/dmaap/NotificationCallback.java        |

