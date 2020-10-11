
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
|||
|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_policy-drools-applications.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/policy-drools-applications) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_policy-drools-applications) <br> [Complete issue report (JSON)](./json/onap_policy-drools-applications.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_policy-models.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/policy-models) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_policy-models) <br> [Complete issue report (JSON)](./json/onap_policy-models.json)</p>
# Project report summaries
## Project: _onap/policy-drools-applications_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_policy-drools-applications.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/policy-drools-applications) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_policy-drools-applications) <br> [Complete issue report (JSON)](./json/onap_policy-drools-applications.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                                   |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:--------------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| controlloop/m2/base/src/main/java/org/onap/policy/m2/base/Util.java                         |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| controlloop/m2/util/src/main/java/org/onap/policy/util/DroolsSessionCommonSerializable.java |             1 |           0 |         0 |           0 |           0 |            0 |     1 |

## Project: _onap/policy-models_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_policy-models.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/policy-models) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_policy-models) <br> [Complete issue report (JSON)](./json/onap_policy-models.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                                                                              |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:---------------------------------------------------------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| models-pdp/src/main/java/org/onap/policy/models/pdp/persistence/provider/PdpStatisticsProvider.java                                    |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| models-dao/src/main/java/org/onap/policy/models/dao/PfDao.java                                                                         |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| models-interactions/model-actors/actor.test/src/main/java/org/onap/policy/controlloop/actor/test/BasicBidirectionalTopicOperation.java |             0 |           1 |         0 |           0 |           0 |            0 |     1 |

