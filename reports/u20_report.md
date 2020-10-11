
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aaf-authz.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aaf-authz) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aaf-authz) <br> [Complete issue report (JSON)](./json/onap_aaf-authz.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-esr-server.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aai-esr-server) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-esr-server) <br> [Complete issue report (JSON)](./json/onap_aai-esr-server.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_appc.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/appc) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_appc) <br> [Complete issue report (JSON)](./json/onap_appc.json)</p>
 | |
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-dbcapi.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-dbcapi) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-dbcapi) <br> [Complete issue report (JSON)](./json/onap_dmaap-dbcapi.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-messagerouter-messageservice.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-messagerouter-messageservice) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-messagerouter-messageservice) <br> [Complete issue report (JSON)](./json/onap_dmaap-messagerouter-messageservice.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_logging-analytics.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/logging-analytics) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_logging-analytics) <br> [Complete issue report (JSON)](./json/onap_logging-analytics.json)</p>
 | |
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_multicloud-framework-artifactbroker.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/multicloud-framework) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_multicloud-framework-artifactbroker) <br> [Complete issue report (JSON)](./json/onap_multicloud-framework-artifactbroker.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_portal.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/portal) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_portal) <br> [Complete issue report (JSON)](./json/onap_portal.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_sdc.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/sdc) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdc) <br> [Complete issue report (JSON)](./json/onap_sdc.json)</p>

# Project report summaries
## Project: _onap/aaf-authz_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aaf-authz.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/aaf-authz) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aaf-authz) <br> [Complete issue report (JSON)](./json/onap_aaf-authz.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name         |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                       |
|:-------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------|
| LocateDAO.java     |             13 |             0 |           2 |      0 |          11 |           0 |            0 | auth/auth-cass/src/main/java/org/onap/aaf/auth/dao/cass/LocateDAO.java     |
| OAuthTokenDAO.java |             12 |             0 |           0 |      0 |          12 |           0 |            0 | auth/auth-cass/src/main/java/org/onap/aaf/auth/dao/cass/OAuthTokenDAO.java |
| ArtiDAO.java       |             11 |             0 |           0 |      0 |          11 |           0 |            0 | auth/auth-cass/src/main/java/org/onap/aaf/auth/dao/cass/ArtiDAO.java       |
| Agent.java         |              9 |             0 |           9 |      0 |           0 |           0 |            0 | cadi/aaf/src/main/java/org/onap/aaf/cadi/configure/Agent.java              |
| InXML.java         |              9 |             0 |           1 |      0 |           8 |           0 |            0 | misc/rosetta/src/main/java/org/onap/aaf/misc/rosetta/InXML.java            |
| Cred.java          |              8 |             0 |           0 |      0 |           8 |           0 |            0 | auth/auth-batch/src/main/java/org/onap/aaf/auth/batch/helpers/Cred.java    |
| FutureDAO.java     |              8 |             0 |           0 |      0 |           8 |           0 |            0 | auth/auth-cass/src/main/java/org/onap/aaf/auth/dao/cass/FutureDAO.java     |
| HistoryDAO.java    |              8 |             0 |           0 |      0 |           8 |           0 |            0 | auth/auth-cass/src/main/java/org/onap/aaf/auth/dao/cass/HistoryDAO.java    |
| CredDAO.java       |              8 |             0 |           0 |      0 |           8 |           0 |            0 | auth/auth-cass/src/main/java/org/onap/aaf/auth/dao/cass/CredDAO.java       |
| AAF_CM.java        |              7 |             0 |           1 |      0 |           6 |           0 |            0 | auth/auth-certman/src/main/java/org/onap/aaf/auth/cm/AAF_CM.java           |

