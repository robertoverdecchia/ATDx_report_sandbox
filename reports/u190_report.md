
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
|||
|-|-|
|<img src="./plots/onap_ccsdk-sli-core.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/ccsdk-sli-core) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_ccsdk-sli-core) <br> [Complete issue report (JSON)](./json/onap_ccsdk-sli-core.json)</p>|<img src="./plots/onap_ccsdk-sli-northbound.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/ccsdk-sli-northbound) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_ccsdk-sli-northbound) <br> [Complete issue report (JSON)](./json/onap_ccsdk-sli-northbound.json)</p>
# Project report summaries
## Project: _onap/ccsdk-sli-core_
|./plots/onap_ccsdk-sli-core.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/ccsdk-sli-core) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_ccsdk-sli-core) <br> [Complete issue report (JSON)](./json/onap_ccsdk-sli-core.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name               |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                             |
|:-------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-------------------------------------------------------------------------------------------------|
| MdsalHelper.java         |              6 |             0 |           0 |      0 |           6 |           0 |            0 | sli/provider/src/main/java/org/onap/ccsdk/sli/core/sli/provider/MdsalHelper.java                 |
| MessageWriter.java       |              3 |             0 |           0 |      0 |           2 |           1 |            0 | sli/common/src/main/java/org/onap/ccsdk/sli/core/sli/MessageWriter.java                          |
| DBConfigFactory.java     |              3 |             0 |           2 |      0 |           1 |           0 |            0 | dblib/provider/src/main/java/org/onap/ccsdk/sli/core/dblib/factory/DBConfigFactory.java          |
| SliStringUtils.java      |              3 |             0 |           3 |      0 |           0 |           0 |            0 | sliPluginUtils/provider/src/main/java/org/onap/ccsdk/sli/core/slipluginutils/SliStringUtils.java |
| BaseDBConfiguration.java |              3 |             0 |           3 |      0 |           0 |           0 |            0 | dblib/provider/src/main/java/org/onap/ccsdk/sli/core/dblib/config/BaseDBConfiguration.java       |
| MetricLogger.java        |              3 |             0 |           0 |      0 |           3 |           0 |            0 | sli/common/src/main/java/org/onap/ccsdk/sli/core/sli/MetricLogger.java                           |

## Project: _onap/ccsdk-sli-northbound_
|./plots/onap_ccsdk-sli-northbound.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/ccsdk-sli-northbound) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_ccsdk-sli-northbound) <br> [Complete issue report (JSON)](./json/onap_ccsdk-sli-northbound.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                                                                       |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:--------------------------------------------------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| ueb-listener/src/main/java/org/onap/ccsdk/sli/northbound/uebclient/SdncGroupModel.java                                          |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| ueb-listener/src/main/java/org/onap/ccsdk/sli/northbound/uebclient/SdncOdlConnection.java                                       |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| daexim-offsite-backup/provider/src/main/java/org/onap/ccsdk/sli/northbound/daeximoffsitebackup/DaeximOffsiteBackupProvider.java |             0 |           0 |         0 |           0 |           0 |            0 |     0 |

