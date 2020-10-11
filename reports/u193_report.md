
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
|||
|-|-|
|<img src="./plots/onap_policy-drools-applications.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/policy-drools-applications) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_policy-drools-applications) <br> [Complete issue report (JSON)](./json/onap_policy-drools-applications.json)</p>|<img src="./plots/onap_policy-drools-pdp.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/policy-drools-pdp) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_policy-drools-pdp) <br> [Complete issue report (JSON)](./json/onap_policy-drools-pdp.json)</p>
# Project report summaries
## Project: _onap/policy-drools-applications_
|./plots/onap_policy-drools-applications.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/policy-drools-applications) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_policy-drools-applications) <br> [Complete issue report (JSON)](./json/onap_policy-drools-applications.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                                   |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:--------------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| controlloop/m2/base/src/main/java/org/onap/policy/m2/base/Util.java                         |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| controlloop/m2/util/src/main/java/org/onap/policy/util/DroolsSessionCommonSerializable.java |             1 |           0 |         0 |           0 |           0 |            0 |     1 |

## Project: _onap/policy-drools-pdp_
|./plots/onap_policy-drools-pdp.jpg|<p style="text-align:left">[Project on Github](https://github.com/onap/policy-drools-pdp) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_policy-drools-pdp) <br> [Complete issue report (JSON)](./json/onap_policy-drools-pdp.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                     |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                     |
|:-------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------------------------------|
| Bucket.java                    |              9 |             2 |           1 |      0 |           0 |           0 |            6 | feature-server-pool/src/main/java/org/onap/policy/drools/serverpool/Bucket.java                          |
| Server.java                    |              7 |             1 |           4 |      0 |           0 |           0 |            2 | feature-server-pool/src/main/java/org/onap/policy/drools/serverpool/Server.java                          |
| TargetLock.java                |              7 |             0 |           1 |      0 |           0 |           0 |            6 | feature-server-pool/src/main/java/org/onap/policy/drools/serverpool/TargetLock.java                      |
| Leader.java                    |              4 |             1 |           0 |      0 |           1 |           0 |            2 | feature-server-pool/src/main/java/org/onap/policy/drools/serverpool/Leader.java                          |
| StateManagementFeatureApi.java |              4 |             0 |           4 |      0 |           0 |           0 |            0 | api-state-management/src/main/java/org/onap/policy/drools/statemanagement/StateManagementFeatureApi.java |

