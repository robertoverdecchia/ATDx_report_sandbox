
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-commons-scheduler.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-commons-scheduler) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-commons-scheduler) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-commons-scheduler.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-discovery-impl.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-discovery-impl) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-discovery-impl) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-discovery-impl.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-discovery-oak.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-discovery-oak) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-discovery-oak) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-discovery-oak.json)</p>
 | |

# Project report summaries
## Project: _apache/sling-org-apache-sling-commons-scheduler_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-commons-scheduler.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-commons-scheduler) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-commons-scheduler) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-commons-scheduler.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                   |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                               |
|:-----------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------------------------|
| Scheduler.java               |             14 |             0 |           6 |      0 |           8 |           0 |            0 | src/main/java/org/apache/sling/commons/scheduler/Scheduler.java                    |
| WebConsolePrinter.java       |              9 |             0 |           0 |      0 |           9 |           0 |            0 | src/main/java/org/apache/sling/commons/scheduler/impl/WebConsolePrinter.java       |
| InternalScheduleOptions.java |              6 |             0 |           0 |      0 |           6 |           0 |            0 | src/main/java/org/apache/sling/commons/scheduler/impl/InternalScheduleOptions.java |
| QuartzScheduler.java         |              4 |             0 |           2 |      0 |           2 |           0 |            0 | src/main/java/org/apache/sling/commons/scheduler/impl/QuartzScheduler.java         |

## Project: _apache/sling-org-apache-sling-discovery-impl_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-discovery-impl.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-discovery-impl) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-discovery-impl) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-discovery-impl.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                    |
|:--------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:------------------------------------------------------------------------|
| DiscoveryServiceImpl.java |              4 |             0 |           2 |      0 |           1 |           0 |            1 | src/main/java/org/apache/sling/discovery/impl/DiscoveryServiceImpl.java |
| View.java                 |              3 |             0 |           3 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/discovery/impl/common/View.java          |

## Project: _apache/sling-org-apache-sling-discovery-oak_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-discovery-oak.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-discovery-oak) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-discovery-oak) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-discovery-oak.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                 |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                            |
|:---------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:--------------------------------------------------------------------------------|
| OakDiscoveryService.java   |              4 |             0 |           2 |      0 |           1 |           0 |            1 | src/main/java/org/apache/sling/discovery/oak/OakDiscoveryService.java           |
| OakClusterViewService.java |              4 |             0 |           4 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/discovery/oak/cluster/OakClusterViewService.java |

