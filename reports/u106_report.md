
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-resources.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aai-resources) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-resources) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_aai-resources.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_sdc-sdc-be-common.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/sdc-sdc-be-common) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdc-sdc-be-common) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_sdc-sdc-be-common.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_sdc.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/sdc) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdc) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_sdc.json)</p>
 | |

# Project report summaries
## Project: _onap/aai-resources_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-resources.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/aai-resources) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-resources) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_aai-resources.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                          |
|:--------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:------------------------------------------------------------------------------|
| DataImportTasks.java      |              4 |             0 |           3 |      0 |           0 |           1 |            0 | aai-resources/src/main/java/org/onap/aai/TenantIsolation/DataImportTasks.java |
| BulkConsumer.java         |              3 |             0 |           3 |      0 |           0 |           0 |            0 | aai-resources/src/main/java/org/onap/aai/rest/BulkConsumer.java               |
| IncreaseNodesTool.java    |              3 |             0 |           2 |      0 |           1 |           0 |            0 | aai-resources/src/main/java/org/onap/aai/IncreaseNodesTool.java               |
| LegacyMoxyConsumer.java   |              2 |             0 |           0 |      0 |           2 |           0 |            0 | aai-resources/src/main/java/org/onap/aai/rest/LegacyMoxyConsumer.java         |
| AuthorizationService.java |              2 |             0 |           2 |      0 |           0 |           0 |            0 | aai-resources/src/main/java/org/onap/aai/service/AuthorizationService.java    |
| LogFormatTools.java       |              1 |             0 |           0 |      0 |           1 |           0 |            0 | aai-resources/src/main/java/org/onap/aai/rest/util/LogFormatTools.java        |
| Command.java              |              1 |             0 |           1 |      0 |           0 |           0 |            0 | aai-resources/src/main/java/org/onap/aai/dbgen/tags/Command.java              |
| PositiveNumValidator.java |              1 |             0 |           1 |      0 |           0 |           0 |            0 | aai-resources/src/main/java/org/onap/aai/util/PositiveNumValidator.java       |
| ResourcesApp.java         |              1 |             0 |           1 |      0 |           0 |           0 |            0 | aai-resources/src/main/java/org/onap/aai/ResourcesApp.java                    |

## Project: _onap/sdc-sdc-be-common_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_sdc-sdc-be-common.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/sdc-sdc-be-common) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdc-sdc-be-common) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_sdc-sdc-be-common.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                     |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                 |
|:-------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------------------------------------------|
| Logger.java                    |             21 |             0 |           0 |      0 |          21 |           0 |            0 | security-util-lib/src/main/java/org/onap/sdc/security/logging/wrappers/Logger.java                   |
| LoggerError.java               |              2 |             2 |           0 |      0 |           0 |           0 |            0 | security-util-lib/src/main/java/org/onap/sdc/security/logging/elements/LoggerError.java              |
| FilterServletOutputStream.java |              2 |             2 |           0 |      0 |           0 |           0 |            0 | security-util-lib/src/main/java/org/onap/sdc/security/filters/FilterServletOutputStream.java         |
| SecurityLogsUtils.java         |              2 |             0 |           0 |      0 |           2 |           0 |            0 | security-util-lib/src/main/java/org/onap/sdc/security/utils/SecurityLogsUtils.java                   |
| RepresentationUtils.java       |              1 |             0 |           0 |      0 |           1 |           0 |            0 | security-util-lib/src/main/java/org/onap/sdc/security/RepresentationUtils.java                       |
| AuthenticationCookieUtils.java |              1 |             0 |           0 |      0 |           1 |           0 |            0 | security-util-lib/src/main/java/org/onap/sdc/security/AuthenticationCookieUtils.java                 |
| CipherUtil.java                |              1 |             0 |           0 |      0 |           1 |           0 |            0 | security-util-lib/src/main/java/org/onap/sdc/security/CipherUtil.java                                |
| RestrictionAccessFilter.java   |              1 |             1 |           0 |      0 |           0 |           0 |            0 | security-util-lib/src/main/java/org/onap/sdc/security/filters/RestrictionAccessFilter.java           |
| RestUtils.java                 |              1 |             0 |           0 |      0 |           1 |           0 |            0 | security-util-lib/src/main/java/org/onap/sdc/security/utils/RestUtils.java                           |
| SynchronizationState.java      |              1 |             1 |           0 |      0 |           0 |           0 |            0 | versioning-lib/src/main/java/org/onap/sdc/common/versioning/services/types/SynchronizationState.java |

## Project: _onap/sdc_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_sdc.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/sdc) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdc) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_sdc.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                         |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                      |
|:-----------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------------------------------------------------|
| ArtifactsBusinessLogic.java        |             31 |             0 |           0 |      0 |          31 |           0 |            0 | catalog-be/src/main/java/org/openecomp/sdc/be/components/impl/ArtifactsBusinessLogic.java                 |
| ResourceBusinessLogic.java         |             22 |             3 |           0 |      0 |          19 |           0 |            0 | catalog-be/src/main/java/org/openecomp/sdc/be/components/impl/ResourceBusinessLogic.java                  |
| Logger.java                        |             21 |             0 |           0 |      0 |          21 |           0 |            0 | common-app-logging/src/main/java/org/openecomp/sdc/common/log/wrappers/Logger.java                        |
| DistributionNotificationEvent.java |             11 |            10 |           0 |      0 |           1 |           0 |            0 | catalog-dao/src/main/java/org/openecomp/sdc/be/resources/data/auditing/DistributionNotificationEvent.java |
| ResourceAdminEvent.java            |             11 |            10 |           0 |      0 |           1 |           0 |            0 | catalog-dao/src/main/java/org/openecomp/sdc/be/resources/data/auditing/ResourceAdminEvent.java            |
| CategoryEvent.java                 |             10 |            10 |           0 |      0 |           0 |           0 |            0 | catalog-dao/src/main/java/org/openecomp/sdc/be/resources/data/auditing/CategoryEvent.java                 |
| CompositionBusinessLogic.java      |             10 |             0 |           0 |      0 |           0 |           0 |           10 | catalog-be/src/main/java/org/openecomp/sdc/be/components/impl/CompositionBusinessLogic.java               |
| AuditingGetUebClusterEvent.java    |             10 |            10 |           0 |      0 |           0 |           0 |            0 | catalog-dao/src/main/java/org/openecomp/sdc/be/resources/data/auditing/AuditingGetUebClusterEvent.java    |
| UserAdminEvent.java                |             10 |            10 |           0 |      0 |           0 |           0 |            0 | catalog-dao/src/main/java/org/openecomp/sdc/be/resources/data/auditing/UserAdminEvent.java                |
| DistributionStatusEvent.java       |             10 |            10 |           0 |      0 |           0 |           0 |            0 | catalog-dao/src/main/java/org/openecomp/sdc/be/resources/data/auditing/DistributionStatusEvent.java       |

