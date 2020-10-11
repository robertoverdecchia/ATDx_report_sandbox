
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-collectors-restconf.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-collectors-restconf) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-collectors-restconf) <br> [Complete issue report (JSON)](./json/onap_dcaegen2-collectors-restconf.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-collectors-ves.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-collectors-ves) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-collectors-ves) <br> [Complete issue report (JSON)](./json/onap_dcaegen2-collectors-ves.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-platform-inventory-api.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-platform-inventory-api) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-platform-inventory-api) <br> [Complete issue report (JSON)](./json/onap_dcaegen2-platform-inventory-api.json)</p>
 | |
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-services-mapper.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-services-mapper) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-services-mapper) <br> [Complete issue report (JSON)](./json/onap_dcaegen2-services-mapper.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-services-prh.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-services-prh) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-services-prh) <br> [Complete issue report (JSON)](./json/onap_dcaegen2-services-prh.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-services-sdk.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-services-sdk) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-services-sdk) <br> [Complete issue report (JSON)](./json/onap_dcaegen2-services-sdk.json)</p>
 | |
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-services-son-handler.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-services-son-handler) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-services-son-handler) <br> [Complete issue report (JSON)](./json/onap_dcaegen2-services-son-handler.json)</p>
# Project report summaries
## Project: _onap/dcaegen2-collectors-restconf_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-collectors-restconf.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-collectors-restconf) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-collectors-restconf) <br> [Complete issue report (JSON)](./json/onap_dcaegen2-collectors-restconf.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name               |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                        |
|:-------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:------------------------------------------------------------|
| Parameters.java          |             27 |             0 |           0 |      0 |          27 |           0 |            0 | src/main/java/org/onap/dcae/common/Parameters.java          |
| RestapiCallNode.java     |              7 |             0 |           7 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dcae/common/RestapiCallNode.java     |
| HttpResponse.java        |              4 |             0 |           0 |      0 |           4 |           0 |            0 | src/main/java/org/onap/dcae/common/HttpResponse.java        |
| RestapiCallNodeUtil.java |              4 |             0 |           4 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dcae/common/RestapiCallNodeUtil.java |

## Project: _onap/dcaegen2-collectors-ves_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-collectors-ves.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-collectors-ves) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-collectors-ves) <br> [Complete issue report (JSON)](./json/onap_dcaegen2-collectors-ves.json)</p>
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

## Project: _onap/dcaegen2-platform-inventory-api_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-platform-inventory-api.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-platform-inventory-api) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-platform-inventory-api) <br> [Complete issue report (JSON)](./json/onap_dcaegen2-platform-inventory-api.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                  |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:---------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| src/main/java/io/swagger/api/impl/DcaeServiceTypesQueryStatement.java      |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/onap/dcae/inventory/daos/DCAEServiceTransactionDAO.java  |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/onap/dcae/inventory/clients/DatabusControllerClient.java |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| src/main/java/io/swagger/api/impl/DcaeServiceTypeObjectRepository.java     |             0 |           0 |         0 |           1 |           0 |            0 |     1 |

## Project: _onap/dcaegen2-services-mapper_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-services-mapper.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-services-mapper) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-services-mapper) <br> [Complete issue report (JSON)](./json/onap_dcaegen2-services-mapper.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                                                  |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:-----------------------------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| UniversalVesAdapter/src/main/java/org/onap/universalvesadapter/adapter/GenericAdapter.java                 |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| UniversalVesAdapter/src/main/java/org/onap/universalvesadapter/dmaap/BaseDMaaPMRComponent.java             |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| UniversalVesAdapter/src/main/java/org/onap/universalvesadapter/adapter/UniversalEventAdapter.java          |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| UniversalVesAdapter/src/main/java/org/onap/universalvesadapter/utils/SmooksUtils.java                      |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| UniversalVesAdapter/src/main/java/org/onap/universalvesadapter/configs/DMaaPMRSubscriberConfig.java        |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| UniversalVesAdapter/src/main/java/org/onap/universalvesadapter/configs/DMaaPMRPublisherConfig.java         |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| UniversalVesAdapter/src/main/java/org/onap/universalvesadapter/dmaap/MRPublisher/DMaaPMRPublisherImpl.java |             0 |           0 |         0 |           1 |           0 |            0 |     1 |

## Project: _onap/dcaegen2-services-prh_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-services-prh.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-services-prh) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-services-prh) <br> [Complete issue report (JSON)](./json/onap_dcaegen2-services-prh.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                                          |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:---------------------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| prh-commons/src/main/java/org/onap/dcaegen2/services/prh/model/utils/PrhModelAwareGsonBuilder.java |             0 |           0 |         0 |           1 |           0 |            0 |     1 |

## Project: _onap/dcaegen2-services-sdk_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-services-sdk.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-services-sdk) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-services-sdk) <br> [Complete issue report (JSON)](./json/onap_dcaegen2-services-sdk.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                  |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                                             |
|:----------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------------------------------------------------------|
| CbsClientConfiguration.java |              5 |             0 |           0 |      0 |           5 |           0 |            0 | rest-services/cbs-client/src/main/java/org/onap/dcaegen2/services/sdk/rest/services/cbs/client/model/CbsClientConfiguration.java |
| MdcVariables.java           |              3 |             0 |           0 |      0 |           3 |           0 |            0 | rest-services/http-client/src/main/java/org/onap/dcaegen2/services/sdk/rest/services/adapters/http/logging/MdcVariables.java     |

## Project: _onap/dcaegen2-services-son-handler_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-services-son-handler.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-services-son-handler) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-services-son-handler) <br> [Complete issue report (JSON)](./json/onap_dcaegen2-services-son-handler.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                              |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:---------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| src/main/java/org/onap/dcaegen2/services/sonhms/utils/AppConfig.java                   |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/onap/dcaegen2/services/sonhms/EventHandler.java                      |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| src/main/java/org/onap/dcaegen2/services/sonhms/model/LteNeighborListInUseLteCell.java |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/onap/dcaegen2/services/sonhms/restclient/OofRestClient.java          |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/onap/dcaegen2/services/sonhms/dmaap/NotificationCallback.java        |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/onap/dcaegen2/services/sonhms/child/ChildThread.java                 |             0 |           0 |         0 |           0 |           0 |            0 |     0 |
| src/main/java/org/onap/dcaegen2/services/sonhms/utils/BeanUtil.java                    |             0 |           0 |         0 |           0 |           0 |            0 |     0 |

