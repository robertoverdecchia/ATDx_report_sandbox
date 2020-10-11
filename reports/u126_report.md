
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="./plots/onap_aai-aai-common.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aai-aai-common) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-aai-common) <br> [Complete issue report (JSON)](./json/onap_aai-aai-common.json)</p>|<img src="./plots/onap_aai-data-router.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aai-data-router) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-data-router) <br> [Complete issue report (JSON)](./json/onap_aai-data-router.json)</p>|<img src="./plots/onap_aai-sparky-be.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aai-sparky-be) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-sparky-be) <br> [Complete issue report (JSON)](./json/onap_aai-sparky-be.json)</p>
 | |

# Project report summaries
## Project: _onap/aai-aai-common_
|./plots/onap_aai-aai-common.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/aai-aai-common) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-aai-common) <br> [Complete issue report (JSON)](./json/onap_aai-aai-common.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name              |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                   |
|:------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------------|
| HttpEntry.java          |             22 |             0 |          19 |      0 |           3 |           0 |            0 | aai-core/src/main/java/org/onap/aai/rest/db/HttpEntry.java                             |
| PojoUtils.java          |              9 |             0 |           9 |      0 |           0 |           0 |            0 | aai-core/src/main/java/org/onap/aai/util/PojoUtils.java                                |
| Auth.java               |              7 |             0 |           7 |      0 |           0 |           0 |            0 | aai-auth/src/main/java/org/onap/aaiauth/auth/Auth.java                                 |
| DBSerializer.java       |              6 |             0 |           5 |      0 |           1 |           0 |            0 | aai-core/src/main/java/org/onap/aai/serialization/db/DBSerializer.java                 |
| ErrorLogHelper.java     |              5 |             0 |           3 |      0 |           2 |           0 |            0 | aai-els-onap-logging/src/main/java/org/onap/aai/logging/ErrorLogHelper.java            |
| RestClient.java         |              5 |             0 |           5 |      0 |           0 |           0 |            0 | aai-rest/src/main/java/org/onap/aai/restclient/RestClient.java                         |
| AAIException.java       |              5 |             0 |           5 |      0 |           0 |           0 |            0 | aai-els-onap-logging/src/main/java/org/onap/aai/exceptions/AAIException.java           |
| OxmModelLoader.java     |              5 |             0 |           4 |      0 |           1 |           0 |            0 | aai-utils/src/main/java/org/onap/aaiutils/oxm/OxmModelLoader.java                      |
| RelationshipSchema.java |              4 |             0 |           4 |      0 |           0 |           0 |            0 | aai-schema-abstraction/src/main/java/org/onap/aai/schemaif/oxm/RelationshipSchema.java |
| Constants.java          |              4 |             0 |           0 |      0 |           4 |           0 |            0 | aai-els-onap-logging/src/main/java/org/onap/logging/filter/base/Constants.java         |

## Project: _onap/aai-data-router_
|./plots/onap_aai-data-router.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/aai-data-router) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-data-router) <br> [Complete issue report (JSON)](./json/onap_aai-data-router.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                             |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                |
|:---------------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:------------------------------------------------------------------------------------|
| AbstractSpikeEntityEventProcessor.java |              6 |             0 |           5 |      0 |           1 |           0 |            0 | src/main/java/org/onap/aai/datarouter/policy/AbstractSpikeEntityEventProcessor.java |
| AaiUiSvcPolicyUtil.java                |              5 |             0 |           4 |      0 |           1 |           0 |            0 | src/main/java/org/onap/aai/datarouter/util/AaiUiSvcPolicyUtil.java                  |
| POAAuditException.java                 |              3 |             0 |           3 |      0 |           0 |           0 |            0 | src/main/java/org/onap/aai/datarouter/exception/POAAuditException.java              |
| SearchServiceAgent.java                |              3 |             0 |           3 |      0 |           0 |           0 |            0 | src/main/java/org/onap/aai/datarouter/util/SearchServiceAgent.java                  |

## Project: _onap/aai-sparky-be_
|./plots/onap_aai-sparky-be.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/aai-sparky-be) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-sparky-be) <br> [Complete issue report (JSON)](./json/onap_aai-sparky-be.json)</p>
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

