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
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-jcr-repoinit.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-jcr-repoinit) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-jcr-repoinit) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-jcr-repoinit.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-testing-clients.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-testing-clients) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-testing-clients) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-testing-clients.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-testing-rules.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-testing-rules) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-testing-rules) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-testing-rules.json)</p>
 | |

# Project report summaries
## Project: _apache/sling-org-apache-sling-jcr-repoinit_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-jcr-repoinit.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-jcr-repoinit) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-jcr-repoinit) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-jcr-repoinit.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                  | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                                   |
|:----------------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:-----------------------------------------------------------------------------|
| AclVisitor.java             | 5              | 0             | 5           | 0      | 0           | 0           | 0            | src/main/java/org/apache/sling/jcr/repoinit/impl/AclVisitor.java             |
| GroupMembershipVisitor.java | 2              | 0             | 2           | 0      | 0           | 0           | 0            | src/main/java/org/apache/sling/jcr/repoinit/impl/GroupMembershipVisitor.java |
| UserVisitor.java            | 1              | 0             | 1           | 0      | 0           | 0           | 0            | src/main/java/org/apache/sling/jcr/repoinit/impl/UserVisitor.java            |
| DoNothingVisitor.java       | 1              | 0             | 1           | 0      | 0           | 0           | 0            | src/main/java/org/apache/sling/jcr/repoinit/impl/DoNothingVisitor.java       |
| AclUtil.java                | 1              | 0             | 0           | 0      | 1           | 0           | 0            | src/main/java/org/apache/sling/jcr/repoinit/impl/AclUtil.java                |
| NodePropertiesVisitor.java  | 1              | 0             | 1           | 0      | 0           | 0           | 0            | src/main/java/org/apache/sling/jcr/repoinit/impl/NodePropertiesVisitor.java  |
| UserUtil.java               | 1              | 0             | 0           | 0      | 1           | 0           | 0            | src/main/java/org/apache/sling/jcr/repoinit/impl/UserUtil.java               |
| -                           | -              | -             | -           | -      | -           | -           | -            | -                                                                            |
| -                           | -              | -             | -           | -      | -           | -           | -            | -                                                                            |
| -                           | -              | -             | -           | -      | -           | -           | -            | -                                                                            |

## Project: _apache/sling-org-apache-sling-testing-clients_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-testing-clients.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-testing-clients) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-testing-clients) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-testing-clients.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                  |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified class name                                                 |
|:----------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------|
| AbstractSlingClient.java    |             10 |             0 |           8 |      0 |           2 |           0 |            0 | src/main/java/org/apache/sling/testing/clients/AbstractSlingClient.java    |
| OsgiConsoleClient.java      |              5 |             0 |           0 |      0 |           5 |           0 |            0 | src/main/java/org/apache/sling/testing/clients/osgi/OsgiConsoleClient.java |
| SlingHttpResponse.java      |              4 |             0 |           4 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/testing/clients/SlingHttpResponse.java      |
| SlingClient.java            |              3 |             0 |           0 |      0 |           3 |           0 |            0 | src/main/java/org/apache/sling/testing/clients/SlingClient.java            |
| HttpUtils.java              |              2 |             0 |           1 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/testing/clients/util/HttpUtils.java         |
| XSSUtils.java               |              2 |             0 |           1 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/testing/clients/util/XSSUtils.java          |
| ResourceUtil.java           |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/testing/clients/util/ResourceUtil.java      |
| BundlesInstaller.java       |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/testing/clients/osgi/BundlesInstaller.java  |
| Constants.java              |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/testing/Constants.java                      |
| SystemPropertiesConfig.java |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/testing/clients/SystemPropertiesConfig.java |

## Project: _apache/sling-org-apache-sling-testing-rules_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-testing-rules.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-testing-rules) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-testing-rules) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-testing-rules.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name               | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                                  |
|:-------------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:----------------------------------------------------------------------------|
| Action.java              | 1              | 0             | 1           | 0      | 0           | 0           | 0            | src/main/java/org/apache/sling/testing/junit/rules/util/Action.java         |
| RemoteLogDumperRule.java | 1              | 1             | 0           | 0      | 0           | 0           | 0            | src/main/java/org/apache/sling/testing/junit/rules/RemoteLogDumperRule.java |
| -                        | -              | -             | -           | -      | -           | -           | -            | -                                                                           |
| -                        | -              | -             | -           | -      | -           | -           | -            | -                                                                           |
| -                        | -              | -             | -           | -      | -           | -           | -            | -                                                                           |
| -                        | -              | -             | -           | -      | -           | -           | -            | -                                                                           |
| -                        | -              | -             | -           | -      | -           | -           | -            | -                                                                           |
| -                        | -              | -             | -           | -      | -           | -           | -            | -                                                                           |
| -                        | -              | -             | -           | -      | -           | -           | -            | -                                                                           |
| -                        | -              | -             | -           | -      | -           | -           | -            | -                                                                           |

