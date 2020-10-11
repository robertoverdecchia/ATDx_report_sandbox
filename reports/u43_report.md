
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-analytics-tca-gen2.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-analytics-tca-gen2) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-analytics-tca-gen2) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dcaegen2-analytics-tca-gen2.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-collectors-ves.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-collectors-ves) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-collectors-ves) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dcaegen2-collectors-ves.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-services-sdk.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-services-sdk) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-services-sdk) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dcaegen2-services-sdk.json)</p>
 | |

# Project report summaries
## Project: _onap/dcaegen2-analytics-tca-gen2_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-analytics-tca-gen2.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-analytics-tca-gen2) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-analytics-tca-gen2) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dcaegen2-analytics-tca-gen2.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                     |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                                        |
|:-------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------------------------------------------------------------------|
| BaseAnalyticsTest.java         |              5 |             0 |           3 |      0 |           2 |           0 |            0 | dcae-analytics/dcae-analytics-test/src/main/java/org/onap/dcae/analytics/test/BaseAnalyticsTest.java                        |
| AnalyticsHttpUtils.java        |              2 |             0 |           0 |      0 |           2 |           0 |            0 | dcae-analytics/dcae-analytics-web/src/main/java/org/onap/dcae/analytics/web/util/AnalyticsHttpUtils.java                    |
| CriticalityMixin.java          |              1 |             0 |           0 |      0 |           1 |           0 |            0 | dcae-analytics/dcae-analytics-model/src/main/java/org/onap/dcae/analytics/model/util/json/mixin/cef/CriticalityMixin.java   |
| AlertActionMixin.java          |              1 |             0 |           0 |      0 |           1 |           0 |            0 | dcae-analytics/dcae-analytics-model/src/main/java/org/onap/dcae/analytics/model/util/json/mixin/cef/AlertActionMixin.java   |
| EventSeverityMixin.java        |              1 |             0 |           0 |      0 |           1 |           0 |            0 | dcae-analytics/dcae-analytics-model/src/main/java/org/onap/dcae/analytics/model/util/json/mixin/cef/EventSeverityMixin.java |
| DomainMixin.java               |              1 |             0 |           0 |      0 |           1 |           0 |            0 | dcae-analytics/dcae-analytics-model/src/main/java/org/onap/dcae/analytics/model/util/json/mixin/cef/DomainMixin.java        |
| PriorityMixin.java             |              1 |             0 |           0 |      0 |           1 |           0 |            0 | dcae-analytics/dcae-analytics-model/src/main/java/org/onap/dcae/analytics/model/util/json/mixin/cef/PriorityMixin.java      |
| MrSubscriberPreferences.java   |              1 |             0 |           0 |      0 |           1 |           0 |            0 | dcae-analytics/dcae-analytics-web/src/main/java/org/onap/dcae/analytics/web/dmaap/MrSubscriberPreferences.java              |
| BaseHttpClientPreferences.java |              1 |             0 |           0 |      0 |           1 |           0 |            0 | dcae-analytics/dcae-analytics-web/src/main/java/org/onap/dcae/analytics/web/http/BaseHttpClientPreferences.java             |
| TcaModelConstants.java         |              1 |             0 |           0 |      0 |           1 |           0 |            0 | dcae-analytics/dcae-analytics-model/src/main/java/org/onap/dcae/analytics/model/TcaModelConstants.java                      |

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

## Project: _onap/dcaegen2-services-sdk_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-services-sdk.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-services-sdk) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-services-sdk) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dcaegen2-services-sdk.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                  |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                                                                 |
|:----------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------|
| CbsClientConfiguration.java |              5 |             0 |           0 |      0 |           5 |           0 |            0 | rest-services/cbs-client/src/main/java/org/onap/dcaegen2/services/sdk/rest/services/cbs/client/model/CbsClientConfiguration.java                     |
| MdcVariables.java           |              3 |             0 |           0 |      0 |           3 |           0 |            0 | rest-services/http-client/src/main/java/org/onap/dcaegen2/services/sdk/rest/services/adapters/http/logging/MdcVariables.java                         |
| DummyHttpServer.java        |              1 |             0 |           1 |      0 |           0 |           0 |            0 | rest-services/http-client/src/main/java/org/onap/dcaegen2/services/sdk/rest/services/adapters/http/test/DummyHttpServer.java                         |
| DataStreamUtils.java        |              1 |             0 |           0 |      0 |           1 |           0 |            0 | rest-services/cbs-client/src/main/java/org/onap/dcaegen2/services/sdk/rest/services/cbs/client/impl/streams/gson/DataStreamUtils.java                |
| StreamPredicates.java       |              1 |             0 |           0 |      0 |           1 |           0 |            0 | rest-services/cbs-client/src/main/java/org/onap/dcaegen2/services/sdk/rest/services/cbs/client/api/streams/StreamPredicates.java                     |
| CbsRequests.java            |              1 |             0 |           0 |      0 |           1 |           0 |            0 | rest-services/cbs-client/src/main/java/org/onap/dcaegen2/services/sdk/rest/services/cbs/client/api/CbsRequests.java                                  |
| CbsClientFactory.java       |              1 |             0 |           0 |      0 |           1 |           0 |            0 | rest-services/cbs-client/src/main/java/org/onap/dcaegen2/services/sdk/rest/services/cbs/client/api/CbsClientFactory.java                             |
| SslFactory.java             |              1 |             0 |           0 |      0 |           1 |           0 |            0 | security/ssl/src/main/java/org/onap/dcaegen2/services/sdk/security/ssl/SslFactory.java                                                               |
| StreamsConstants.java       |              1 |             0 |           0 |      0 |           1 |           0 |            0 | rest-services/cbs-client/src/main/java/org/onap/dcaegen2/services/sdk/rest/services/cbs/client/impl/streams/gson/StreamsConstants.java               |
| WireFrameEncoder.java       |              1 |             0 |           1 |      0 |           0 |           0 |            0 | services/hv-ves-client/producer/impl/src/main/java/org/onap/dcaegen2/services/sdk/services/hvves/client/producer/impl/encoders/WireFrameEncoder.java |

