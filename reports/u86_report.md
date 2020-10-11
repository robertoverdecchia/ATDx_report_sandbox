
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="./plots/apache_sling-org-apache-sling-distribution-core.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-distribution-core) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-distribution-core) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-distribution-core.json)</p>|<img src="./plots/apache_sling-org-apache-sling-distribution-journal.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-distribution-journal) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-distribution-journal) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-distribution-journal.json)</p>|<img src="./plots/apache_sling-org-apache-sling-resource-filter.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-resource-filter) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-resource-filter) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-resource-filter.json)</p>
 | |

# Project report summaries
## Project: _apache/sling-org-apache-sling-distribution-core_
|./plots/apache_sling-org-apache-sling-distribution-core.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-distribution-core) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-distribution-core) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-distribution-core.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                                 |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                           |
|:-------------------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------------------------------------|
| ResourceQueue.java                         |             12 |             0 |          12 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/distribution/queue/impl/resource/ResourceQueue.java                             |
| ForwardDistributionAgentFactory.java       |              4 |             4 |           0 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/distribution/agent/impl/ForwardDistributionAgentFactory.java                    |
| SyncDistributionAgentFactory.java          |              4 |             4 |           0 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/distribution/agent/impl/SyncDistributionAgentFactory.java                       |
| ReverseDistributionAgentFactory.java       |              4 |             4 |           0 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/distribution/agent/impl/ReverseDistributionAgentFactory.java                    |
| QueueDistributionAgentFactory.java         |              4 |             4 |           0 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/distribution/agent/impl/QueueDistributionAgentFactory.java                      |
| SimpleDistributionAgentFactory.java        |              4 |             4 |           0 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/distribution/agent/impl/SimpleDistributionAgentFactory.java                     |
| DistributionPackageExporterServlet.java    |              3 |             0 |           3 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/distribution/servlet/DistributionPackageExporterServlet.java                    |
| RepositoryDistributionPackageImporter.java |              3 |             0 |           3 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/distribution/packaging/impl/importer/RepositoryDistributionPackageImporter.java |

## Project: _apache/sling-org-apache-sling-distribution-journal_
|./plots/apache_sling-org-apache-sling-distribution-journal.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-distribution-journal) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-distribution-journal) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-distribution-journal.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name      |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                |
|:----------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:------------------------------------------------------------------------------------|
| LocalStore.java |              3 |             0 |           3 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/distribution/journal/impl/subscriber/LocalStore.java |

## Project: _apache/sling-org-apache-sling-resource-filter_
|./plots/apache_sling-org-apache-sling-resource-filter.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-resource-filter) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-resource-filter) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-resource-filter.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name            |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                             |
|:----------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------|
| FilterParser.java     |             33 |             0 |          16 |      0 |           3 |           0 |           14 | src/main/java/org/apache/sling/resource/filter/impl/script/FilterParser.java     |
| Token.java            |              8 |             0 |           0 |      0 |           8 |           0 |            0 | src/main/java/org/apache/sling/resource/filter/impl/script/Token.java            |
| ParseException.java   |              7 |             0 |           4 |      0 |           3 |           0 |            0 | src/main/java/org/apache/sling/resource/filter/impl/script/ParseException.java   |
| Node.java             |              5 |             0 |           0 |      0 |           5 |           0 |            0 | src/main/java/org/apache/sling/resource/filter/impl/node/Node.java               |
| SimpleCharStream.java |              4 |             0 |           1 |      0 |           3 |           0 |            0 | src/main/java/org/apache/sling/resource/filter/impl/script/SimpleCharStream.java |
| TokenMgrError.java    |              3 |             2 |           1 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/resource/filter/impl/script/TokenMgrError.java    |

