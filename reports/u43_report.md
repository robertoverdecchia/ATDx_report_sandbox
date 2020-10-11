
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-analytics-tca-gen2.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-analytics-tca-gen2) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-analytics-tca-gen2) <br> [Complete issue report (JSON)](./json/onap_dcaegen2-analytics-tca-gen2.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-collectors-ves.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-collectors-ves) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-collectors-ves) <br> [Complete issue report (JSON)](./json/onap_dcaegen2-collectors-ves.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-services-sdk.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-services-sdk) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-services-sdk) <br> [Complete issue report (JSON)](./json/onap_dcaegen2-services-sdk.json)</p>
 | |

# Project report summaries
## Project: _onap/dcaegen2-analytics-tca-gen2_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-analytics-tca-gen2.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-analytics-tca-gen2) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-analytics-tca-gen2) <br> [Complete issue report (JSON)](./json/onap_dcaegen2-analytics-tca-gen2.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name             |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                 |
|:-----------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------------------------------------------|
| BaseAnalyticsTest.java |              5 |             0 |           3 |      0 |           2 |           0 |            0 | dcae-analytics/dcae-analytics-test/src/main/java/org/onap/dcae/analytics/test/BaseAnalyticsTest.java |

## Project: _onap/dcaegen2-collectors-ves_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-collectors-ves.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-collectors-ves) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-collectors-ves) <br> [Complete issue report (JSON)](./json/onap_dcaegen2-collectors-ves.json)</p>
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

## Project: _onap/dcaegen2-services-sdk_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-services-sdk.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-services-sdk) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-services-sdk) <br> [Complete issue report (JSON)](./json/onap_dcaegen2-services-sdk.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                  |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                                             |
|:----------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------------------------------------------------------|
| CbsClientConfiguration.java |              5 |             0 |           0 |      0 |           5 |           0 |            0 | rest-services/cbs-client/src/main/java/org/onap/dcaegen2/services/sdk/rest/services/cbs/client/model/CbsClientConfiguration.java |
| MdcVariables.java           |              3 |             0 |           0 |      0 |           3 |           0 |            0 | rest-services/http-client/src/main/java/org/onap/dcaegen2/services/sdk/rest/services/adapters/http/logging/MdcVariables.java     |

