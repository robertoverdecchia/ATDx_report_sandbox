
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-jcr-repoinit.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-jcr-repoinit) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-jcr-repoinit) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-jcr-repoinit.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-testing-clients.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-testing-clients) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-testing-clients) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-testing-clients.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-testing-rules.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-testing-rules) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-testing-rules) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-testing-rules.json)</p>
 | |

# Project report summaries
## Project: _apache/sling-org-apache-sling-jcr-repoinit_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-jcr-repoinit.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-jcr-repoinit) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-jcr-repoinit) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-jcr-repoinit.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name      |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                             |
|:----------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------|
| AclVisitor.java |              5 |             0 |           5 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/jcr/repoinit/impl/AclVisitor.java |

## Project: _apache/sling-org-apache-sling-testing-clients_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-testing-clients.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-testing-clients) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-testing-clients) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-testing-clients.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name               |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                       |
|:-------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------|
| AbstractSlingClient.java |             10 |             0 |           8 |      0 |           2 |           0 |            0 | src/main/java/org/apache/sling/testing/clients/AbstractSlingClient.java    |
| OsgiConsoleClient.java   |              5 |             0 |           0 |      0 |           5 |           0 |            0 | src/main/java/org/apache/sling/testing/clients/osgi/OsgiConsoleClient.java |
| SlingHttpResponse.java   |              4 |             0 |           4 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/testing/clients/SlingHttpResponse.java      |
| SlingClient.java         |              3 |             0 |           0 |      0 |           3 |           0 |            0 | src/main/java/org/apache/sling/testing/clients/SlingClient.java            |

## Project: _apache/sling-org-apache-sling-testing-rules_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-testing-rules.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-testing-rules) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-testing-rules) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-testing-rules.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                   |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:----------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| src/main/java/org/apache/sling/testing/junit/rules/util/Action.java         |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/testing/junit/rules/RemoteLogDumperRule.java |             1 |           0 |         0 |           0 |           0 |            0 |     1 |

