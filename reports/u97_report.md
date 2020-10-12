# ATDx Report Summary
Following the overview of the ATDx analysis of your projects.

In short, the ATDx analysis is based on software metrics aggregation, and statistical severity evaluation of the aggregated values across a portfolio of software projects.

ATDx provides an overview of the project Architectural Technical Debt (ATD) in 6 distinct dimensions:
* **Inheritance**: flaws concerning inheritance mechanisms between classes, such as overrides and inheritance of methods or fields
* **Exception**: flaws regarding the Java throwable class “Exception” and its subclasses
* **JVMS**: potential misuse of the Java Virtual Machine, e.g., the incorrect usage of the specific Java class “Serializable”
* **Threading**: flaws arising from the implementation of multiple execution threads, which could potentially lead to concurrency problems
* **Interface**: flaws related to the usage of Java interfaces
* **Complexity**: flaws derived from prominent complexity measures, such as McCabe’s cyclomatic complexity

For each project, an overview of the ATDx values is presented, followed by the top classes of the project contributing to the ATDx values.

Note that if numerous classes with 1 violation are reported, this might point to a widespread problematics (only a maximum of 10 classes are provided per project). Similarly, empty rows may indicate that only few classes are affected by ATDx violations.
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_holmes-common.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/holmes-common) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_holmes-common) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_holmes-common.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_holmes-engine-management.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/holmes-engine-management) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_holmes-engine-management) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_holmes-engine-management.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_holmes-rule-management.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/holmes-rule-management) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_holmes-rule-management) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_holmes-rule-management.json)</p>
 | |

# Project report summaries
## Project: _onap/holmes-common_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_holmes-common.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/holmes-common) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_holmes-common) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_holmes-common.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified class name                                                                         |
|:--------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------------------------|
| AaiConfig.java            |              3 |             0 |           0 |      0 |           3 |           0 |            0 | holmes-actions/src/main/java/org/onap/holmes/common/aai/config/AaiConfig.java                      |
| VesAlarm.java             |              2 |             2 |           0 |      0 |           0 |           0 |            0 | holmes-actions/src/main/java/org/onap/holmes/common/api/stat/VesAlarm.java                         |
| MicroServiceConfig.java   |              1 |             0 |           0 |      0 |           1 |           0 |            0 | holmes-actions/src/main/java/org/onap/holmes/common/config/MicroServiceConfig.java                 |
| CorrelationRule.java      |              1 |             1 |           0 |      0 |           0 |           0 |            0 | holmes-actions/src/main/java/org/onap/holmes/common/api/entity/CorrelationRule.java                |
| AaiQuery4Ccvpn.java       |              1 |             0 |           1 |      0 |           0 |           0 |            0 | holmes-actions/src/main/java/org/onap/holmes/common/aai/AaiQuery4Ccvpn.java                        |
| ServiceLocatorHolder.java |              1 |             0 |           0 |      0 |           1 |           0 |            0 | holmes-actions/src/main/java/org/onap/holmes/common/dropwizard/ioc/utils/ServiceLocatorHolder.java |
| DroolsLog.java            |              1 |             0 |           0 |      0 |           1 |           0 |            0 | holmes-actions/src/main/java/org/onap/holmes/common/utils/DroolsLog.java                           |
| GsonUtil.java             |              1 |             0 |           1 |      0 |           0 |           0 |            0 | holmes-actions/src/main/java/org/onap/holmes/common/utils/GsonUtil.java                            |
| Alarm.java                |              1 |             1 |           0 |      0 |           0 |           0 |            0 | holmes-actions/src/main/java/org/onap/holmes/common/api/stat/Alarm.java                            |
| HttpsUtils.java           |              1 |             0 |           0 |      0 |           1 |           0 |            0 | holmes-actions/src/main/java/org/onap/holmes/common/utils/HttpsUtils.java                          |

## Project: _onap/holmes-engine-management_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_holmes-engine-management.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/holmes-engine-management) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_holmes-engine-management) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_holmes-engine-management.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name              | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                                     |
|:------------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:-------------------------------------------------------------------------------|
| Subscriber.java         | 1              | 0             | 1           | 0      | 0           | 0           | 0            | engine-d/src/main/java/org/onap/holmes/dsa/dmaappolling/Subscriber.java        |
| DMaaPResponseUtil.java  | 1              | 0             | 1           | 0      | 0           | 0           | 0            | engine-d/src/main/java/org/onap/holmes/dsa/dmaappolling/DMaaPResponseUtil.java |
| RuleMgtWrapper.java     | 1              | 0             | 1           | 0      | 0           | 0           | 0            | engine-d/src/main/java/org/onap/holmes/engine/wrapper/RuleMgtWrapper.java      |
| CorrelationRuleDao.java | 1              | 0             | 0           | 0      | 1           | 0           | 0            | engine-d/src/main/java/org/onap/holmes/engine/db/CorrelationRuleDao.java       |
| -                       | -              | -             | -           | -      | -           | -           | -            | -                                                                              |
| -                       | -              | -             | -           | -      | -           | -           | -            | -                                                                              |
| -                       | -              | -             | -           | -      | -           | -           | -            | -                                                                              |
| -                       | -              | -             | -           | -      | -           | -           | -            | -                                                                              |
| -                       | -              | -             | -           | -      | -           | -           | -            | -                                                                              |
| -                       | -              | -             | -           | -      | -           | -           | -            | -                                                                              |

## Project: _onap/holmes-rule-management_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_holmes-rule-management.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/holmes-rule-management) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_holmes-rule-management) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_holmes-rule-management.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name              | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                                       |
|:------------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:---------------------------------------------------------------------------------|
| EngineService.java      | 3              | 0             | 3           | 0      | 0           | 0           | 0            | rulemgt/src/main/java/org/onap/holmes/rulemgt/bolt/enginebolt/EngineService.java |
| MsbQuery.java           | 2              | 0             | 2           | 0      | 0           | 0           | 0            | rulemgt/src/main/java/org/onap/holmes/rulemgt/msb/MsbQuery.java                  |
| RuleMgtWrapper.java     | 2              | 0             | 2           | 0      | 0           | 0           | 0            | rulemgt/src/main/java/org/onap/holmes/rulemgt/wrapper/RuleMgtWrapper.java        |
| RuleQueryWrapper.java   | 2              | 0             | 2           | 0      | 0           | 0           | 0            | rulemgt/src/main/java/org/onap/holmes/rulemgt/wrapper/RuleQueryWrapper.java      |
| EngineInsQueryTool.java | 1              | 0             | 1           | 0      | 0           | 0           | 0            | rulemgt/src/main/java/org/onap/holmes/rulemgt/msb/EngineInsQueryTool.java        |
| RuleAllocator.java      | 1              | 0             | 1           | 0      | 0           | 0           | 0            | rulemgt/src/main/java/org/onap/holmes/rulemgt/send/RuleAllocator.java            |
| -                       | -              | -             | -           | -      | -           | -           | -            | -                                                                                |
| -                       | -              | -             | -           | -      | -           | -           | -            | -                                                                                |
| -                       | -              | -             | -           | -      | -           | -           | -            | -                                                                                |
| -                       | -              | -             | -           | -      | -           | -           | -            | -                                                                                |

