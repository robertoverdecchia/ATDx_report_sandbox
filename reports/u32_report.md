
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-datarouter.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-datarouter) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-datarouter) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dmaap-datarouter.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-dbcapi.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-dbcapi) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-dbcapi) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dmaap-dbcapi.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-messagerouter-dmaapclient.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-messagerouter-dmaapclient) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-messagerouter-dmaapclient) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dmaap-messagerouter-dmaapclient.json)</p>
 | |
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-messagerouter-messageservice.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-messagerouter-messageservice) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-messagerouter-messageservice) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dmaap-messagerouter-messageservice.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-messagerouter-mirroragent.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-messagerouter-mirroragent) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-messagerouter-mirroragent) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dmaap-messagerouter-mirroragent.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-messagerouter-msgrtr.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-messagerouter-msgrtr) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-messagerouter-msgrtr) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dmaap-messagerouter-msgrtr.json)</p>
 | |

# Project report summaries
## Project: _onap/dmaap-datarouter_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-datarouter.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-datarouter) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-datarouter) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dmaap-datarouter.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name         |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                          |
|:-------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------------------------------------|
| StatusLog.java     |              4 |             0 |           0 |      0 |           4 |           0 |            0 | datarouter-node/src/main/java/org/onap/dmaap/datarouter/node/StatusLog.java                   |
| RLEBitSet.java     |              2 |             2 |           0 |      0 |           0 |           0 |            0 | datarouter-prov/src/main/java/org/onap/dmaap/datarouter/provisioning/utils/RLEBitSet.java     |
| LOGJSONObject.java |              2 |             2 |           0 |      0 |           0 |           0 |            0 | datarouter-prov/src/main/java/org/onap/dmaap/datarouter/provisioning/utils/LOGJSONObject.java |
| NodeConfig.java    |              1 |             0 |           0 |      0 |           1 |           0 |            0 | datarouter-node/src/main/java/org/onap/dmaap/datarouter/node/NodeConfig.java                  |

## Project: _onap/dmaap-dbcapi_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-dbcapi.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-dbcapi) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-dbcapi) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dmaap-dbcapi.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name          |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                             |
|:--------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------|
| DBFieldHandler.java |              7 |             0 |           7 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/dbcapi/database/DBFieldHandler.java |
| AafLurService.java  |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/dbcapi/aaf/AafLurService.java       |
| DatabaseClass.java  |              1 |             0 |           1 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/dbcapi/database/DatabaseClass.java  |
| ConnWrapper.java    |              1 |             0 |           1 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/dbcapi/database/ConnWrapper.java    |
| TableHandler.java   |              1 |             0 |           1 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/dbcapi/database/TableHandler.java   |
| ApiService.java     |              1 |             0 |           1 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/dbcapi/service/ApiService.java      |
| Main.java           |              1 |             0 |           1 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/dbcapi/server/Main.java             |
| AafObject.java      |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/onap/dmaap/dbcapi/aaf/AafObject.java           |
| DBSingleton.java    |              1 |             0 |           1 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/dbcapi/database/DBSingleton.java    |

## Project: _onap/dmaap-messagerouter-dmaapclient_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-messagerouter-dmaapclient.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-messagerouter-dmaapclient) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-messagerouter-dmaapclient) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dmaap-messagerouter-dmaapclient.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                   |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                     |
|:-----------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-------------------------------------------------------------------------|
| MRBaseClient.java            |             18 |             0 |          17 |      0 |           1 |           0 |            0 | src/main/java/org/onap/dmaap/mr/client/impl/MRBaseClient.java            |
| MRClientFactory.java         |             18 |             0 |           7 |      0 |          11 |           0 |            0 | src/main/java/org/onap/dmaap/mr/client/MRClientFactory.java              |
| MRSimplerBatchPublisher.java |              6 |             0 |           1 |      0 |           3 |           2 |            0 | src/main/java/org/onap/dmaap/mr/client/impl/MRSimplerBatchPublisher.java |
| MRConsumer.java              |              4 |             0 |           4 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/mr/client/MRConsumer.java                   |
| SimpleExamplePublisher.java  |              4 |             0 |           4 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/mr/test/clients/SimpleExamplePublisher.java |
| MRMetaClient.java            |              4 |             0 |           4 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/mr/client/impl/MRMetaClient.java            |
| MRTopicManager.java          |              3 |             0 |           2 |      0 |           1 |           0 |            0 | src/main/java/org/onap/dmaap/mr/client/MRTopicManager.java               |
| MRConsumerImpl.java          |              3 |             0 |           1 |      0 |           2 |           0 |            0 | src/main/java/org/onap/dmaap/mr/client/impl/MRConsumerImpl.java          |
| MRBatchPublisher.java        |              2 |             0 |           1 |      0 |           1 |           0 |            0 | src/main/java/org/onap/dmaap/mr/client/impl/MRBatchPublisher.java        |
| SimpleExamplePublisher.java  |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/mr/dme/client/SimpleExamplePublisher.java   |

