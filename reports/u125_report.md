
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-services-son-handler.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-services-son-handler) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-services-son-handler) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dcaegen2-services-son-handler.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_optf-fgps.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/optf-fgps) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_optf-fgps) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_optf-fgps.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_policy-models.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/policy-models) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_policy-models) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_policy-models.json)</p>
 | |

# Project report summaries
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

## Project: _onap/optf-fgps_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_optf-fgps.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/optf-fgps) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_optf-fgps) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_optf-fgps.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                    |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                               |
|:------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------------------------|
| AAFProxy.java                 |              6 |             0 |           0 |      0 |           5 |           1 |            0 | valetapi/src/main/java/org/onap/fgps/api/proxy/AAFProxy.java                       |
| CipherUtil.java               |              5 |             0 |           5 |      0 |           0 |           0 |            0 | valetapi/src/main/java/org/onap/fgps/api/utils/CipherUtil.java                     |
| AuthorizationInterceptor.java |              2 |             0 |           2 |      0 |           0 |           0 |            0 | valetapi/src/main/java/org/onap/fgps/api/interceptor/AuthorizationInterceptor.java |

## Project: _onap/policy-models_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_policy-models.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/policy-models) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_policy-models) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_policy-models.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                            |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                                                   |
|:--------------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------------------------------------------------------------|
| PdpStatisticsProvider.java            |              1 |             0 |           0 |      0 |           1 |           0 |            0 | models-pdp/src/main/java/org/onap/policy/models/pdp/persistence/provider/PdpStatisticsProvider.java                                    |
| PfDao.java                            |              1 |             0 |           0 |      0 |           1 |           0 |            0 | models-dao/src/main/java/org/onap/policy/models/dao/PfDao.java                                                                         |
| BasicBidirectionalTopicOperation.java |              1 |             0 |           1 |      0 |           0 |           0 |            0 | models-interactions/model-actors/actor.test/src/main/java/org/onap/policy/controlloop/actor/test/BasicBidirectionalTopicOperation.java |

