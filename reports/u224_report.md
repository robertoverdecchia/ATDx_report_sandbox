
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
|||
|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-junit-core.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-junit-core) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-junit-core) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-junit-core.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-testing-clients.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-testing-clients) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-testing-clients) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-testing-clients.json)</p>
# Project report summaries
## Project: _apache/sling-org-apache-sling-junit-core_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-junit-core.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-junit-core) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-junit-core) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-junit-core.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                     |
|:--------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-------------------------------------------------------------------------|
| SlingJUnitServlet.java    |              4 |             0 |           4 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/junit/impl/servlet/SlingJUnitServlet.java |
| RendererSelectorImpl.java |              4 |             0 |           4 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/junit/impl/RendererSelectorImpl.java      |
| JsonRenderer.java         |              4 |             0 |           4 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/junit/impl/servlet/JsonRenderer.java      |
| TestLogServlet.java       |              3 |             0 |           3 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/junit/impl/servlet/TestLogServlet.java    |
| PlainTextRenderer.java    |              3 |             2 |           1 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/junit/impl/servlet/PlainTextRenderer.java |

## Project: _apache/sling-org-apache-sling-testing-clients_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-testing-clients.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-testing-clients) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-testing-clients) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-testing-clients.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name               |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                       |
|:-------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------|
| AbstractSlingClient.java |             10 |             0 |           8 |      0 |           2 |           0 |            0 | src/main/java/org/apache/sling/testing/clients/AbstractSlingClient.java    |
| OsgiConsoleClient.java   |              5 |             0 |           0 |      0 |           5 |           0 |            0 | src/main/java/org/apache/sling/testing/clients/osgi/OsgiConsoleClient.java |
| SlingHttpResponse.java   |              4 |             0 |           4 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/testing/clients/SlingHttpResponse.java      |
| SlingClient.java         |              3 |             0 |           0 |      0 |           3 |           0 |            0 | src/main/java/org/apache/sling/testing/clients/SlingClient.java            |

