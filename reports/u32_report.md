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
|<p align="center">Project 1</p><img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-datarouter.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-datarouter) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-datarouter) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dmaap-datarouter.json)</p>|<p align="center">Project 2</p><img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-dbcapi.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-dbcapi) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-dbcapi) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dmaap-dbcapi.json)</p>|<p align="center">Project 3</p><img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-messagerouter-dmaapclient.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-messagerouter-dmaapclient) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-messagerouter-dmaapclient) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dmaap-messagerouter-dmaapclient.json)</p>
 | |
|<p align="center">Project 4</p><img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-messagerouter-messageservice.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-messagerouter-messageservice) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-messagerouter-messageservice) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dmaap-messagerouter-messageservice.json)</p>|<p align="center">Project 5</p><img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-messagerouter-mirroragent.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-messagerouter-mirroragent) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-messagerouter-mirroragent) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dmaap-messagerouter-mirroragent.json)</p>|<p align="center">Project 6</p><img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-messagerouter-msgrtr.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-messagerouter-msgrtr) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-messagerouter-msgrtr) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dmaap-messagerouter-msgrtr.json)</p>
 | |

# Project report summaries
## Project 1: _onap/dmaap-datarouter_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-datarouter.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-datarouter) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-datarouter) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dmaap-datarouter.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name         | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                                                    |
|:-------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:----------------------------------------------------------------------------------------------|
| StatusLog.java     | 4              | 0             | 0           | 0      | 4           | 0           | 0            | datarouter-node/src/main/java/org/onap/dmaap/datarouter/node/StatusLog.java                   |
| RLEBitSet.java     | 2              | 2             | 0           | 0      | 0           | 0           | 0            | datarouter-prov/src/main/java/org/onap/dmaap/datarouter/provisioning/utils/RLEBitSet.java     |
| LOGJSONObject.java | 2              | 2             | 0           | 0      | 0           | 0           | 0            | datarouter-prov/src/main/java/org/onap/dmaap/datarouter/provisioning/utils/LOGJSONObject.java |
| NodeConfig.java    | 1              | 0             | 0           | 0      | 1           | 0           | 0            | datarouter-node/src/main/java/org/onap/dmaap/datarouter/node/NodeConfig.java                  |
| -                  | -              | -             | -           | -      | -           | -           | -            | -                                                                                             |
| -                  | -              | -             | -           | -      | -           | -           | -            | -                                                                                             |
| -                  | -              | -             | -           | -      | -           | -           | -            | -                                                                                             |
| -                  | -              | -             | -           | -      | -           | -           | -            | -                                                                                             |
| -                  | -              | -             | -           | -      | -           | -           | -            | -                                                                                             |
| -                  | -              | -             | -           | -      | -           | -           | -            | -                                                                                             |

## Project 2: _onap/dmaap-dbcapi_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-dbcapi.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-dbcapi) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-dbcapi) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dmaap-dbcapi.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name          | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                       |
|:--------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:-----------------------------------------------------------------|
| DBFieldHandler.java | 7              | 0             | 7           | 0      | 0           | 0           | 0            | src/main/java/org/onap/dmaap/dbcapi/database/DBFieldHandler.java |
| AafLurService.java  | 2              | 0             | 2           | 0      | 0           | 0           | 0            | src/main/java/org/onap/dmaap/dbcapi/aaf/AafLurService.java       |
| DatabaseClass.java  | 1              | 0             | 1           | 0      | 0           | 0           | 0            | src/main/java/org/onap/dmaap/dbcapi/database/DatabaseClass.java  |
| ConnWrapper.java    | 1              | 0             | 1           | 0      | 0           | 0           | 0            | src/main/java/org/onap/dmaap/dbcapi/database/ConnWrapper.java    |
| TableHandler.java   | 1              | 0             | 1           | 0      | 0           | 0           | 0            | src/main/java/org/onap/dmaap/dbcapi/database/TableHandler.java   |
| ApiService.java     | 1              | 0             | 1           | 0      | 0           | 0           | 0            | src/main/java/org/onap/dmaap/dbcapi/service/ApiService.java      |
| Main.java           | 1              | 0             | 1           | 0      | 0           | 0           | 0            | src/main/java/org/onap/dmaap/dbcapi/server/Main.java             |
| AafObject.java      | 1              | 0             | 0           | 0      | 1           | 0           | 0            | src/main/java/org/onap/dmaap/dbcapi/aaf/AafObject.java           |
| DBSingleton.java    | 1              | 0             | 1           | 0      | 0           | 0           | 0            | src/main/java/org/onap/dmaap/dbcapi/database/DBSingleton.java    |
| -                   | -              | -             | -           | -      | -           | -           | -            | -                                                                |

