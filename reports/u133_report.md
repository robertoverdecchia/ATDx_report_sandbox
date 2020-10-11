
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="./plots/onap_clamp.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/clamp) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_clamp) <br> [Complete issue report (JSON)](./json/onap_clamp.json)</p>|<img src="./plots/onap_sdc-sdc-workflow-designer.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/sdc-sdc-workflow-designer) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdc-sdc-workflow-designer) <br> [Complete issue report (JSON)](./json/onap_sdc-sdc-workflow-designer.json)</p>|<img src="./plots/onap_sdc.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/sdc) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_sdc) <br> [Complete issue report (JSON)](./json/onap_sdc.json)</p>
 | |

# Project report summaries
## Project: _onap/clamp_
|./plots/onap_clamp.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/clamp) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_clamp) <br> [Complete issue report (JSON)](./json/onap_clamp.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                           |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| src/main/java/org/onap/clamp/clds/tosca/ToscaYamlToJsonConvertor.java               |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/onap/clamp/clds/util/XmlTools.java                                |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| src/main/java/org/onap/clamp/util/PassDecoder.java                                  |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/onap/clamp/clds/util/drawing/SvgLoopGenerator.java                |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/onap/clamp/clds/model/dcae/DcaeInventoryResponse.java             |             1 |           0 |         0 |           0 |           0 |            0 |     1 |
| src/main/java/org/onap/clamp/authorization/SecureServicePermissionDeserializer.java |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| src/main/java/org/onap/clamp/util/SemanticVersioning.java                           |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/onap/clamp/loop/deploy/DcaeDeployParameters.java                  |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/onap/clamp/loop/CsarInstaller.java                                |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| src/main/java/org/onap/clamp/clds/tosca/update/execution/ToscaMetadataProcess.java  |             0 |           0 |         0 |           1 |           0 |            0 |     1 |

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

