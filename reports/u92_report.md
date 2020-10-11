
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_holmes-common.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/holmes-common) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_holmes-common) <br> [Complete issue report (JSON)](./json/onap_holmes-common.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_holmes-engine-management.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/holmes-engine-management) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_holmes-engine-management) <br> [Complete issue report (JSON)](./json/onap_holmes-engine-management.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_holmes-rule-management.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/holmes-rule-management) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_holmes-rule-management) <br> [Complete issue report (JSON)](./json/onap_holmes-rule-management.json)</p>
 | |

# Project report summaries
## Project: _onap/holmes-common_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_holmes-common.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/holmes-common) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_holmes-common) <br> [Complete issue report (JSON)](./json/onap_holmes-common.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name     |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                          |
|:---------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:------------------------------------------------------------------------------|
| AaiConfig.java |              3 |             0 |           0 |      0 |           3 |           0 |            0 | holmes-actions/src/main/java/org/onap/holmes/common/aai/config/AaiConfig.java |

## Project: _onap/holmes-engine-management_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_holmes-engine-management.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/holmes-engine-management) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_holmes-engine-management) <br> [Complete issue report (JSON)](./json/onap_holmes-engine-management.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                      |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:-------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| engine-d/src/main/java/org/onap/holmes/dsa/dmaappolling/Subscriber.java        |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| engine-d/src/main/java/org/onap/holmes/dsa/dmaappolling/DMaaPResponseUtil.java |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| engine-d/src/main/java/org/onap/holmes/engine/wrapper/RuleMgtWrapper.java      |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| engine-d/src/main/java/org/onap/holmes/engine/db/CorrelationRuleDao.java       |             0 |           0 |         0 |           1 |           0 |            0 |     1 |

## Project: _onap/holmes-rule-management_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_holmes-rule-management.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/holmes-rule-management) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_holmes-rule-management) <br> [Complete issue report (JSON)](./json/onap_holmes-rule-management.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name         |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                             |
|:-------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------|
| EngineService.java |              3 |             0 |           3 |      0 |           0 |           0 |            0 | rulemgt/src/main/java/org/onap/holmes/rulemgt/bolt/enginebolt/EngineService.java |

