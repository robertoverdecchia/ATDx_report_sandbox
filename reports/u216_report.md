
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
|||
|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-aai-common.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aai-aai-common) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-aai-common) <br> [Complete issue report (JSON)](./json/onap_aai-aai-common.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-schema-service.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aai-schema-service) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-schema-service) <br> [Complete issue report (JSON)](./json/onap_aai-schema-service.json)</p>
# Project report summaries
## Project: _onap/aai-aai-common_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-aai-common.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/aai-aai-common) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-aai-common) <br> [Complete issue report (JSON)](./json/onap_aai-aai-common.json)</p>
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

## Project: _onap/aai-schema-service_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-schema-service.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/aai-schema-service) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-schema-service) <br> [Complete issue report (JSON)](./json/onap_aai-schema-service.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name            |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                             |
|:----------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------|
| XSDElement.java       |             24 |             0 |          24 |      0 |           0 |           0 |            0 | aai-schema-gen/src/main/java/org/onap/aai/schemagen/genxsd/XSDElement.java       |
| NodesYAMLfromOXM.java |             11 |             8 |           2 |      0 |           1 |           0 |            0 | aai-schema-gen/src/main/java/org/onap/aai/schemagen/genxsd/NodesYAMLfromOXM.java |
| YAMLfromOXM.java      |             11 |             8 |           2 |      0 |           1 |           0 |            0 | aai-schema-gen/src/main/java/org/onap/aai/schemagen/genxsd/YAMLfromOXM.java      |
| HTMLfromOXM.java      |              4 |             3 |           1 |      0 |           0 |           0 |            0 | aai-schema-gen/src/main/java/org/onap/aai/schemagen/genxsd/HTMLfromOXM.java      |

