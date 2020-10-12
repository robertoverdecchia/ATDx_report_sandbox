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
|||
|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_policy-apex-pdp.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/policy-apex-pdp) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_policy-apex-pdp) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_policy-apex-pdp.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_policy-models.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/policy-models) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_policy-models) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_policy-models.json)</p>
# Project report summaries
## Project: _onap/policy-apex-pdp_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_policy-apex-pdp.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/policy-apex-pdp) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_policy-apex-pdp) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_policy-apex-pdp.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name           | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                                                        |
|:---------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:--------------------------------------------------------------------------------------------------|
| ApexEditorApi.java   | 3              | 0             | 0           | 0      | 3           | 0           | 0            | model/model-api/src/main/java/org/onap/policy/apex/model/modelapi/ApexEditorApi.java              |
| ApexModelImpl.java   | 2              | 2             | 0           | 0      | 0           | 0           | 0            | model/model-api/src/main/java/org/onap/policy/apex/model/modelapi/impl/ApexModelImpl.java         |
| CollectionUtils.java | 1              | 0             | 0           | 0      | 1           | 0           | 0            | model/utilities/src/main/java/org/onap/policy/apex/model/utilities/CollectionUtils.java           |
| TreeMapUtils.java    | 1              | 0             | 0           | 0      | 1           | 0           | 0            | model/utilities/src/main/java/org/onap/policy/apex/model/utilities/TreeMapUtils.java              |
| AxStateTree.java     | 1              | 1             | 0           | 0      | 0           | 0           | 0            | model/policy-model/src/main/java/org/onap/policy/apex/model/policymodel/concepts/AxStateTree.java |
| ApexModel.java       | 1              | 1             | 0           | 0      | 0           | 0           | 0            | model/model-api/src/main/java/org/onap/policy/apex/model/modelapi/ApexModel.java                  |
| -                    | -              | -             | -           | -      | -           | -           | -            | -                                                                                                 |
| -                    | -              | -             | -           | -      | -           | -           | -            | -                                                                                                 |
| -                    | -              | -             | -           | -      | -           | -           | -            | -                                                                                                 |
| -                    | -              | -             | -           | -      | -           | -           | -            | -                                                                                                 |

## Project: _onap/policy-models_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_policy-models.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/policy-models) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_policy-models) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_policy-models.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                            | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                                                                                             |
|:--------------------------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:---------------------------------------------------------------------------------------------------------------------------------------|
| PdpStatisticsProvider.java            | 1              | 0             | 0           | 0      | 1           | 0           | 0            | models-pdp/src/main/java/org/onap/policy/models/pdp/persistence/provider/PdpStatisticsProvider.java                                    |
| PfDao.java                            | 1              | 0             | 0           | 0      | 1           | 0           | 0            | models-dao/src/main/java/org/onap/policy/models/dao/PfDao.java                                                                         |
| BasicBidirectionalTopicOperation.java | 1              | 0             | 1           | 0      | 0           | 0           | 0            | models-interactions/model-actors/actor.test/src/main/java/org/onap/policy/controlloop/actor/test/BasicBidirectionalTopicOperation.java |
| -                                     | -              | -             | -           | -      | -           | -           | -            | -                                                                                                                                      |
| -                                     | -              | -             | -           | -      | -           | -           | -            | -                                                                                                                                      |
| -                                     | -              | -             | -           | -      | -           | -           | -            | -                                                                                                                                      |
| -                                     | -              | -             | -           | -      | -           | -           | -            | -                                                                                                                                      |
| -                                     | -              | -             | -           | -      | -           | -           | -            | -                                                                                                                                      |
| -                                     | -              | -             | -           | -      | -           | -           | -            | -                                                                                                                                      |
| -                                     | -              | -             | -           | -      | -           | -           | -            | -                                                                                                                                      |