## Project: _onap/aai-esr-server_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-esr-server.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/aai-esr-server) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-esr-server) <br> [Complete issue report (JSON)](./json/onap_aai-esr-server.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                            |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:-------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| esr-mgr/src/main/java/org/onap/aai/esr/externalservice/aai/RelationshipProvider.java |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| esr-mgr/src/main/java/org/onap/aai/esr/externalservice/aai/EmsRegisterProvider.java  |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| esr-mgr/src/main/java/org/onap/aai/esr/externalservice/aai/VnfmRegisterProvider.java |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| esr-mgr/src/main/java/org/onap/aai/esr/externalservice/aai/PnfRegisterProvider.java  |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| esr-mgr/src/main/java/org/onap/aai/esr/externalservice/aai/VimRegisterProvider.java  |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| esr-mgr/src/main/java/org/onap/aai/esr/externalservice/aai/NfvoRegisterProvider.java |             0 |           1 |         0 |           0 |           0 |            0 |     1 |

## Project: _onap/appc_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_appc.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/appc) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_appc) <br> [Complete issue report (JSON)](./json/onap_appc.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                  |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                                               |
|:----------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------------------------------------------------------------------------|
| DGGeneralDBService.java     |             25 |             0 |          25 |      0 |           0 |           0 |            0 | appc-config/appc-data-services/provider/src/main/java/org/onap/appc/data/services/db/DGGeneralDBService.java                       |
| DesignDBService.java        |             19 |             0 |          19 |      0 |           0 |           0 |            0 | appc-inbound/appc-design-services/provider/src/main/java/org/onap/appc/design/dbervices/DesignDBService.java                       |
| RequestValidator.java       |             11 |             0 |          10 |      0 |           1 |           0 |            0 | appc-inbound/appc-interfaces-service/bundle/src/main/java/org/onap/appc/interfaces/service/executor/RequestValidator.java          |
| ConfigComponentAdaptor.java |              8 |             0 |           6 |      0 |           2 |           0 |            0 | appc-config/appc-config-adaptor/provider/src/main/java/org/onap/appc/ccadaptor/ConfigComponentAdaptor.java                         |
| FlowSequenceGenerator.java  |              7 |             0 |           7 |      0 |           0 |           0 |            0 | appc-config/appc-flow-controller/provider/src/main/java/org/onap/appc/flow/controller/node/FlowSequenceGenerator.java              |
| RequestFailedException.java |              7 |             0 |           7 |      0 |           0 |           0 |            0 | appc-adapters/appc-iaas-adapter/appc-iaas-adapter-bundle/src/main/java/org/onap/appc/adapter/iaas/impl/RequestFailedException.java |
| ArtificatTransformer.java   |              6 |             0 |           6 |      0 |           0 |           0 |            0 | appc-config/appc-config-params/provider/src/main/java/org/onap/sdnc/config/params/transformer/ArtificatTransformer.java            |
| ParseAdminArtifcat.java     |              6 |             0 |           6 |      0 |           0 |           0 |            0 | appc-config/appc-encryption-tool/provider/src/main/java/org/onap/appc/encryptiontool/fqdn/ParseAdminArtifcat.java                  |
| RequestFailedException.java |              5 |             0 |           5 |      0 |           0 |           0 |            0 | appc-adapters/appc-rest-adapter/appc-rest-adapter-bundle/src/main/java/org/onap/appc/adapter/rest/impl/RequestFailedException.java |
| ArtifactHandlerNode.java    |              5 |             0 |           5 |      0 |           0 |           0 |            0 | appc-inbound/appc-artifact-handler/provider/src/main/java/org/onap/appc/artifact/handler/node/ArtifactHandlerNode.java             |

## Project: _onap/dmaap-dbcapi_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-dbcapi.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-dbcapi) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-dbcapi) <br> [Complete issue report (JSON)](./json/onap_dmaap-dbcapi.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name          |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                             |
|:--------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------|
| DBFieldHandler.java |              7 |             0 |           7 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/dbcapi/database/DBFieldHandler.java |

## Project: _onap/dmaap-messagerouter-messageservice_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dmaap-messagerouter-messageservice.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/dmaap-messagerouter-messageservice) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dmaap-messagerouter-messageservice) <br> [Complete issue report (JSON)](./json/onap_dmaap-messagerouter-messageservice.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name         |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                    |
|:-------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:--------------------------------------------------------|
| MirrorMaker.java   |              5 |             0 |           0 |      0 |           5 |           0 |            0 | src/main/java/org/onap/dmaap/mmagent/MirrorMaker.java   |
| MMRestService.java |              4 |             0 |           4 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dmaap/service/MMRestService.java |

