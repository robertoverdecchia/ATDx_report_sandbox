
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-api.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-api) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-api) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-api.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-auth-core.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-auth-core) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-auth-core) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-auth-core.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-commons-scheduler.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-commons-scheduler) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-commons-scheduler) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-commons-scheduler.json)</p>
 | |
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-discovery-oak.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-discovery-oak) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-discovery-oak) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-discovery-oak.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-distribution-core.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-distribution-core) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-distribution-core) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-distribution-core.json)</p>
# Project report summaries
## Project: _apache/sling-org-apache-sling-api_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-api.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-api) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-api) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-api.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name               |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                             |
|:-------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------|
| ResourceProviderDTO.java |             10 |             0 |           0 |      0 |          10 |           0 |            0 | src/main/java/org/apache/sling/api/resource/runtime/dto/ResourceProviderDTO.java |
| ResourceUtil.java        |              7 |             0 |           0 |      0 |           7 |           0 |            0 | src/main/java/org/apache/sling/api/resource/ResourceUtil.java                    |
| SlingConstants.java      |              4 |             0 |           0 |      0 |           4 |           0 |            0 | src/main/java/org/apache/sling/api/SlingConstants.java                           |
| ResourceChange.java      |              4 |             0 |           0 |      0 |           4 |           0 |            0 | src/main/java/org/apache/sling/api/resource/observation/ResourceChange.java      |
| CompositeValueMap.java   |              3 |             2 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/api/wrappers/CompositeValueMap.java               |
| NonExistingResource.java |              3 |             3 |           0 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/api/resource/NonExistingResource.java             |

## Project: _apache/sling-org-apache-sling-auth-core_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-auth-core.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-auth-core) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-auth-core) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-auth-core.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                         |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                            |
|:-----------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:--------------------------------------------------------------------------------|
| AbstractAuthenticationHandler.java |              9 |             0 |           0 |      0 |           9 |           0 |            0 | src/main/java/org/apache/sling/auth/core/spi/AbstractAuthenticationHandler.java |

## Project: _apache/sling-org-apache-sling-commons-scheduler_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-commons-scheduler.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-commons-scheduler) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-commons-scheduler) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-commons-scheduler.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                   |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                               |
|:-----------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------------------------|
| Scheduler.java               |             14 |             0 |           6 |      0 |           8 |           0 |            0 | src/main/java/org/apache/sling/commons/scheduler/Scheduler.java                    |
| WebConsolePrinter.java       |              9 |             0 |           0 |      0 |           9 |           0 |            0 | src/main/java/org/apache/sling/commons/scheduler/impl/WebConsolePrinter.java       |
| InternalScheduleOptions.java |              6 |             0 |           0 |      0 |           6 |           0 |            0 | src/main/java/org/apache/sling/commons/scheduler/impl/InternalScheduleOptions.java |
| QuartzScheduler.java         |              4 |             0 |           2 |      0 |           2 |           0 |            0 | src/main/java/org/apache/sling/commons/scheduler/impl/QuartzScheduler.java         |

## Project: _apache/sling-org-apache-sling-discovery-oak_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-discovery-oak.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-discovery-oak) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-discovery-oak) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-discovery-oak.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                 |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                            |
|:---------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:--------------------------------------------------------------------------------|
| OakDiscoveryService.java   |              4 |             0 |           2 |      0 |           1 |           0 |            1 | src/main/java/org/apache/sling/discovery/oak/OakDiscoveryService.java           |
| OakClusterViewService.java |              4 |             0 |           4 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/discovery/oak/cluster/OakClusterViewService.java |

## Project: _apache/sling-org-apache-sling-distribution-core_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-distribution-core.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-distribution-core) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-distribution-core) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-distribution-core.json)</p>
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

