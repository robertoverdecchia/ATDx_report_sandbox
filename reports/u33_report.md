
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_ccsdk-features.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/ccsdk-features) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_ccsdk-features) <br> [Complete issue report (JSON)](./json/onap_ccsdk-features.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_ccsdk-sli-adaptors.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/ccsdk-sli-adaptors) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_ccsdk-sli-adaptors) <br> [Complete issue report (JSON)](./json/onap_ccsdk-sli-adaptors.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_ccsdk-sli-core.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/ccsdk-sli-core) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_ccsdk-sli-core) <br> [Complete issue report (JSON)](./json/onap_ccsdk-sli-core.json)</p>
 | |
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_ccsdk-sli-northbound.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/ccsdk-sli-northbound) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_ccsdk-sli-northbound) <br> [Complete issue report (JSON)](./json/onap_ccsdk-sli-northbound.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_ccsdk-sli-plugins.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/ccsdk-sli-plugins) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_ccsdk-sli-plugins) <br> [Complete issue report (JSON)](./json/onap_ccsdk-sli-plugins.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_sdnc-northbound.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/sdnc-northbound) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdnc-northbound) <br> [Complete issue report (JSON)](./json/onap_sdnc-northbound.json)</p>
 | |

# Project report summaries
## Project: _onap/ccsdk-features_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_ccsdk-features.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/ccsdk-features) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_ccsdk-features) <br> [Complete issue report (JSON)](./json/onap_ccsdk-features.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name          |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                                     |
|:--------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-------------------------------------------------------------------------------------------------------------------------|
| Program.java        |             12 |             0 |          12 |      0 |           0 |           0 |            0 | sdnr/wt/data-provider/setup/src/main/java/org/onap/ccsdk/features/sdnr/wt/dataprovider/setup/Program.java                |
| MessageDaoImpl.java |              8 |             0 |           8 |      0 |           0 |           0 |            0 | lib/doorman/src/main/java/org/onap/ccsdk/features/lib/doorman/dao/MessageDaoImpl.java                                    |
| MyOdluxBundle.java  |              8 |             8 |           0 |      0 |           0 |           0 |            0 | sdnr/wt/odlux/apps/maintenanceApp/src2/main/java/org/onap/ccsdk/features/sdnr/wt/odlux/bundles/MyOdluxBundle.java        |
| MyOdluxBundle.java  |              8 |             8 |           0 |      0 |           0 |           0 |            0 | sdnr/wt/odlux/apps/apiDemo/src2/main/java/org/onap/ccsdk/features/sdnr/wt/odlux/bundles/MyOdluxBundle.java               |
| MyOdluxBundle.java  |              8 |             8 |           0 |      0 |           0 |           0 |            0 | sdnr/wt/odlux/apps/mediatorApp/src2/main/java/org/onap/ccsdk/features/sdnr/wt/odlux/bundles/MyOdluxBundle.java           |
| MyOdluxBundle.java  |              8 |             8 |           0 |      0 |           0 |           0 |            0 | sdnr/wt/odlux/apps/performanceHistoryApp/src2/main/java/org/onap/ccsdk/features/sdnr/wt/odlux/bundles/MyOdluxBundle.java |
| MyOdluxBundle.java  |              8 |             8 |           0 |      0 |           0 |           0 |            0 | sdnr/wt/odlux/apps/configurationApp/src2/main/java/org/onap/ccsdk/features/sdnr/wt/odlux/bundles/MyOdluxBundle.java      |
| MyOdluxBundle.java  |              8 |             8 |           0 |      0 |           0 |           0 |            0 | sdnr/wt/odlux/apps/connectApp/src2/main/java/org/onap/ccsdk/features/sdnr/wt/odlux/bundles/MyOdluxBundle.java            |
| MyOdluxBundle.java  |              8 |             8 |           0 |      0 |           0 |           0 |            0 | sdnr/wt/odlux/apps/inventoryApp/src2/main/java/org/onap/ccsdk/features/sdnr/wt/odlux/bundles/MyOdluxBundle.java          |
| MyOdluxBundle.java  |              8 |             8 |           0 |      0 |           0 |           0 |            0 | sdnr/wt/odlux/apps/minimumApp/src2/main/java/org/onap/ccsdk/features/sdnr/wt/odlux/bundles/MyOdluxBundle.java            |

