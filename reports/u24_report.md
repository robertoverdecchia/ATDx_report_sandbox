
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="./plots/onap_sdc-dcae-d-ci.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/sdc-dcae-d-ci) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdc-dcae-d-ci) <br> [Complete issue report (JSON)](./json/onap_sdc-dcae-d-ci.json)</p>|<img src="./plots/onap_sdc-dcae-d-dt-be-main.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/sdc-dcae-d-dt-be-main) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdc-dcae-d-dt-be-main) <br> [Complete issue report (JSON)](./json/onap_sdc-dcae-d-dt-be-main.json)</p>|<img src="./plots/onap_sdc-dcae-d-dt-be-property.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/sdc-dcae-d-dt-be-property) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdc-dcae-d-dt-be-property) <br> [Complete issue report (JSON)](./json/onap_sdc-dcae-d-dt-be-property.json)</p>
 | |
|<img src="./plots/onap_sdc-sdc-be-common.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/sdc-sdc-be-common) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdc-sdc-be-common) <br> [Complete issue report (JSON)](./json/onap_sdc-sdc-be-common.json)</p>|<img src="./plots/onap_sdc-sdc-distribution-client.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/sdc-sdc-distribution-client) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdc-sdc-distribution-client) <br> [Complete issue report (JSON)](./json/onap_sdc-sdc-distribution-client.json)</p>|<img src="./plots/onap_sdc-sdc-tosca.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/sdc-sdc-tosca) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdc-sdc-tosca) <br> [Complete issue report (JSON)](./json/onap_sdc-sdc-tosca.json)</p>
 | |