## Project 3: _onap/dmaap-messagerouter-dmaapclient_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-messagerouter-dmaapclient.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-messagerouter-dmaapclient) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-messagerouter-dmaapclient) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dmaap-messagerouter-dmaapclient.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                   |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified class name                                               |
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

## Project 4: _onap/dmaap-messagerouter-messageservice_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-messagerouter-messageservice.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-messagerouter-messageservice) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-messagerouter-messageservice) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dmaap-messagerouter-messageservice.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                    | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                      |
|:------------------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:----------------------------------------------------------------|
| MirrorMaker.java              | 5              | 0             | 0           | 0      | 5           | 0           | 0            | src/main/java/org/onap/dmaap/mmagent/MirrorMaker.java           |
| MMRestService.java            | 4              | 0             | 4           | 0      | 0           | 0           | 0            | src/main/java/org/onap/dmaap/service/MMRestService.java         |
| TopicRestService.java         | 2              | 0             | 2           | 0      | 0           | 0           | 0            | src/main/java/org/onap/dmaap/service/TopicRestService.java      |
| ApiKeysRestService.java       | 2              | 0             | 2           | 0      | 0           | 0           | 0            | src/main/java/org/onap/dmaap/service/ApiKeysRestService.java    |
| ServiceUtil.java              | 1              | 0             | 0           | 0      | 1           | 0           | 0            | src/main/java/org/onap/dmaap/service/ServiceUtil.java           |
| ServicePropertiesMapBean.java | 1              | 0             | 0           | 0      | 1           | 0           | 0            | src/main/java/org/onap/dmaap/util/ServicePropertiesMapBean.java |
| CreateMirrorMaker.java        | 1              | 0             | 1           | 0      | 0           | 0           | 0            | src/main/java/org/onap/dmaap/mmagent/CreateMirrorMaker.java     |
| -                             | -              | -             | -           | -      | -           | -           | -            | -                                                               |
| -                             | -              | -             | -           | -      | -           | -           | -            | -                                                               |
| -                             | -              | -             | -           | -      | -           | -           | -            | -                                                               |

## Project 5: _onap/dmaap-messagerouter-mirroragent_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-messagerouter-mirroragent.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-messagerouter-mirroragent) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-messagerouter-mirroragent) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dmaap-messagerouter-mirroragent.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                     | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                                        |
|:-------------------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:----------------------------------------------------------------------------------|
| MirrorMaker.java               | 7              | 0             | 0           | 0      | 7           | 0           | 0            | src/main/java/org/onap/dmaap/mr/dmaapMMAgent/dao/MirrorMaker.java                 |
| MirrorMakerProcessHandler.java | 3              | 1             | 1           | 0      | 1           | 0           | 0            | src/main/java/org/onap/dmaap/mr/dmaapMMAgent/utils/MirrorMakerProcessHandler.java |
| MirrorMakerAgent.java          | 1              | 0             | 0           | 0      | 1           | 0           | 0            | src/main/java/org/onap/dmaap/mr/dmaapMMAgent/MirrorMakerAgent.java                |
| -                              | -              | -             | -           | -      | -           | -           | -            | -                                                                                 |
| -                              | -              | -             | -           | -      | -           | -           | -            | -                                                                                 |
| -                              | -              | -             | -           | -      | -           | -           | -            | -                                                                                 |
| -                              | -              | -             | -           | -      | -           | -           | -            | -                                                                                 |
| -                              | -              | -             | -           | -      | -           | -           | -            | -                                                                                 |
| -                              | -              | -             | -           | -      | -           | -           | -            | -                                                                                 |
| -                              | -              | -             | -           | -      | -           | -           | -            | -                                                                                 |

## Project 6: _onap/dmaap-messagerouter-msgrtr_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-messagerouter-msgrtr.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-messagerouter-msgrtr) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-messagerouter-msgrtr) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dmaap-messagerouter-msgrtr.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                      |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified class name                                                           |
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

