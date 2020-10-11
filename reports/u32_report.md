
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-datarouter.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-datarouter) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-datarouter) <br> [Complete issue report (JSON)](./json/onap_dmaap-datarouter.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-dbcapi.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-dbcapi) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-dbcapi) <br> [Complete issue report (JSON)](./json/onap_dmaap-dbcapi.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-messagerouter-dmaapclient.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-messagerouter-dmaapclient) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-messagerouter-dmaapclient) <br> [Complete issue report (JSON)](./json/onap_dmaap-messagerouter-dmaapclient.json)</p>
 | |
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-messagerouter-messageservice.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-messagerouter-messageservice) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-messagerouter-messageservice) <br> [Complete issue report (JSON)](./json/onap_dmaap-messagerouter-messageservice.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-messagerouter-mirroragent.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-messagerouter-mirroragent) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-messagerouter-mirroragent) <br> [Complete issue report (JSON)](./json/onap_dmaap-messagerouter-mirroragent.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-messagerouter-msgrtr.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-messagerouter-msgrtr) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-messagerouter-msgrtr) <br> [Complete issue report (JSON)](./json/onap_dmaap-messagerouter-msgrtr.json)</p>
 | |

# Project report summaries
## Project: _onap/dmaap-datarouter_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-datarouter.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-datarouter) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-datarouter) <br> [Complete issue report (JSON)](./json/onap_dmaap-datarouter.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name     |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                        |
|:---------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------------------|
| StatusLog.java |              4 |             0 |           0 |      0 |           4 |           0 |            0 | datarouter-node/src/main/java/org/onap/dmaap/datarouter/node/StatusLog.java |

## Project: _onap/dmaap-dbcapi_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-dbcapi.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-dbcapi) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-dbcapi) <br> [Complete issue report (JSON)](./json/onap_dmaap-dbcapi.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name          |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                             |
|:--------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------|
| DBFieldHandler.java |              7 |             0 |           7 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/dbcapi/database/DBFieldHandler.java |

## Project: _onap/dmaap-messagerouter-dmaapclient_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-messagerouter-dmaapclient.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-messagerouter-dmaapclient) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-messagerouter-dmaapclient) <br> [Complete issue report (JSON)](./json/onap_dmaap-messagerouter-dmaapclient.json)</p>
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

## Project: _onap/dmaap-messagerouter-messageservice_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-messagerouter-messageservice.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-messagerouter-messageservice) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-messagerouter-messageservice) <br> [Complete issue report (JSON)](./json/onap_dmaap-messagerouter-messageservice.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name         |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                    |
|:-------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:--------------------------------------------------------|
| MirrorMaker.java   |              5 |             0 |           0 |      0 |           5 |           0 |            0 | src/main/java/org/onap/dmaap/mmagent/MirrorMaker.java   |
| MMRestService.java |              4 |             0 |           4 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/service/MMRestService.java |

## Project: _onap/dmaap-messagerouter-mirroragent_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-messagerouter-mirroragent.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-messagerouter-mirroragent) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-messagerouter-mirroragent) <br> [Complete issue report (JSON)](./json/onap_dmaap-messagerouter-mirroragent.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                     |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                              |
|:-------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------------------------|
| MirrorMaker.java               |              7 |             0 |           0 |      0 |           7 |           0 |            0 | src/main/java/org/onap/dmaap/mr/dmaapMMAgent/dao/MirrorMaker.java                 |
| MirrorMakerProcessHandler.java |              3 |             1 |           1 |      0 |           1 |           0 |            0 | src/main/java/org/onap/dmaap/mr/dmaapMMAgent/utils/MirrorMakerProcessHandler.java |

## Project: _onap/dmaap-messagerouter-msgrtr_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-messagerouter-msgrtr.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-messagerouter-msgrtr) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-messagerouter-msgrtr) <br> [Complete issue report (JSON)](./json/onap_dmaap-messagerouter-msgrtr.json)</p>
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

