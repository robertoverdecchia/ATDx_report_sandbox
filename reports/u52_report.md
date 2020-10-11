
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-collectors-restconf.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-collectors-restconf) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-collectors-restconf) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dcaegen2-collectors-restconf.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-services-mapper.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-services-mapper) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-services-mapper) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dcaegen2-services-mapper.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_so.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/so) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_so) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_so.json)</p>
 | |
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_usecase-ui-server.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/usecase-ui-server) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_usecase-ui-server) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_usecase-ui-server.json)</p>
# Project report summaries
## Project: _onap/dcaegen2-collectors-restconf_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-collectors-restconf.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-collectors-restconf) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-collectors-restconf) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dcaegen2-collectors-restconf.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name               |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                        |
|:-------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:------------------------------------------------------------|
| Parameters.java          |             27 |             0 |           0 |      0 |          27 |           0 |            0 | src/main/java/org/onap/dcae/common/Parameters.java          |
| RestapiCallNode.java     |              7 |             0 |           7 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dcae/common/RestapiCallNode.java     |
| HttpResponse.java        |              4 |             0 |           0 |      0 |           4 |           0 |            0 | src/main/java/org/onap/dcae/common/HttpResponse.java        |
| RestapiCallNodeUtil.java |              4 |             0 |           4 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dcae/common/RestapiCallNodeUtil.java |

## Project: _onap/dcaegen2-services-mapper_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_dcaegen2-services-mapper.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/dcaegen2-services-mapper) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_dcaegen2-services-mapper) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_dcaegen2-services-mapper.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                                                  |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:-----------------------------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| UniversalVesAdapter/src/main/java/org/onap/universalvesadapter/adapter/GenericAdapter.java                 |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| UniversalVesAdapter/src/main/java/org/onap/universalvesadapter/dmaap/BaseDMaaPMRComponent.java             |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| UniversalVesAdapter/src/main/java/org/onap/universalvesadapter/adapter/UniversalEventAdapter.java          |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| UniversalVesAdapter/src/main/java/org/onap/universalvesadapter/utils/SmooksUtils.java                      |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| UniversalVesAdapter/src/main/java/org/onap/universalvesadapter/configs/DMaaPMRSubscriberConfig.java        |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| UniversalVesAdapter/src/main/java/org/onap/universalvesadapter/configs/DMaaPMRPublisherConfig.java         |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| UniversalVesAdapter/src/main/java/org/onap/universalvesadapter/dmaap/MRPublisher/DMaaPMRPublisherImpl.java |             0 |           0 |         0 |           1 |           0 |            0 |     1 |

## Project: _onap/so_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_so.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/so) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_so) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_so.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                          |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                       |
|:------------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------------------------------------------------|
| BBInputSetup.java                   |             20 |             0 |          16 |      0 |           4 |           0 |            0 | bpmn/MSOCommonBPMN/src/main/java/org/onap/so/bpmn/servicedecomposition/tasks/BBInputSetup.java             |
| NetworkAdapterResources.java        |             12 |             0 |          10 |      0 |           2 |           0 |            0 | bpmn/so-bpmn-tasks/src/main/java/org/onap/so/client/orchestration/NetworkAdapterResources.java             |
| ResourceModelInfo.java              |             12 |            12 |           0 |      0 |           0 |           0 |            0 | bpmn/so-bpmn-tasks/src/main/java/org/onap/so/client/oof/beans/ResourceModelInfo.java                       |
| MsoNetworkAdapterImpl.java          |             10 |             0 |           1 |      0 |           9 |           0 |            0 | adapters/mso-openstack-adapters/src/main/java/org/onap/so/adapters/network/MsoNetworkAdapterImpl.java      |
| BBInputSetupUtils.java              |             10 |             0 |          10 |      0 |           0 |           0 |            0 | bpmn/MSOCommonBPMN/src/main/java/org/onap/so/bpmn/servicedecomposition/tasks/BBInputSetupUtils.java        |
| WorkflowAction.java                 |              9 |             0 |           6 |      0 |           3 |           0 |            0 | bpmn/so-bpmn-tasks/src/main/java/org/onap/so/bpmn/infrastructure/workflow/tasks/WorkflowAction.java        |
| SDNCConfigurationResources.java     |              8 |             0 |           8 |      0 |           0 |           0 |            0 | bpmn/so-bpmn-tasks/src/main/java/org/onap/so/client/orchestration/SDNCConfigurationResources.java          |
| MsoNetworkAdapter.java              |              7 |             0 |           0 |      0 |           7 |           0 |            0 | adapters/mso-openstack-adapters/src/main/java/org/onap/so/adapters/network/MsoNetworkAdapter.java          |
| VnfAdapterVfModuleObjectMapper.java |              6 |             0 |           5 |      0 |           1 |           0 |            0 | bpmn/so-bpmn-tasks/src/main/java/org/onap/so/client/adapter/vnf/mapper/VnfAdapterVfModuleObjectMapper.java |
| AAIDeleteTasks.java                 |              6 |             0 |           6 |      0 |           0 |           0 |            0 | bpmn/so-bpmn-tasks/src/main/java/org/onap/so/bpmn/infrastructure/aai/tasks/AAIDeleteTasks.java             |

## Project: _onap/usecase-ui-server_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_usecase-ui-server.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/usecase-ui-server) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_usecase-ui-server) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_usecase-ui-server.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                         |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                |
|:-----------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------------------------------------------|
| ResourceMgtServiceConvert.java     |              5 |             0 |           5 |      0 |           0 |           0 |            0 | server/src/main/java/org/onap/usecaseui/server/service/nsmf/impl/ResourceMgtServiceConvert.java     |
| ResourceMonitorServiceConvert.java |              4 |             0 |           4 |      0 |           0 |           0 |            0 | server/src/main/java/org/onap/usecaseui/server/service/nsmf/impl/ResourceMonitorServiceConvert.java |
| SotnServiceTemplateService.java    |              4 |             0 |           4 |      0 |           0 |           0 |            0 | server/src/main/java/org/onap/usecaseui/server/service/lcm/SotnServiceTemplateService.java          |
| DateUtils.java                     |              3 |             0 |           2 |      0 |           1 |           0 |            0 | server/src/main/java/org/onap/usecaseui/server/util/DateUtils.java                                  |

