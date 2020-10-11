
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_ccsdk-dashboard.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/ccsdk-dashboard) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_ccsdk-dashboard) <br> [Complete issue report (JSON)](./json/onap_ccsdk-dashboard.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-analytics-tca-gen2.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-analytics-tca-gen2) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-analytics-tca-gen2) <br> [Complete issue report (JSON)](./json/onap_dcaegen2-analytics-tca-gen2.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-platform-inventory-api.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-platform-inventory-api) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-platform-inventory-api) <br> [Complete issue report (JSON)](./json/onap_dcaegen2-platform-inventory-api.json)</p>
 | |

# Project report summaries
## Project: _onap/ccsdk-dashboard_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_ccsdk-dashboard.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/ccsdk-dashboard) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_ccsdk-dashboard) <br> [Complete issue report (JSON)](./json/onap_ccsdk-dashboard.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                         |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                  |
|:-----------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:------------------------------------------------------------------------------------------------------|
| CommonApiController.java           |             22 |             0 |          22 |      0 |           0 |           0 |            0 | ccsdk-app-common/src/main/java/org/onap/ccsdk/dashboard/controller/CommonApiController.java           |
| CloudifyController.java            |             19 |             0 |          19 |      0 |           0 |           0 |            0 | ccsdk-app-common/src/main/java/org/onap/ccsdk/dashboard/controller/CloudifyController.java            |
| ServiceTypeRequest.java            |             13 |             0 |           0 |      0 |          13 |           0 |            0 | ccsdk-app-common/src/main/java/org/onap/ccsdk/dashboard/model/inventory/ServiceTypeRequest.java       |
| ConsulController.java              |             11 |             0 |          11 |      0 |           0 |           0 |            0 | ccsdk-app-common/src/main/java/org/onap/ccsdk/dashboard/controller/ConsulController.java              |
| InventoryController.java           |             10 |             0 |          10 |      0 |           0 |           0 |            0 | ccsdk-app-common/src/main/java/org/onap/ccsdk/dashboard/controller/InventoryController.java           |
| ServiceComponent.java              |              9 |             0 |           0 |      0 |           9 |           0 |            0 | ccsdk-app-common/src/main/java/org/onap/ccsdk/dashboard/model/inventory/ServiceComponent.java         |
| Link.java                          |              8 |             0 |           0 |      0 |           8 |           0 |            0 | ccsdk-app-common/src/main/java/org/onap/ccsdk/dashboard/model/inventory/Link.java                     |
| CloudifyExecutionRequest.java      |              6 |             0 |           0 |      0 |           6 |           0 |            0 | ccsdk-app-common/src/main/java/org/onap/ccsdk/dashboard/model/CloudifyExecutionRequest.java           |
| ServiceTypeUploadRequest.java      |              6 |             0 |           0 |      0 |           6 |           0 |            0 | ccsdk-app-common/src/main/java/org/onap/ccsdk/dashboard/model/inventory/ServiceTypeUploadRequest.java |
| ControllerEndpointCredentials.java |              6 |             0 |           2 |      0 |           4 |           0 |            0 | ccsdk-app-common/src/main/java/org/onap/ccsdk/dashboard/model/ControllerEndpointCredentials.java      |

## Project: _onap/dcaegen2-analytics-tca-gen2_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-analytics-tca-gen2.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-analytics-tca-gen2) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-analytics-tca-gen2) <br> [Complete issue report (JSON)](./json/onap_dcaegen2-analytics-tca-gen2.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name             |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                 |
|:-----------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------------------------------------------|
| BaseAnalyticsTest.java |              5 |             0 |           3 |      0 |           2 |           0 |            0 | dcae-analytics/dcae-analytics-test/src/main/java/org/onap/dcae/analytics/test/BaseAnalyticsTest.java |

## Project: _onap/dcaegen2-platform-inventory-api_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-platform-inventory-api.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-platform-inventory-api) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-platform-inventory-api) <br> [Complete issue report (JSON)](./json/onap_dcaegen2-platform-inventory-api.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                  |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:---------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| src/main/java/io/swagger/api/impl/DcaeServiceTypesQueryStatement.java      |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/onap/dcae/inventory/daos/DCAEServiceTransactionDAO.java  |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/onap/dcae/inventory/clients/DatabusControllerClient.java |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| src/main/java/io/swagger/api/impl/DcaeServiceTypeObjectRepository.java     |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