## Project: _onap/ccsdk-sli-adaptors_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_ccsdk-sli-adaptors.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/ccsdk-sli-adaptors) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_ccsdk-sli-adaptors) <br> [Complete issue report (JSON)](./json/onap_ccsdk-sli-adaptors.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                  |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                       |
|:----------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------------------------------------------------|
| ResourceRequest.java        |             23 |             0 |           0 |      0 |          23 |           0 |            0 | resource-assignment/provider/src/main/java/org/onap/ccsdk/sli/adaptors/ra/comp/ResourceRequest.java        |
| ResourceRule.java           |             11 |             0 |           0 |      0 |          11 |           0 |            0 | resource-assignment/provider/src/main/java/org/onap/ccsdk/sli/adaptors/ra/rule/data/ResourceRule.java      |
| RangeAllocationRequest.java |             10 |             0 |           0 |      0 |          10 |           0 |            0 | resource-assignment/provider/src/main/java/org/onap/ccsdk/sli/adaptors/rm/data/RangeAllocationRequest.java |
| AllocationItem.java         |             10 |             0 |           0 |      0 |          10 |           0 |            0 | resource-assignment/provider/src/main/java/org/onap/ccsdk/sli/adaptors/rm/dao/jdbc/AllocationItem.java     |
| ResourceResponse.java       |              9 |             0 |           0 |      0 |           9 |           0 |            0 | resource-assignment/provider/src/main/java/org/onap/ccsdk/sli/adaptors/ra/comp/ResourceResponse.java       |
| AllocationRequest.java      |              9 |             0 |           0 |      0 |           9 |           0 |            0 | resource-assignment/provider/src/main/java/org/onap/ccsdk/sli/adaptors/rm/data/AllocationRequest.java      |
| Resource.java               |              8 |             0 |           0 |      0 |           8 |           0 |            0 | resource-assignment/provider/src/main/java/org/onap/ccsdk/sli/adaptors/rm/dao/jdbc/Resource.java           |
| ResourceData.java           |              8 |             0 |           0 |      0 |           8 |           0 |            0 | resource-assignment/provider/src/main/java/org/onap/ccsdk/sli/adaptors/ra/comp/ResourceData.java           |
| ResourceAllocator.java      |              8 |             0 |           8 |      0 |           0 |           0 |            0 | resource-assignment/provider/src/main/java/org/onap/ccsdk/sli/adaptors/ra/ResourceAllocator.java           |
| AAIDeclarations.java        |              7 |             0 |           4 |      0 |           0 |           0 |            3 | aai-service/provider/src/main/java/org/onap/ccsdk/sli/adaptors/aai/AAIDeclarations.java                    |

## Project: _onap/ccsdk-sli-core_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_ccsdk-sli-core.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/ccsdk-sli-core) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_ccsdk-sli-core) <br> [Complete issue report (JSON)](./json/onap_ccsdk-sli-core.json)</p>
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
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_ccsdk-sli-northbound.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/ccsdk-sli-northbound) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_ccsdk-sli-northbound) <br> [Complete issue report (JSON)](./json/onap_ccsdk-sli-northbound.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                                                                       |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:--------------------------------------------------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| ueb-listener/src/main/java/org/onap/ccsdk/sli/northbound/uebclient/SdncGroupModel.java                                          |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| ueb-listener/src/main/java/org/onap/ccsdk/sli/northbound/uebclient/SdncOdlConnection.java                                       |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| daexim-offsite-backup/provider/src/main/java/org/onap/ccsdk/sli/northbound/daeximoffsitebackup/DaeximOffsiteBackupProvider.java |             0 |           0 |         0 |           0 |           0 |            0 |     0 |

## Project: _onap/ccsdk-sli-plugins_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_ccsdk-sli-plugins.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/ccsdk-sli-plugins) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_ccsdk-sli-plugins) <br> [Complete issue report (JSON)](./json/onap_ccsdk-sli-plugins.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name             |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                 |
|:-----------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------------------------------------------|
| Parameters.java        |             31 |             0 |           0 |      0 |          31 |           0 |            0 | restapi-call-node/provider/src/main/java/org/onap/ccsdk/sli/plugins/restapicall/Parameters.java      |
| RestapiCallNode.java   |             17 |             0 |           0 |      0 |          17 |           0 |            0 | restapi-call-node/provider/src/main/java/org/onap/ccsdk/sli/plugins/restapicall/RestapiCallNode.java |
| Parameters.java        |             15 |             0 |           0 |      0 |          15 |           0 |            0 | sshapi-call-node/provider/src/main/java/org/onap/ccsdk/sli/plugins/sshapicall/model/Parameters.java  |
| HttpResponse.java      |              5 |             0 |           0 |      0 |           5 |           0 |            0 | restapi-call-node/provider/src/main/java/org/onap/ccsdk/sli/plugins/restapicall/HttpResponse.java    |
| Parameters.java        |              4 |             0 |           0 |      0 |           4 |           0 |            0 | properties-node/provider/src/main/java/org/onap/ccsdk/sli/plugins/prop/Parameters.java               |
| GrToolkitProvider.java |              3 |             0 |           0 |      0 |           3 |           0 |            0 | grToolkit/provider/src/main/java/org/onap/ccsdk/sli/plugins/grtoolkit/GrToolkitProvider.java         |

## Project: _onap/sdnc-northbound_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_sdnc-northbound.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/sdnc-northbound) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdnc-northbound) <br> [Complete issue report (JSON)](./json/onap_sdnc-northbound.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                              |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:-----------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| vnfapi/provider/src/main/java/org/onap/sdnc/vnfapi/VnfApiProvider.java |             0 |           0 |         0 |           0 |           1 |            0 |     1 |

