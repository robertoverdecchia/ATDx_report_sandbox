
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aaf-authz.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aaf-authz) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aaf-authz) <br> [Complete issue report (JSON)](./json/onap_aaf-authz.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-aai-common.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aai-aai-common) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-aai-common) <br> [Complete issue report (JSON)](./json/onap_aai-aai-common.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-esr-server.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aai-esr-server) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-esr-server) <br> [Complete issue report (JSON)](./json/onap_aai-esr-server.json)</p>
 | |
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-event-client.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aai-event-client) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-event-client) <br> [Complete issue report (JSON)](./json/onap_aai-event-client.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-sparky-be.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aai-sparky-be) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-sparky-be) <br> [Complete issue report (JSON)](./json/onap_aai-sparky-be.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_appc.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/appc) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_appc) <br> [Complete issue report (JSON)](./json/onap_appc.json)</p>
 | |
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_ccsdk-apps.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/ccsdk-apps) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_ccsdk-apps) <br> [Complete issue report (JSON)](./json/onap_ccsdk-apps.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_ccsdk-dashboard.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/ccsdk-dashboard) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_ccsdk-dashboard) <br> [Complete issue report (JSON)](./json/onap_ccsdk-dashboard.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_ccsdk-features.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/ccsdk-features) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_ccsdk-features) <br> [Complete issue report (JSON)](./json/onap_ccsdk-features.json)</p>

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

## Project: _onap/aai-event-client_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-event-client.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/aai-event-client) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-event-client) <br> [Complete issue report (JSON)](./json/onap_aai-event-client.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name               |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                |
|:-------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:------------------------------------------------------------------------------------|
| EventPublisher.java      |              9 |             0 |           9 |      0 |           0 |           0 |            0 | event-client-api/src/main/java/org/onap/aai/event/api/EventPublisher.java           |
| EventConsumer.java       |              6 |             0 |           6 |      0 |           0 |           0 |            0 | event-client-api/src/main/java/org/onap/aai/event/api/EventConsumer.java            |
| DMaaPEventPublisher.java |              3 |             0 |           1 |      0 |           2 |           0 |            0 | event-client-dmaap/src/main/java/org/onap/aai/event/client/DMaaPEventPublisher.java |
| DMaaPEventConsumer.java  |              3 |             0 |           0 |      0 |           3 |           0 |            0 | event-client-dmaap/src/main/java/org/onap/aai/event/client/DMaaPEventConsumer.java  |

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

## Project: _onap/ccsdk-apps_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_ccsdk-apps.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/ccsdk-apps) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_ccsdk-apps) <br> [Complete issue report (JSON)](./json/onap_ccsdk-apps.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                   |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                               |
|:-----------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------------------------|
| SpringService.java           |              5 |             0 |           5 |      0 |           0 |           0 |            0 | ms/neng/src/main/java/org/onap/ccsdk/apps/ms/neng/core/service/SpringService.java                  |
| PolicyFinderServiceImpl.java |              5 |             0 |           5 |      0 |           0 |           0 |            0 | ms/neng/src/main/java/org/onap/ccsdk/apps/ms/neng/service/extinf/impl/PolicyFinderServiceImpl.java |
| PropertyOperator.java        |              5 |             0 |           5 |      0 |           0 |           0 |            0 | ms/neng/src/main/java/org/onap/ccsdk/apps/ms/neng/core/policy/PropertyOperator.java                |
| SpringServiceImpl.java       |              5 |             0 |           5 |      0 |           0 |           0 |            0 | ms/neng/src/main/java/org/onap/ccsdk/apps/ms/neng/core/service/SpringServiceImpl.java              |
| VlantagApiService.java       |              4 |             0 |           4 |      0 |           0 |           0 |            0 | ms/vlantag-api/src/main/java/org/onap/ccsdk/apps/ms/vlantagapi/core/service/VlantagApiService.java |
| PolicyParameters.java        |              3 |             0 |           3 |      0 |           0 |           0 |            0 | ms/neng/src/main/java/org/onap/ccsdk/apps/ms/neng/core/policy/PolicyParameters.java                |

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

## Project: _onap/ccsdk-features_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_ccsdk-features.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/ccsdk-features) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_ccsdk-features) <br> [Complete issue report (JSON)](./json/onap_ccsdk-features.json)</p>
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
