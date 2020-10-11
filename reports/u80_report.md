
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-data-router.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aai-data-router) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-data-router) <br> [Complete issue report (JSON)](./json/onap_aai-data-router.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-search-data-service.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aai-search-data-service) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-search-data-service) <br> [Complete issue report (JSON)](./json/onap_aai-search-data-service.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-sparky-be.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aai-sparky-be) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-sparky-be) <br> [Complete issue report (JSON)](./json/onap_aai-sparky-be.json)</p>
 | |
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-spike.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aai-spike) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-spike) <br> [Complete issue report (JSON)](./json/onap_aai-spike.json)</p>
# Project report summaries
## Project: _onap/aai-data-router_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-data-router.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/aai-data-router) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-data-router) <br> [Complete issue report (JSON)](./json/onap_aai-data-router.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                             |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                |
|:---------------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:------------------------------------------------------------------------------------|
| AbstractSpikeEntityEventProcessor.java |              6 |             0 |           5 |      0 |           1 |           0 |            0 | src/main/java/org/onap/aai/datarouter/policy/AbstractSpikeEntityEventProcessor.java |
| AaiUiSvcPolicyUtil.java                |              5 |             0 |           4 |      0 |           1 |           0 |            0 | src/main/java/org/onap/aai/datarouter/util/AaiUiSvcPolicyUtil.java                  |
| POAAuditException.java                 |              3 |             0 |           3 |      0 |           0 |           0 |            0 | src/main/java/org/onap/aai/datarouter/exception/POAAuditException.java              |
| SearchServiceAgent.java                |              3 |             0 |           3 |      0 |           0 |           0 |            0 | src/main/java/org/onap/aai/datarouter/util/SearchServiceAgent.java                  |

## Project: _onap/aai-search-data-service_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-search-data-service.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/aai-search-data-service) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-search-data-service) <br> [Complete issue report (JSON)](./json/onap_aai-search-data-service.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                              |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:-----------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| search-data-service-app/src/main/java/org/onap/aai/sa/Application.java |             0 |           1 |         0 |           0 |           0 |            0 |     1 |

## Project: _onap/aai-sparky-be_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-sparky-be.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/aai-sparky-be) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-sparky-be) <br> [Complete issue report (JSON)](./json/onap_aai-sparky-be.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                         |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                              |
|:-----------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:------------------------------------------------------------------------------------------------------------------|
| SparkyConstants.java               |             24 |             0 |           0 |      0 |          24 |           0 |            0 | sparkybe-onap-service/src/main/java/org/onap/aai/sparky/viewandinspect/config/SparkyConstants.java                |
| BaseGizmoVisualizationContext.java |             12 |             0 |           1 |      0 |           0 |           0 |           11 | sparkybe-onap-service/src/main/java/org/onap/aai/sparky/viewandinspect/context/BaseGizmoVisualizationContext.java |
| GizmoAdapter.java                  |             10 |             0 |           8 |      0 |           0 |           0 |            2 | sparkybe-onap-service/src/main/java/org/onap/aai/sparky/dal/GizmoAdapter.java                                     |
| BaseVisualizationContext.java      |              9 |             0 |           1 |      0 |           0 |           0 |            8 | sparkybe-onap-service/src/main/java/org/onap/aai/sparky/viewandinspect/context/BaseVisualizationContext.java      |
| ActiveInventoryAdapter.java        |              7 |             0 |           5 |      0 |           0 |           0 |            2 | sparkybe-onap-service/src/main/java/org/onap/aai/sparky/dal/ActiveInventoryAdapter.java                           |
| RestOperationalStatistics.java     |              5 |             0 |           0 |      0 |           0 |           0 |            5 | sparkybe-onap-service/src/main/java/org/onap/aai/sparky/dal/rest/RestOperationalStatistics.java                   |
| EncryptConvertor.java              |              4 |             0 |           3 |      0 |           1 |           0 |            0 | sparkybe-onap-service/src/main/java/org/onap/aai/sparky/util/EncryptConvertor.java                                |
| SyncControllerImpl.java            |              4 |             0 |           2 |      0 |           0 |           0 |            2 | sparkybe-onap-service/src/main/java/org/onap/aai/sparky/sync/SyncControllerImpl.java                              |
| RestClientFactory.java             |              4 |             0 |           0 |      0 |           1 |           0 |            3 | sparkybe-onap-service/src/main/java/org/onap/aai/sparky/dal/rest/RestClientFactory.java                           |
| D3VisualizationOutput.java         |              3 |             0 |           0 |      0 |           3 |           0 |            0 | sparkybe-onap-service/src/main/java/org/onap/aai/sparky/viewandinspect/entity/D3VisualizationOutput.java          |

## Project: _onap/aai-spike_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-spike.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/aai-spike) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-spike) <br> [Complete issue report (JSON)](./json/onap_aai-spike.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                          |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:-------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| src/main/java/org/onap/aai/spike/util/SpikeConstants.java          |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/onap/aai/spike/util/SpikeProperties.java         |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/onap/aai/spike/schema/GraphEventTransformer.java |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/onap/aai/spike/service/SpikeService.java         |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| src/main/java/org/onap/aai/spike/event/incoming/OffsetManager.java |             0 |           0 |         0 |           1 |           0 |            0 |     1 |

