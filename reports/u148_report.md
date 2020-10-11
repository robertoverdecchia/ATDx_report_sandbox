
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
|||
|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-datarouter.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-datarouter) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-datarouter) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dmaap-datarouter.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-dbcapi.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-dbcapi) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-dbcapi) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dmaap-dbcapi.json)</p>
# Project report summaries
## Project: _onap/dmaap-datarouter_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-datarouter.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-datarouter) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-datarouter) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dmaap-datarouter.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name         |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                          |
|:-------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------------------------------------|
| StatusLog.java     |              4 |             0 |           0 |      0 |           4 |           0 |            0 | datarouter-node/src/main/java/org/onap/dmaap/datarouter/node/StatusLog.java                   |
| RLEBitSet.java     |              2 |             2 |           0 |      0 |           0 |           0 |            0 | datarouter-prov/src/main/java/org/onap/dmaap/datarouter/provisioning/utils/RLEBitSet.java     |
| LOGJSONObject.java |              2 |             2 |           0 |      0 |           0 |           0 |            0 | datarouter-prov/src/main/java/org/onap/dmaap/datarouter/provisioning/utils/LOGJSONObject.java |
| NodeConfig.java    |              1 |             0 |           0 |      0 |           1 |           0 |            0 | datarouter-node/src/main/java/org/onap/dmaap/datarouter/node/NodeConfig.java                  |

## Project: _onap/dmaap-dbcapi_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-dbcapi.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-dbcapi) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-dbcapi) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dmaap-dbcapi.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name          |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                             |
|:--------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------|
| DBFieldHandler.java |              7 |             0 |           7 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/dbcapi/database/DBFieldHandler.java |
| AafLurService.java  |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/dbcapi/aaf/AafLurService.java       |
| DatabaseClass.java  |              1 |             0 |           1 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/dbcapi/database/DatabaseClass.java  |
| ConnWrapper.java    |              1 |             0 |           1 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/dbcapi/database/ConnWrapper.java    |
| TableHandler.java   |              1 |             0 |           1 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/dbcapi/database/TableHandler.java   |
| ApiService.java     |              1 |             0 |           1 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/dbcapi/service/ApiService.java      |
| Main.java           |              1 |             0 |           1 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/dbcapi/server/Main.java             |
| AafObject.java      |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/onap/dmaap/dbcapi/aaf/AafObject.java           |
| DBSingleton.java    |              1 |             0 |           1 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/dbcapi/database/DBSingleton.java    |

