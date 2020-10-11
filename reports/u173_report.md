
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
|||
|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-aai-common.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aai-aai-common) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-aai-common) <br> [Complete issue report (JSON)](./json/onap_aai-aai-common.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-graphadmin.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aai-graphadmin) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-graphadmin) <br> [Complete issue report (JSON)](./json/onap_aai-graphadmin.json)</p>
# Project report summaries
## Project: _onap/aai-aai-common_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-aai-common.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/aai-aai-common) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-aai-common) <br> [Complete issue report (JSON)](./json/onap_aai-aai-common.json)</p>
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

## Project: _onap/aai-graphadmin_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-graphadmin.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/aai-graphadmin) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-graphadmin) <br> [Complete issue report (JSON)](./json/onap_aai-graphadmin.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                             |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                           |
|:---------------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-------------------------------------------------------------------------------|
| PartialPropAndEdgeLoader.java          |             12 |             0 |          11 |      0 |           1 |           0 |            0 | src/main/java/org/onap/aai/datasnapshot/PartialPropAndEdgeLoader.java          |
| PartialPropAndEdgeLoader4HistInit.java |             12 |             0 |          11 |      0 |           1 |           0 |            0 | src/main/java/org/onap/aai/datasnapshot/PartialPropAndEdgeLoader4HistInit.java |
| DataSnapshot.java                      |             10 |             0 |          10 |      0 |           0 |           0 |            0 | src/main/java/org/onap/aai/datasnapshot/DataSnapshot.java                      |
| DataSnapshot4HistInit.java             |             10 |             0 |          10 |      0 |           0 |           0 |            0 | src/main/java/org/onap/aai/datasnapshot/DataSnapshot4HistInit.java             |
| DataGrooming.java                      |              6 |             0 |           2 |      0 |           4 |           0 |            0 | src/main/java/org/onap/aai/datagrooming/DataGrooming.java                      |
| DupeTool.java                          |              5 |             0 |           1 |      0 |           4 |           0 |            0 | src/main/java/org/onap/aai/dbgen/DupeTool.java                                 |
| UpdatePropertyTool.java                |              4 |             0 |           0 |      0 |           4 |           0 |            0 | src/main/java/org/onap/aai/dbgen/UpdatePropertyTool.java                       |
| PartialVertexLoader.java               |              4 |             0 |           4 |      0 |           0 |           0 |            0 | src/main/java/org/onap/aai/datasnapshot/PartialVertexLoader.java               |
| MigrateINVPhysicalInventory.java       |              4 |             0 |           4 |      0 |           0 |           0 |            0 | src/main/java/org/onap/aai/migration/v12/MigrateINVPhysicalInventory.java      |
| DataGroomingTasks.java                 |              3 |             0 |           2 |      0 |           0 |           1 |            0 | src/main/java/org/onap/aai/datagrooming/DataGroomingTasks.java                 |

