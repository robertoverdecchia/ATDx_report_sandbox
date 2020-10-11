
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_policy-apex-pdp.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/policy-apex-pdp) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_policy-apex-pdp) <br> [Complete issue report (JSON)](./json/onap_policy-apex-pdp.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_policy-drools-applications.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/policy-drools-applications) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_policy-drools-applications) <br> [Complete issue report (JSON)](./json/onap_policy-drools-applications.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_policy-drools-pdp.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/policy-drools-pdp) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_policy-drools-pdp) <br> [Complete issue report (JSON)](./json/onap_policy-drools-pdp.json)</p>
 | |
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_policy-engine.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/policy-engine) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_policy-engine) <br> [Complete issue report (JSON)](./json/onap_policy-engine.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_policy-models.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/policy-models) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_policy-models) <br> [Complete issue report (JSON)](./json/onap_policy-models.json)</p>
# Project report summaries
## Project: _onap/policy-apex-pdp_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_policy-apex-pdp.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/policy-apex-pdp) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_policy-apex-pdp) <br> [Complete issue report (JSON)](./json/onap_policy-apex-pdp.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name         |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                 |
|:-------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-------------------------------------------------------------------------------------|
| ApexEditorApi.java |              3 |             0 |           0 |      0 |           3 |           0 |            0 | model/model-api/src/main/java/org/onap/policy/apex/model/modelapi/ApexEditorApi.java |

## Project: _onap/policy-drools-applications_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_policy-drools-applications.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/policy-drools-applications) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_policy-drools-applications) <br> [Complete issue report (JSON)](./json/onap_policy-drools-applications.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                                   |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:--------------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| controlloop/m2/base/src/main/java/org/onap/policy/m2/base/Util.java                         |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| controlloop/m2/util/src/main/java/org/onap/policy/util/DroolsSessionCommonSerializable.java |             1 |           0 |         0 |           0 |           0 |            0 |     1 |

## Project: _onap/policy-drools-pdp_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_policy-drools-pdp.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/policy-drools-pdp) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_policy-drools-pdp) <br> [Complete issue report (JSON)](./json/onap_policy-drools-pdp.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                     |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                     |
|:-------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------------------------------|
| Bucket.java                    |              9 |             2 |           1 |      0 |           0 |           0 |            6 | feature-server-pool/src/main/java/org/onap/policy/drools/serverpool/Bucket.java                          |
| Server.java                    |              7 |             1 |           4 |      0 |           0 |           0 |            2 | feature-server-pool/src/main/java/org/onap/policy/drools/serverpool/Server.java                          |
| TargetLock.java                |              7 |             0 |           1 |      0 |           0 |           0 |            6 | feature-server-pool/src/main/java/org/onap/policy/drools/serverpool/TargetLock.java                      |
| Leader.java                    |              4 |             1 |           0 |      0 |           1 |           0 |            2 | feature-server-pool/src/main/java/org/onap/policy/drools/serverpool/Leader.java                          |
| StateManagementFeatureApi.java |              4 |             0 |           4 |      0 |           0 |           0 |            0 | api-state-management/src/main/java/org/onap/policy/drools/statemanagement/StateManagementFeatureApi.java |

## Project: _onap/policy-engine_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_policy-engine.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/policy-engine) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_policy-engine) <br> [Complete issue report (JSON)](./json/onap_policy-engine.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                          |
|:--------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------------------------------------|
| PolicyEngine.java         |             21 |             0 |           0 |      0 |          21 |           0 |            0 | PolicyEngineAPI/src/main/java/org/onap/policy/api/PolicyEngine.java                           |
| ElkConnector.java         |              7 |             0 |           7 |      0 |           0 |           0 |            0 | ONAP-PAP-REST/src/main/java/org/onap/policy/pap/xacml/rest/elk/client/ElkConnector.java       |
| ElkConnectorImpl.java     |              7 |             0 |           7 |      0 |           0 |           0 |            0 | ONAP-PAP-REST/src/main/java/org/onap/policy/pap/xacml/rest/elk/client/ElkConnectorImpl.java   |
| PolicyEngineServices.java |              5 |             0 |           0 |      0 |           5 |           0 |            0 | ONAP-PDP-REST/src/main/java/org/onap/policy/pdp/rest/api/controller/PolicyEngineServices.java |
| SavePolicyHandler.java    |              4 |             0 |           4 |      0 |           0 |           0 |            0 | ONAP-PAP-REST/src/main/java/org/onap/policy/pap/xacml/rest/handler/SavePolicyHandler.java     |
| PolicyApiUtils.java       |              4 |             0 |           3 |      0 |           1 |           0 |            0 | ONAP-PDP-REST/src/main/java/org/onap/policy/pdp/rest/api/utils/PolicyApiUtils.java            |
| StdPolicyEngine.java      |              4 |             0 |           0 |      0 |           4 |           0 |            0 | PolicyEngineAPI/src/main/java/org/onap/policy/std/StdPolicyEngine.java                        |
| StdEngine.java            |              3 |             0 |           0 |      0 |           1 |           0 |            2 | ONAP-XACML/src/main/java/org/onap/policy/xacml/std/pap/StdEngine.java                         |

## Project: _onap/policy-models_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_policy-models.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/policy-models) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_policy-models) <br> [Complete issue report (JSON)](./json/onap_policy-models.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                                                                              |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:---------------------------------------------------------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| models-pdp/src/main/java/org/onap/policy/models/pdp/persistence/provider/PdpStatisticsProvider.java                                    |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| models-dao/src/main/java/org/onap/policy/models/dao/PfDao.java                                                                         |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| models-interactions/model-actors/actor.test/src/main/java/org/onap/policy/controlloop/actor/test/BasicBidirectionalTopicOperation.java |             0 |           1 |         0 |           0 |           0 |            0 |     1 |

