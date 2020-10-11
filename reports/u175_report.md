
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
|||
|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aaf-authz.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/aaf-authz) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aaf-authz) <br> [Complete issue report (JSON)](./json/onap_aaf-authz.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_so.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/so) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_so) <br> [Complete issue report (JSON)](./json/onap_so.json)</p>
# Project report summaries
## Project: _onap/aaf-authz_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_aaf-authz.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/aaf-authz) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_aaf-authz) <br> [Complete issue report (JSON)](./json/onap_aaf-authz.json)</p>
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

## Project: _onap/so_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_so.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/so) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_so) <br> [Complete issue report (JSON)](./json/onap_so.json)</p>
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