## Project: _onap/dmaap-messagerouter-messageservice_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-messagerouter-messageservice.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-messagerouter-messageservice) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-messagerouter-messageservice) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dmaap-messagerouter-messageservice.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                    |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                            |
|:------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------|
| MirrorMaker.java              |              5 |             0 |           0 |      0 |           5 |           0 |            0 | src/main/java/org/onap/dmaap/mmagent/MirrorMaker.java           |
| MMRestService.java            |              4 |             0 |           4 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/service/MMRestService.java         |
| TopicRestService.java         |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/service/TopicRestService.java      |
| ApiKeysRestService.java       |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/service/ApiKeysRestService.java    |
| ServiceUtil.java              |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/onap/dmaap/service/ServiceUtil.java           |
| ServicePropertiesMapBean.java |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/onap/dmaap/util/ServicePropertiesMapBean.java |
| CreateMirrorMaker.java        |              1 |             0 |           1 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/mmagent/CreateMirrorMaker.java     |

## Project: _onap/dmaap-messagerouter-mirroragent_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-messagerouter-mirroragent.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-messagerouter-mirroragent) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-messagerouter-mirroragent) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dmaap-messagerouter-mirroragent.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                     |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                              |
|:-------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------------------------|
| MirrorMaker.java               |              7 |             0 |           0 |      0 |           7 |           0 |            0 | src/main/java/org/onap/dmaap/mr/dmaapMMAgent/dao/MirrorMaker.java                 |
| MirrorMakerProcessHandler.java |              3 |             1 |           1 |      0 |           1 |           0 |            0 | src/main/java/org/onap/dmaap/mr/dmaapMMAgent/utils/MirrorMakerProcessHandler.java |
| MirrorMakerAgent.java          |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/onap/dmaap/mr/dmaapMMAgent/MirrorMakerAgent.java                |

## Project: _onap/dmaap-messagerouter-msgrtr_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-messagerouter-msgrtr.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-messagerouter-msgrtr) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-messagerouter-msgrtr) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dmaap-messagerouter-msgrtr.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                      |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                 |
|:--------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-------------------------------------------------------------------------------------|
| MMServiceImpl.java              |              6 |             0 |           6 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/dmf/mr/service/impl/MMServiceImpl.java                  |
| ConfigurationReader.java        |              4 |             0 |           3 |      0 |           1 |           0 |            0 | src/main/java/org/onap/dmaap/dmf/mr/utils/ConfigurationReader.java                   |
| CambriaOutboundEventStream.java |              4 |             0 |           4 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/dmf/mr/resources/CambriaOutboundEventStream.java        |
| EventsServiceImpl.java          |              4 |             0 |           4 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/dmf/mr/service/impl/EventsServiceImpl.java              |
| KafkaConsumerCache.java         |              3 |             0 |           0 |      0 |           0 |           0 |            3 | src/main/java/org/onap/dmaap/dmf/mr/backends/kafka/KafkaConsumerCache.java           |
| TopicServiceImpl.java           |              3 |             0 |           3 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/dmf/mr/service/impl/TopicServiceImpl.java               |
| DMaaPCambriaClientFactory.java  |              3 |             0 |           0 |      0 |           3 |           0 |            0 | src/main/java/org/onap/dmaap/dmf/mr/metrics/publisher/DMaaPCambriaClientFactory.java |
| UIServiceImpl.java              |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/dmf/mr/service/impl/UIServiceImpl.java                  |
| TopicService.java               |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/dmf/mr/service/TopicService.java                        |
| CambriaPublisherUtility.java    |              2 |             0 |           1 |      0 |           1 |           0 |            0 | src/main/java/org/onap/dmaap/dmf/mr/metrics/publisher/CambriaPublisherUtility.java   |

