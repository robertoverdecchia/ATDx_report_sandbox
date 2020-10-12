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
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_policy-drools-applications.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/policy-drools-applications) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_policy-drools-applications) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_policy-drools-applications.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_policy-drools-pdp.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/onap/policy-drools-pdp) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_policy-drools-pdp) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_policy-drools-pdp.json)</p>
# Project report summaries
## Project: _onap/policy-drools-applications_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_policy-drools-applications.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/policy-drools-applications) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_policy-drools-applications) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_policy-drools-applications.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                           | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                                                  |
|:-------------------------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:--------------------------------------------------------------------------------------------|
| GuardContext.java                    | 2              | 0             | 0           | 0      | 2           | 0           | 0            | controlloop/m2/guard/src/main/java/org/onap/policy/guard/GuardContext.java                  |
| Util.java                            | 1              | 0             | 0           | 0      | 1           | 0           | 0            | controlloop/m2/base/src/main/java/org/onap/policy/m2/base/Util.java                         |
| DroolsSessionCommonSerializable.java | 1              | 1             | 0           | 0      | 0           | 0           | 0            | controlloop/m2/util/src/main/java/org/onap/policy/util/DroolsSessionCommonSerializable.java |
| -                                    | -              | -             | -           | -      | -           | -           | -            | -                                                                                           |
| -                                    | -              | -             | -           | -      | -           | -           | -            | -                                                                                           |
| -                                    | -              | -             | -           | -      | -           | -           | -            | -                                                                                           |
| -                                    | -              | -             | -           | -      | -           | -           | -            | -                                                                                           |
| -                                    | -              | -             | -           | -      | -           | -           | -            | -                                                                                           |
| -                                    | -              | -             | -           | -      | -           | -           | -            | -                                                                                           |
| -                                    | -              | -             | -           | -      | -           | -           | -            | -                                                                                           |

## Project: _onap/policy-drools-pdp_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/onap_policy-drools-pdp.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/onap/policy-drools-pdp) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=onap_policy-drools-pdp) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/onap_policy-drools-pdp.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                     | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                                                                   |
|:-------------------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:-------------------------------------------------------------------------------------------------------------|
| Bucket.java                    | 9              | 2             | 1           | 0      | 0           | 0           | 6            | feature-server-pool/src/main/java/org/onap/policy/drools/serverpool/Bucket.java                              |
| Server.java                    | 7              | 1             | 4           | 0      | 0           | 0           | 2            | feature-server-pool/src/main/java/org/onap/policy/drools/serverpool/Server.java                              |
| TargetLock.java                | 7              | 0             | 1           | 0      | 0           | 0           | 6            | feature-server-pool/src/main/java/org/onap/policy/drools/serverpool/TargetLock.java                          |
| Leader.java                    | 4              | 1             | 0           | 0      | 1           | 0           | 2            | feature-server-pool/src/main/java/org/onap/policy/drools/serverpool/Leader.java                              |
| StateManagementFeatureApi.java | 4              | 0             | 4           | 0      | 0           | 0           | 0            | api-state-management/src/main/java/org/onap/policy/drools/statemanagement/StateManagementFeatureApi.java     |
| ServerPoolProperties.java      | 1              | 0             | 0           | 0      | 1           | 0           | 0            | feature-server-pool/src/main/java/org/onap/policy/drools/serverpool/ServerPoolProperties.java                |
| Util.java                      | 1              | 0             | 0           | 0      | 1           | 0           | 0            | feature-server-pool/src/main/java/org/onap/policy/drools/serverpool/Util.java                                |
| DroolsPdpIntegrityMonitor.java | 1              | 0             | 1           | 0      | 0           | 0           | 0            | feature-state-management/src/main/java/org/onap/policy/drools/statemanagement/DroolsPdpIntegrityMonitor.java |
| -                              | -              | -             | -           | -      | -           | -           | -            | -                                                                                                            |
| -                              | -              | -             | -           | -      | -           | -           | -            | -                                                                                                            |

