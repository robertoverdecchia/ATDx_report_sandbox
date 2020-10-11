
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-aai-common.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aai-aai-common) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-aai-common) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_aai-aai-common.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-cacher.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aai-cacher) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-cacher) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_aai-cacher.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-data-router.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aai-data-router) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-data-router) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_aai-data-router.json)</p>
 | |
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-event-client.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aai-event-client) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-event-client) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_aai-event-client.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-graphadmin.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aai-graphadmin) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-graphadmin) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_aai-graphadmin.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-resources.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aai-resources) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-resources) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_aai-resources.json)</p>
 | |
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-router-core.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aai-router-core) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-router-core) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_aai-router-core.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-schema-service.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aai-schema-service) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-schema-service) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_aai-schema-service.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-search-data-service.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aai-search-data-service) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-search-data-service) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_aai-search-data-service.json)</p>

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

## Project: _onap/aai-cacher_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-cacher.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/aai-cacher) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-cacher) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_aai-cacher.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                  |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                         |
|:----------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------------------|
| CacheKey.java               |             12 |             0 |           0 |      0 |          12 |           0 |            0 | src/main/java/org/onap/aai/cacher/model/CacheKey.java                        |
| RestClient.java             |              3 |             0 |           3 |      0 |           0 |           0 |            0 | src/main/java/org/onap/aai/cacher/util/RestClient.java                       |
| AuthorizationService.java   |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/onap/aai/cacher/service/AuthorizationService.java          |
| ScheduledTaskConfig.java    |              2 |             0 |           0 |      0 |           1 |           1 |            0 | src/main/java/org/onap/aai/cacher/service/tasks/ScheduledTaskConfig.java     |
| JerseyConfiguration.java    |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/onap/aai/cacher/web/JerseyConfiguration.java               |
| AAIParentEventConsumer.java |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/onap/aai/cacher/dmaap/consumer/AAIParentEventConsumer.java |

## Project: _onap/aai-data-router_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-data-router.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/aai-data-router) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-data-router) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_aai-data-router.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                             |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                |
|:---------------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:------------------------------------------------------------------------------------|
| AbstractSpikeEntityEventProcessor.java |              6 |             0 |           5 |      0 |           1 |           0 |            0 | src/main/java/org/onap/aai/datarouter/policy/AbstractSpikeEntityEventProcessor.java |
| AaiUiSvcPolicyUtil.java                |              5 |             0 |           4 |      0 |           1 |           0 |            0 | src/main/java/org/onap/aai/datarouter/util/AaiUiSvcPolicyUtil.java                  |
| POAAuditException.java                 |              3 |             0 |           3 |      0 |           0 |           0 |            0 | src/main/java/org/onap/aai/datarouter/exception/POAAuditException.java              |
| SearchServiceAgent.java                |              3 |             0 |           3 |      0 |           0 |           0 |            0 | src/main/java/org/onap/aai/datarouter/util/SearchServiceAgent.java                  |
| ChameleonErrorProcessor.java           |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/onap/aai/datarouter/query/ChameleonErrorProcessor.java            |
| GapEventTransformer.java               |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/onap/aai/datarouter/policy/GapEventTransformer.java               |
| EntityEventPolicy.java                 |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/onap/aai/datarouter/policy/EntityEventPolicy.java                 |
| SpikeEntityEventPolicy.java            |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/onap/aai/datarouter/policy/SpikeEntityEventPolicy.java            |
| AuditService.java                      |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/onap/aai/datarouter/service/AuditService.java                     |

## Project: _onap/aai-event-client_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-event-client.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/aai-event-client) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-event-client) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_aai-event-client.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name               |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                |
|:-------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:------------------------------------------------------------------------------------|
| EventPublisher.java      |              9 |             0 |           9 |      0 |           0 |           0 |            0 | event-client-api/src/main/java/org/onap/aai/event/api/EventPublisher.java           |
| EventConsumer.java       |              6 |             0 |           6 |      0 |           0 |           0 |            0 | event-client-api/src/main/java/org/onap/aai/event/api/EventConsumer.java            |
| DMaaPEventPublisher.java |              3 |             0 |           1 |      0 |           2 |           0 |            0 | event-client-dmaap/src/main/java/org/onap/aai/event/client/DMaaPEventPublisher.java |
| DMaaPEventConsumer.java  |              3 |             0 |           0 |      0 |           3 |           0 |            0 | event-client-dmaap/src/main/java/org/onap/aai/event/client/DMaaPEventConsumer.java  |
| RabbitMqUtils.java       |              2 |             0 |           1 |      0 |           1 |           0 |            0 | event-client-rabbitmq/src/main/java/org/onap/aai/event/client/RabbitMqUtils.java    |

## Project: _onap/aai-graphadmin_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-graphadmin.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/aai-graphadmin) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-graphadmin) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_aai-graphadmin.json)</p>
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

## Project: _onap/aai-router-core_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-router-core.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/aai-router-core) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-router-core) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_aai-router-core.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                        |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                |
|:----------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:--------------------------------------------------------------------|
| SchemaIngestPropertiesReader.java |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/onap/aai/schema/SchemaIngestPropertiesReader.java |

## Project: _onap/aai-schema-service_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-schema-service.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/aai-schema-service) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-schema-service) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_aai-schema-service.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                          |
|:--------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------------------------------------|
| XSDElement.java           |             24 |             0 |          24 |      0 |           0 |           0 |            0 | aai-schema-gen/src/main/java/org/onap/aai/schemagen/genxsd/XSDElement.java                    |
| NodesYAMLfromOXM.java     |             11 |             8 |           2 |      0 |           1 |           0 |            0 | aai-schema-gen/src/main/java/org/onap/aai/schemagen/genxsd/NodesYAMLfromOXM.java              |
| YAMLfromOXM.java          |             11 |             8 |           2 |      0 |           1 |           0 |            0 | aai-schema-gen/src/main/java/org/onap/aai/schemagen/genxsd/YAMLfromOXM.java                   |
| HTMLfromOXM.java          |              4 |             3 |           1 |      0 |           0 |           0 |            0 | aai-schema-gen/src/main/java/org/onap/aai/schemagen/genxsd/HTMLfromOXM.java                   |
| GenerateSwagger.java      |              2 |             0 |           1 |      0 |           1 |           0 |            0 | aai-schema-gen/src/main/java/org/onap/aai/schemagen/swagger/GenerateSwagger.java              |
| SchemaServiceApp.java     |              2 |             0 |           2 |      0 |           0 |           0 |            0 | aai-schema-service/src/main/java/org/onap/aai/schemaservice/SchemaServiceApp.java             |
| AuthorizationService.java |              2 |             0 |           2 |      0 |           0 |           0 |            0 | aai-schema-service/src/main/java/org/onap/aai/schemaservice/service/AuthorizationService.java |
| GenerateXsd.java          |              2 |             0 |           1 |      0 |           1 |           0 |            0 | aai-schema-gen/src/main/java/org/onap/aai/schemagen/GenerateXsd.java                          |
| OxmFileProcessor.java     |              2 |             0 |           2 |      0 |           0 |           0 |            0 | aai-schema-gen/src/main/java/org/onap/aai/schemagen/genxsd/OxmFileProcessor.java              |

## Project: _onap/aai-search-data-service_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aai-search-data-service.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/aai-search-data-service) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aai-search-data-service) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_aai-search-data-service.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name       |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                   |
|:-----------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------------|
| Application.java |              1 |             0 |           1 |      0 |           0 |           0 |            0 | search-data-service-app/src/main/java/org/onap/aai/sa/Application.java |

