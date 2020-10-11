
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-jcr-resource.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-jcr-resource) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-jcr-resource) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-jcr-resource.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-models-impl.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-models-impl) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-models-impl) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-models-impl.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-pipes.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-pipes) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-pipes) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-pipes.json)</p>
 | |

# Project report summaries
## Project: _apache/sling-org-apache-sling-jcr-resource_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-jcr-resource.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-jcr-resource) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-jcr-resource) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-jcr-resource.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                                |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:-----------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| src/main/java/org/apache/sling/jcr/resource/internal/helper/jcr/JcrResourceProvider.java |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/jcr/resource/internal/helper/JcrResourceUtil.java         |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/jcr/resource/internal/JcrValueMap.java                    |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/jcr/resource/api/JcrResourceConstants.java                |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/jcr/resource/internal/NodeUtil.java                       |             0 |           0 |         0 |           1 |           0 |            0 |     1 |

## Project: _apache/sling-org-apache-sling-models-impl_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-models-impl.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-models-impl) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-models-impl) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-models-impl.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name               |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                |
|:-------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:--------------------------------------------------------------------|
| ModelAdapterFactory.java |              7 |             0 |           6 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/models/impl/ModelAdapterFactory.java |

## Project: _apache/sling-org-apache-sling-pipes_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-pipes.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-pipes) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-pipes) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-pipes.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name             |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                 |
|:-----------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------|
| GogoCommands.java      |              7 |             0 |           1 |      0 |           0 |           0 |            6 | src/main/java/org/apache/sling/pipes/internal/GogoCommands.java      |
| JsonUtil.java          |              5 |             0 |           4 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/pipes/internal/JsonUtil.java          |
| PlumberImpl.java       |              4 |             0 |           4 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/pipes/internal/PlumberImpl.java       |
| MultiPropertyPipe.java |              4 |             0 |           2 |      0 |           0 |           0 |            2 | src/main/java/org/apache/sling/pipes/internal/MultiPropertyPipe.java |
| PipeBuilder.java       |              4 |             0 |           4 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/pipes/PipeBuilder.java                |