## Project: _onap/logging-analytics_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_logging-analytics.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/logging-analytics) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_logging-analytics) <br> [Complete issue report (JSON)](./json/onap_logging-analytics.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                         |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                                       |
|:-----------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------------------------------------------------|
| Constants.java                     |              4 |             0 |           0 |      0 |           4 |           0 |            0 | reference/logging-filter/logging-filter-base/src/main/java/org/onap/logging/filter/base/Constants.java                     |
| FilteredMetricLogClientFilter.java |              4 |             4 |           0 |      0 |           0 |           0 |            0 | reference/logging-filter/logging-filter-base/src/main/java/org/onap/logging/filter/base/FilteredMetricLogClientFilter.java |

## Project: _onap/multicloud-framework_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_multicloud-framework-artifactbroker.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/multicloud-framework) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_multicloud-framework-artifactbroker) <br> [Complete issue report (JSON)](./json/onap_multicloud-framework-artifactbroker.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                            |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:---------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| model/src/main/java/org/onap/policy/distribution/model/GsonUtil.java |             0 |           0 |         0 |           1 |           0 |            0 |     1 |

## Project: _onap/portal_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_portal.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/portal) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_portal) <br> [Complete issue report (JSON)](./json/onap_portal.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                         |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                         |
|:-----------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-------------------------------------------------------------------------------------------------------------|
| ExternalAccessRolesService.java    |             37 |             0 |          37 |      0 |           0 |           0 |            0 | ecomp-portal-BE-common/src/main/java/org/onap/portalapp/portal/service/ExternalAccessRolesService.java       |
| RolesController.java               |             28 |             0 |          28 |      0 |           0 |           0 |            0 | ecomp-portal-BE-common/src/main/java/org/onap/portalapp/portal/controller/RolesController.java               |
| UserRolesCommonServiceImpl.java    |             25 |             0 |          23 |      0 |           2 |           0 |            0 | ecomp-portal-BE-common/src/main/java/org/onap/portalapp/portal/service/UserRolesCommonServiceImpl.java       |
| OnboardingApp.java                 |             20 |             0 |           0 |      0 |          20 |           0 |            0 | ecomp-portal-BE-os/src/main/java/org/onap/portalapp/portal/transport/OnboardingApp.java                      |
| SharedContextRestController.java   |             12 |             0 |          12 |      0 |           0 |           0 |            0 | ecomp-portal-BE-common/src/main/java/org/onap/portalapp/portal/controller/SharedContextRestController.java   |
| RolesApprovalSystemController.java |              8 |             0 |           8 |      0 |           0 |           0 |            0 | ecomp-portal-BE-common/src/main/java/org/onap/portalapp/portal/controller/RolesApprovalSystemController.java |
| BasicAuthAccountService.java       |              7 |             0 |           7 |      0 |           0 |           0 |            0 | ecomp-portal-BE-common/src/main/java/org/onap/portalapp/portal/service/BasicAuthAccountService.java          |
| EPAppCommonServiceImpl.java        |              7 |             2 |           4 |      0 |           1 |           0 |            0 | ecomp-portal-BE-common/src/main/java/org/onap/portalapp/portal/service/EPAppCommonServiceImpl.java           |
| CommonSessionCookieUtil.java       |              6 |             0 |           2 |      0 |           4 |           0 |            0 | ecomp-portal-BE-common/src/main/java/org/onap/portalapp/util/CommonSessionCookieUtil.java                    |
| SchedulerController.java           |              6 |             0 |           5 |      0 |           0 |           1 |            0 | ecomp-portal-BE-common/src/main/java/org/onap/portalapp/portal/controller/SchedulerController.java           |

## Project: _onap/sdc_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_sdc.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/sdc) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdc) <br> [Complete issue report (JSON)](./json/onap_sdc.json)</p>
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