|<img src="./plots/onap_sdc-sdc-workflow-designer.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/sdc-sdc-workflow-designer) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdc-sdc-workflow-designer) <br> [Complete issue report (JSON)](./json/onap_sdc-sdc-workflow-designer.json)</p>|<img src="./plots/onap_sdc.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/sdc) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdc) <br> [Complete issue report (JSON)](./json/onap_sdc.json)</p>
# Project report summaries
## Project: _onap/sdc-dcae-d-ci_
|./plots/onap_sdc-dcae-d-ci.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/sdc-dcae-d-ci) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdc-dcae-d-ci) <br> [Complete issue report (JSON)](./json/onap_sdc-dcae-d-ci.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                      |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                       |
|:--------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-------------------------------------------------------------------------------------------|
| RuleEditorControllerTest.java   |              8 |             0 |           8 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dcae/ci/api/tests/ruleEditor/RuleEditorControllerTest.java          |
| PostAttachment.java             |              7 |             0 |           7 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dcae/ci/api/tests/services/attachment/PostAttachment.java           |
| PutCheckout.java                |              7 |             0 |           7 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dcae/ci/api/tests/lifeCycle/PutCheckout.java                        |
| PutCheckin.java                 |              7 |             0 |           7 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dcae/ci/api/tests/lifeCycle/PutCheckin.java                         |
| DcaeEntityClient.java           |              6 |             0 |           6 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dcae/ci/utilities/DcaeEntityClient.java                             |
| DcaeUtil.java                   |              5 |             0 |           2 |      0 |           3 |           0 |            0 | src/main/java/org/onap/dcae/ci/utilities/DcaeUtil.java                                     |
| CreateMonitoringComponent.java  |              4 |             0 |           4 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dcae/ci/api/tests/vfcmt/CreateMonitoringComponent.java              |
| GetServiceInstancePositive.java |              3 |             0 |           3 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dcae/ci/api/tests/services/instance/GetServiceInstancePositive.java |
| GetDefinitionTest.java          |              3 |             0 |           3 |      0 |           0 |           0 |            0 | src/main/java/org/onap/dcae/ci/api/tests/ruleEditor/GetDefinitionTest.java                 |

## Project: _onap/sdc-dcae-d-dt-be-main_
|./plots/onap_sdc-dcae-d-dt-be-main.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/sdc-dcae-d-dt-be-main) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdc-dcae-d-dt-be-main) <br> [Complete issue report (JSON)](./json/onap_sdc-dcae-d-dt-be-main.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                                       |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:------------------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| dcaedt_catalog/asdc/src/main/java/org/onap/sdc/dcae/errormng/PolicyException.java               |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| dcaedt_catalog/asdc/src/main/java/org/onap/sdc/dcae/errormng/ServiceException.java              |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| dcaedt_catalog/asdc/src/main/java/org/onap/sdc/dcae/utils/Normalizers.java                      |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| dcaedt_be/src/main/java/org/onap/sdc/dcae/rule/editor/translators/ActionTranslator.java         |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| dcaedt_catalog/asdc/src/main/java/org/onap/sdc/dcae/errormng/AbstractSdncException.java         |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| dcaedt_be/src/main/java/org/onap/sdc/dcae/composition/impl/VfcmtBusinessLogic.java              |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| dcaedt_be/src/main/java/org/onap/sdc/dcae/composition/controller/BlueprintController.java       |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| dcaedt_be/src/main/java/org/onap/sdc/dcae/composition/impl/CompositionCatalogBusinessLogic.java |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| dcaedt_be/src/main/java/org/onap/sdc/dcae/composition/controller/ServicesController.java        |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| dcaedt_be/src/main/java/org/onap/sdc/dcae/ves/VesJsonDeserializer.java                          |             0 |           1 |         0 |           0 |           0 |            0 |     1 |

## Project: _onap/sdc-dcae-d-dt-be-property_
|./plots/onap_sdc-dcae-d-dt-be-property.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/sdc-dcae-d-dt-be-property) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdc-dcae-d-dt-be-property) <br> [Complete issue report (JSON)](./json/onap_sdc-dcae-d-dt-be-property.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                  |
|:--------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------------|
| OnapLogConfiguration.java |             28 |             0 |           0 |      0 |          28 |           0 |            0 | src/main/java/org/onap/sdc/common/onaplog/OnapLogConfiguration.java   |
| DcaeBeConstants.java      |              3 |             0 |           0 |      0 |           3 |           0 |            0 | src/main/java/org/onap/sdc/dcae/composition/util/DcaeBeConstants.java |

## Project: _onap/sdc-sdc-be-common_
|./plots/onap_sdc-sdc-be-common.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/sdc-sdc-be-common) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdc-sdc-be-common) <br> [Complete issue report (JSON)](./json/onap_sdc-sdc-be-common.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name   |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                               |
|:-------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------------------------|
| Logger.java  |             21 |             0 |           0 |      0 |          21 |           0 |            0 | security-util-lib/src/main/java/org/onap/sdc/security/logging/wrappers/Logger.java |

## Project: _onap/sdc-sdc-distribution-client_
|./plots/onap_sdc-sdc-distribution-client.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/sdc-sdc-distribution-client) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdc-sdc-distribution-client) <br> [Complete issue report (JSON)](./json/onap_sdc-sdc-distribution-client.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                                             |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:------------------------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| sdc-distribution-client/src/main/java/org/onap/sdc/api/results/IDistributionClientDownloadResult.java |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| sdc-distribution-client/src/main/java/org/onap/sdc/api/IDistributionClient.java                       |             0 |           0 |         0 |           1 |           0 |            0 |     1 |

## Project: _onap/sdc-sdc-tosca_
|./plots/onap_sdc-sdc-tosca.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/sdc-sdc-tosca) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdc-sdc-tosca) <br> [Complete issue report (JSON)](./json/onap_sdc-sdc-tosca.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name             |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                              |
|:-----------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------------------------|
| ISdcCsarHelper.java    |             45 |             0 |           0 |      0 |          45 |           0 |            0 | sdc-tosca/src/main/java/org/onap/sdc/tosca/parser/api/ISdcCsarHelper.java         |
| CapabilityTypeDef.java |              4 |             4 |           0 |      0 |           0 |           0 |            0 | jtosca/src/main/java/org/onap/sdc/toscaparser/api/elements/CapabilityTypeDef.java |
| TOSCAException.java    |              3 |             0 |           3 |      0 |           0 |           0 |            0 | jtosca/src/main/java/org/onap/sdc/toscaparser/api/common/TOSCAException.java      |

## Project: _onap/sdc-sdc-workflow-designer_
|./plots/onap_sdc-sdc-workflow-designer.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/sdc-sdc-workflow-designer) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdc-sdc-workflow-designer) <br> [Complete issue report (JSON)](./json/onap_sdc-sdc-workflow-designer.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                                                    |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:-------------------------------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| sdc-workflow-designer-be/src/main/java/org/onap/sdc/workflow/api/ArtifactAssociationService.java             |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| sdc-workflow-designer-be/src/main/java/org/onap/sdc/workflow/services/types/WorkflowValidationConstants.java |             0 |           0 |         0 |           1 |           0 |            0 |     1 |

## Project: _onap/sdc_
|./plots/onap_sdc.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/sdc) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdc) <br> [Complete issue report (JSON)](./json/onap_sdc.json)</p>
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

