
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_sdc-dcae-d-dt-be-main.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/sdc-dcae-d-dt-be-main) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdc-dcae-d-dt-be-main) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_sdc-dcae-d-dt-be-main.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_sdc-sdc-workflow-designer.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/sdc-sdc-workflow-designer) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdc-sdc-workflow-designer) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_sdc-sdc-workflow-designer.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_sdc.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/sdc) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdc) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_sdc.json)</p>
 | |

# Project report summaries
## Project: _onap/sdc-dcae-d-dt-be-main_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_sdc-dcae-d-dt-be-main.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/sdc-dcae-d-dt-be-main) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdc-dcae-d-dt-be-main) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_sdc-dcae-d-dt-be-main.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                           |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                            |
|:-------------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:------------------------------------------------------------------------------------------------|
| ServiceBusinessLogic.java            |              2 |             0 |           2 |      0 |           0 |           0 |            0 | dcaedt_be/src/main/java/org/onap/sdc/dcae/composition/impl/ServiceBusinessLogic.java            |
| CompositionEngine.java               |              2 |             0 |           2 |      0 |           0 |           0 |            0 | dcaedt_be/src/main/java/org/onap/sdc/dcae/composition/CompositionEngine.java                    |
| PolicyException.java                 |              1 |             0 |           1 |      0 |           0 |           0 |            0 | dcaedt_catalog/asdc/src/main/java/org/onap/sdc/dcae/errormng/PolicyException.java               |
| ServiceException.java                |              1 |             0 |           1 |      0 |           0 |           0 |            0 | dcaedt_catalog/asdc/src/main/java/org/onap/sdc/dcae/errormng/ServiceException.java              |
| Normalizers.java                     |              1 |             0 |           0 |      0 |           1 |           0 |            0 | dcaedt_catalog/asdc/src/main/java/org/onap/sdc/dcae/utils/Normalizers.java                      |
| ActionTranslator.java                |              1 |             0 |           0 |      0 |           1 |           0 |            0 | dcaedt_be/src/main/java/org/onap/sdc/dcae/rule/editor/translators/ActionTranslator.java         |
| AbstractSdncException.java           |              1 |             0 |           1 |      0 |           0 |           0 |            0 | dcaedt_catalog/asdc/src/main/java/org/onap/sdc/dcae/errormng/AbstractSdncException.java         |
| VfcmtBusinessLogic.java              |              1 |             0 |           1 |      0 |           0 |           0 |            0 | dcaedt_be/src/main/java/org/onap/sdc/dcae/composition/impl/VfcmtBusinessLogic.java              |
| BlueprintController.java             |              1 |             0 |           0 |      0 |           1 |           0 |            0 | dcaedt_be/src/main/java/org/onap/sdc/dcae/composition/controller/BlueprintController.java       |
| CompositionCatalogBusinessLogic.java |              1 |             0 |           1 |      0 |           0 |           0 |            0 | dcaedt_be/src/main/java/org/onap/sdc/dcae/composition/impl/CompositionCatalogBusinessLogic.java |

## Project: _onap/sdc-sdc-workflow-designer_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_sdc-sdc-workflow-designer.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/sdc-sdc-workflow-designer) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdc-sdc-workflow-designer) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_sdc-sdc-workflow-designer.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                       |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                         |
|:---------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-------------------------------------------------------------------------------------------------------------|
| JsonUtil.java                    |              2 |             0 |           2 |      0 |           0 |           0 |            0 | sdc-workflow-designer-be/src/main/java/org/onap/sdc/workflow/services/utilities/JsonUtil.java                |
| ArtifactAssociationService.java  |              1 |             0 |           0 |      0 |           1 |           0 |            0 | sdc-workflow-designer-be/src/main/java/org/onap/sdc/workflow/api/ArtifactAssociationService.java             |
| WorkflowValidationConstants.java |              1 |             0 |           0 |      0 |           1 |           0 |            0 | sdc-workflow-designer-be/src/main/java/org/onap/sdc/workflow/services/types/WorkflowValidationConstants.java |

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

