
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
|||
|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-aai-common.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aai-aai-common) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-aai-common) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_aai-aai-common.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-traversal.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aai-traversal) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-traversal) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_aai-traversal.json)</p>
# Project report summaries
## Project: _onap/aai-aai-common_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-aai-common.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/aai-aai-common) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-aai-common) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_aai-aai-common.json)</p>
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

## Project: _onap/aai-traversal_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-traversal.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/aai-traversal) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-traversal) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_aai-traversal.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                          |
|:--------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:------------------------------------------------------------------------------|
| ModelBasedProcessing.java |              6 |             0 |           0 |      0 |           6 |           0 |            0 | aai-traversal/src/main/java/org/onap/aai/dbgraphgen/ModelBasedProcessing.java |
| DslConsumer.java          |              2 |             0 |           0 |      0 |           2 |           0 |            0 | aai-traversal/src/main/java/org/onap/aai/rest/DslConsumer.java                |
| AuthorizationService.java |              2 |             0 |           2 |      0 |           0 |           0 |            0 | aai-traversal/src/main/java/org/onap/aai/service/AuthorizationService.java    |
| NodeQueryProcessor.java   |              2 |             2 |           0 |      0 |           0 |           0 |            0 | aai-traversal/src/main/java/org/onap/aai/rest/search/NodeQueryProcessor.java  |
| QueryConsumer.java        |              2 |             0 |           0 |      0 |           2 |           0 |            0 | aai-traversal/src/main/java/org/onap/aai/rest/QueryConsumer.java              |
| AAIDslErrorListener.java  |              1 |             0 |           1 |      0 |           0 |           0 |            0 | aai-traversal/src/main/java/org/onap/aai/rest/dsl/AAIDslErrorListener.java    |
| DslListener.java          |              1 |             0 |           1 |      0 |           0 |           0 |            0 | aai-traversal/src/main/java/org/onap/aai/rest/dsl/v2/DslListener.java         |
| SearchProvider.java       |              1 |             0 |           0 |      0 |           1 |           0 |            0 | aai-traversal/src/main/java/org/onap/aai/rest/search/SearchProvider.java      |
| DslContext.java           |              1 |             0 |           0 |      0 |           1 |           0 |            0 | aai-traversal/src/main/java/org/onap/aai/rest/dsl/DslContext.java             |
| DslListener.java          |              1 |             0 |           1 |      0 |           0 |           0 |            0 | aai-traversal/src/main/java/org/onap/aai/rest/dsl/v1/DslListener.java         |

