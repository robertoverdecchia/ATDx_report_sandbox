
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
|||
|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_plc4x.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/plc4x) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_plc4x) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_plc4x.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-distribution-journal.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-distribution-journal) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-distribution-journal) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-distribution-journal.json)</p>
# Project report summaries
## Project: _apache/plc4x_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_plc4x.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/plc4x) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_plc4x) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_plc4x.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                      |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                                                         |
|:--------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------------------------------------------------------------------|
| LittleEndianDecoder.java        |             39 |             0 |           0 |      0 |           0 |           0 |           39 | sandbox/test-java-amsads-driver/src/main/java/org/apache/plc4x/java/amsads/protocol/util/LittleEndianDecoder.java                            |
| JavaLanguageTemplateHelper.java |             38 |             0 |          10 |      0 |           0 |           0 |           28 | build-utils/language-java/src/main/java/org/apache/plc4x/language/java/JavaLanguageTemplateHelper.java                                       |
| TriggerConfiguration.java       |             12 |             0 |          12 |      0 |           0 |           0 |            0 | plc4j/tools/scraper/src/main/java/org/apache/plc4x/java/scraper/triggeredscraper/triggerhandler/TriggerConfiguration.java                    |
| DriverTestsuiteRunner.java      |              8 |             0 |           1 |      0 |           0 |           0 |            7 | plc4j/utils/test-utils/src/main/java/org/apache/plc4x/test/driver/DriverTestsuiteRunner.java                                                 |
| S7Step7ServerAdapter.java       |              7 |             0 |           0 |      0 |           0 |           0 |            7 | sandbox/plc-simulator/src/main/java/org/apache/plc4x/simulator/server/s7/protocol/S7Step7ServerAdapter.java                                  |
| SerialChannel.java              |              6 |             0 |           6 |      0 |           0 |           0 |            0 | plc4j/transports/serial/src/main/java/org/apache/plc4x/java/transport/serial/SerialChannel.java                                              |
| Df1Protocol.java                |              5 |             0 |           0 |      0 |           1 |           0 |            4 | sandbox/test-java-df1-driver/src/main/java/org/apache/plc4x/java/df1/protocol/Df1Protocol.java                                               |
| ExpressionStringListener.java   |              5 |             0 |           5 |      0 |           0 |           0 |            0 | build-utils/protocol-base-mspec/src/main/java/org/apache/plc4x/plugins/codegenerator/language/mspec/expression/ExpressionStringListener.java |
| WaterTankService.java           |              5 |             0 |           5 |      0 |           0 |           0 |            0 | plc4j/examples/hello-webapp/webapp/src/main/java/org/apache/plc4x/examples/watertank/service/WaterTankService.java                           |
| DF1Utils.java                   |              5 |             0 |           4 |      0 |           1 |           0 |            0 | sandbox/test-java-df1-driver/src/main/java/org/apache/plc4x/java/df1/util/DF1Utils.java                                                      |

## Project: _apache/sling-org-apache-sling-distribution-journal_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-distribution-journal.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-distribution-journal) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-distribution-journal) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-distribution-journal.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                 |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                          |
|:---------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------------------------------------|
| LocalStore.java            |              3 |             0 |           3 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/distribution/journal/impl/subscriber/LocalStore.java           |
| DistributionPublisher.java |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/distribution/journal/impl/publisher/DistributionPublisher.java |
| PubQueueCache.java         |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/distribution/journal/impl/queue/impl/PubQueueCache.java        |
| JMXRegistration.java       |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/distribution/journal/impl/shared/JMXRegistration.java          |

