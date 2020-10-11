
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_so-libs.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/so-libs) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_so-libs) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_so-libs.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_so.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/so) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_so) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_so.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_usecase-ui-server.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/usecase-ui-server) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_usecase-ui-server) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_usecase-ui-server.json)</p>
 | |

# Project report summaries
## Project: _onap/so-libs_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_so-libs.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/so-libs) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_so-libs) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_so-libs.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                      |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                             |
|:--------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------------------------------------------------------|
| Network.java                    |              6 |             0 |           0 |      0 |           6 |           0 |            0 | quantum-model/src/main/java/com/woorea/openstack/quantum/model/Network.java                                      |
| SecurityGroupsExtension.java    |              5 |             0 |           0 |      0 |           5 |           0 |            0 | nova-client/src/main/java/com/woorea/openstack/nova/api/extensions/SecurityGroupsExtension.java                  |
| SecurityGroupRuleForCreate.java |              4 |             0 |           0 |      0 |           4 |           0 |            0 | nova-model/src/main/java/com/woorea/openstack/nova/model/SecurityGroupRuleForCreate.java                         |
| SubnetForCreate.java            |              3 |             0 |           0 |      0 |           3 |           0 |            0 | quantum-model/src/main/java/com/woorea/openstack/quantum/model/SubnetForCreate.java                              |
| AbsOpenStackCmd.java            |              1 |             0 |           1 |      0 |           0 |           0 |            0 | quantum-client/src/main/java/com/woorea/openstack/quantum/api/query/AbsOpenStackCmd.java                         |
| KeystoneUtils.java              |              1 |             0 |           1 |      0 |           0 |           0 |            0 | keystone-client/src/main/java/com/woorea/openstack/keystone/utils/KeystoneUtils.java                             |
| HttpClientConnector.java        |              1 |             0 |           1 |      0 |           0 |           0 |            0 | openstack-client-connectors/http-connector/src/main/java/com/woorea/openstack/connector/HttpClientConnector.java |
| PortForCreate.java              |              1 |             0 |           0 |      0 |           1 |           0 |            0 | quantum-model/src/main/java/com/woorea/openstack/quantum/model/PortForCreate.java                                |
| NetworkForCreate.java           |              1 |             0 |           0 |      0 |           1 |           0 |            0 | quantum-model/src/main/java/com/woorea/openstack/quantum/model/NetworkForCreate.java                             |

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
| CommonConstant.java                |              2 |             0 |           0 |      0 |           2 |           0 |            0 | server/src/main/java/org/onap/usecaseui/server/constant/CommonConstant.java                         |
| Constant.java                      |              2 |             0 |           0 |      0 |           2 |           0 |            0 | server/src/main/java/org/onap/usecaseui/server/constant/Constant.java                               |
| SotnServiceLcmController.java      |              2 |             0 |           2 |      0 |           0 |           0 |            0 | server/src/main/java/org/onap/usecaseui/server/controller/lcm/SotnServiceLcmController.java         |
| UuiServerApplication.java          |              1 |             0 |           0 |      0 |           1 |           0 |            0 | server/src/main/java/org/onap/usecaseui/server/UuiServerApplication.java                            |
| AlarmsHeader.java                  |              1 |             0 |           0 |      0 |           1 |           0 |            0 | server/src/main/java/org/onap/usecaseui/server/bean/AlarmsHeader.java                               |
| ServiceTemplateInput.java          |              1 |             0 |           0 |      0 |           1 |           0 |            0 | server/src/main/java/org/onap/usecaseui/server/bean/lcm/ServiceTemplateInput.java                   |

