# ATDx Report Summary
Our ATDx analysis targets a portfolio of software projects and identifies the pain points of each project in terms of Architectural Technical Debt (ATD). This evaluation is based on a statistical analysis of the violations of SonarCloud rules.

ATDx provides an overview of the architectural technical debt in a project  in 6 distinct dimensions:
* **Inheritance**: flaws concerning inheritance mechanisms between classes, such as overrides and inheritance of methods or fields
* **Exception**: flaws regarding the management of Java exceptions and the subclassing of the “Exception” Java class.
* **JVMS**: potential misuses of the Java Virtual Machine, e.g., the incorrect usage of the specific Java class “Serializable”
* **Threading**: flaws arising from the implementation of multiple execution threads, which could potentially lead to concurrency problems
* **Interface**: flaws related to the usage of Java interfaces
* **Complexity**: flaws derived from prominent complexity measures, such as McCabe’s cyclomatic complexity

For each project, the dimensions assume a value between 0 and 5, where 0 denotes minimum architectural debt of the project in that dimension, and 5 maximum architectural debt.

In the reminder of this report, we firstly provide a set of radar charts (one for each project). Then for each project we give:
1. The same radar chart as shown at the beginning
2. A table showing the top-10 classes of the project with the highest architectural technical debt.

Note that if numerous classes with 1 violation are reported, this might point to a widespread problem (only a maximum of 10 classes are provided per project for the sake of readability). Similarly, empty rows indicate that only a few classes are affected by ATDx violations.

## Radar charts
||||
|-|-|-|
|<p align="center">Project 1</p><img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-api.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-api) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-api) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-api.json)</p>|<p align="center">Project 2</p><img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-clam.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-clam) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-clam) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-clam.json)</p>|<p align="center">Project 3</p><img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-commons-html.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-commons-html) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-commons-html) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-commons-html.json)</p>
 | |
|<p align="center">Project 4</p><img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-commons-jcr-file.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-commons-jcr-file) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-commons-jcr-file) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-commons-jcr-file.json)</p>|<p align="center">Project 5</p><img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-commons-metrics.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-commons-metrics) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-commons-metrics) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-commons-metrics.json)</p>|<p align="center">Project 6</p><img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-i18n.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-i18n) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-i18n) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-i18n.json)</p>
 | |
|<p align="center">Project 7</p><img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-jcr-contentloader.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-jcr-contentloader) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-jcr-contentloader) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-jcr-contentloader.json)</p>|<p align="center">Project 8</p><img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-jcr-repoinit.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-jcr-repoinit) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-jcr-repoinit) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-jcr-repoinit.json)</p>|<p align="center">Project 9</p><img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-pipes.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-pipes) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-pipes) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-pipes.json)</p>

# Project report summaries
## Project 1: _apache/sling-org-apache-sling-api_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-api.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-api) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-api) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-api.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name               |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified class name                                                       |
|:-------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------|
| ResourceProviderDTO.java |             10 |             0 |           0 |      0 |          10 |           0 |            0 | src/main/java/org/apache/sling/api/resource/runtime/dto/ResourceProviderDTO.java |
| ResourceUtil.java        |              7 |             0 |           0 |      0 |           7 |           0 |            0 | src/main/java/org/apache/sling/api/resource/ResourceUtil.java                    |
| SlingConstants.java      |              4 |             0 |           0 |      0 |           4 |           0 |            0 | src/main/java/org/apache/sling/api/SlingConstants.java                           |
| ResourceChange.java      |              4 |             0 |           0 |      0 |           4 |           0 |            0 | src/main/java/org/apache/sling/api/resource/observation/ResourceChange.java      |
| CompositeValueMap.java   |              3 |             2 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/api/wrappers/CompositeValueMap.java               |
| NonExistingResource.java |              3 |             3 |           0 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/api/resource/NonExistingResource.java             |
| ResourceMetadata.java    |              2 |             1 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/api/resource/ResourceMetadata.java                |
| ResourceProvider.java    |              2 |             0 |           0 |      0 |           2 |           0 |            0 | src/main/java/org/apache/sling/api/resource/ResourceProvider.java                |
| RuntimeDTO.java          |              2 |             0 |           0 |      0 |           2 |           0 |            0 | src/main/java/org/apache/sling/api/resource/runtime/dto/RuntimeDTO.java          |
| ValueMapDecorator.java   |              2 |             2 |           0 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/api/wrappers/ValueMapDecorator.java               |

## Project 2: _apache/sling-org-apache-sling-clam_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-clam.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-clam) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-clam) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-clam.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                               | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                                                   |
|:-----------------------------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:---------------------------------------------------------------------------------------------|
| RequestUtil.java                         | 10             | 0             | 10          | 0      | 0           | 0           | 0            | src/main/java/org/apache/sling/clam/http/internal/RequestUtil.java                           |
| ClamUtil.java                            | 3              | 0             | 2           | 0      | 1           | 0           | 0            | src/main/java/org/apache/sling/clam/internal/ClamUtil.java                                   |
| JcrPropertyScanJobConsumer.java          | 2              | 0             | 2           | 0      | 0           | 0           | 0            | src/main/java/org/apache/sling/clam/job/internal/JcrPropertyScanJobConsumer.java             |
| ResourcePersistingScanResultHandler.java | 2              | 0             | 1           | 0      | 0           | 1           | 0            | src/main/java/org/apache/sling/clam/result/internal/ResourcePersistingScanResultHandler.java |
| NodeDescendingJcrPropertyDigger.java     | 1              | 0             | 1           | 0      | 0           | 0           | 0            | src/main/java/org/apache/sling/clam/jcr/NodeDescendingJcrPropertyDigger.java                 |
| -                                        | -              | -             | -           | -      | -           | -           | -            | -                                                                                            |
| -                                        | -              | -             | -           | -      | -           | -           | -            | -                                                                                            |
| -                                        | -              | -             | -           | -      | -           | -           | -            | -                                                                                            |
| -                                        | -              | -             | -           | -      | -           | -           | -            | -                                                                                            |
| -                                        | -              | -             | -           | -      | -           | -           | -            | -                                                                                            |

## Project 3: _apache/sling-org-apache-sling-commons-html_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-commons-html.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-commons-html) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-commons-html) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-commons-html.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                 | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                                         |
|:---------------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:-----------------------------------------------------------------------------------|
| TagParser.java             | 26             | 0             | 8           | 0      | 3           | 0           | 15           | src/main/java/org/apache/sling/commons/html/impl/parser/TagParser.java             |
| Token.java                 | 8              | 0             | 0           | 0      | 8           | 0           | 0            | src/main/java/org/apache/sling/commons/html/impl/parser/Token.java                 |
| ParseException.java        | 7              | 0             | 4           | 0      | 3           | 0           | 0            | src/main/java/org/apache/sling/commons/html/impl/parser/ParseException.java        |
| SimpleCharStream.java      | 4              | 0             | 1           | 0      | 3           | 0           | 0            | src/main/java/org/apache/sling/commons/html/impl/parser/SimpleCharStream.java      |
| TokenMgrError.java         | 3              | 2             | 1           | 0      | 0           | 0           | 0            | src/main/java/org/apache/sling/commons/html/impl/parser/TokenMgrError.java         |
| TagParserTokenManager.java | 2              | 0             | 1           | 0      | 1           | 0           | 0            | src/main/java/org/apache/sling/commons/html/impl/parser/TagParserTokenManager.java |
| StartTag.java              | 1              | 1             | 0           | 0      | 0           | 0           | 0            | src/main/java/org/apache/sling/commons/html/impl/tag/StartTag.java                 |
| -                          | -              | -             | -           | -      | -           | -           | -            | -                                                                                  |
| -                          | -              | -             | -           | -      | -           | -           | -            | -                                                                                  |
| -                          | -              | -             | -           | -      | -           | -           | -            | -                                                                                  |

## Project 4: _apache/sling-org-apache-sling-commons-jcr-file_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-commons-jcr-file.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-commons-jcr-file) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-commons-jcr-file) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-commons-jcr-file.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                 | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                                          |
|:---------------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:------------------------------------------------------------------------------------|
| JcrFile.java               | 2              | 0             | 2           | 0      | 0           | 0           | 0            | src/main/java/org/apache/sling/commons/jcr/file/internal/JcrFile.java               |
| JcrFileSystemProvider.java | 1              | 1             | 0           | 0      | 0           | 0           | 0            | src/main/java/org/apache/sling/commons/jcr/file/internal/JcrFileSystemProvider.java |
| JcrFileChannel.java        | 1              | 0             | 1           | 0      | 0           | 0           | 0            | src/main/java/org/apache/sling/commons/jcr/file/internal/JcrFileChannel.java        |
| JcrFileAttributes.java     | 1              | 0             | 0           | 0      | 1           | 0           | 0            | src/main/java/org/apache/sling/commons/jcr/file/internal/JcrFileAttributes.java     |
| PathUtil.java              | 1              | 0             | 0           | 0      | 1           | 0           | 0            | src/main/java/org/apache/sling/commons/jcr/file/internal/PathUtil.java              |
| JcrDirectoryStream.java    | 1              | 0             | 1           | 0      | 0           | 0           | 0            | src/main/java/org/apache/sling/commons/jcr/file/internal/JcrDirectoryStream.java    |
| -                          | -              | -             | -           | -      | -           | -           | -            | -                                                                                   |
| -                          | -              | -             | -           | -      | -           | -           | -            | -                                                                                   |
| -                          | -              | -             | -           | -      | -           | -           | -            | -                                                                                   |
| -                          | -              | -             | -           | -      | -           | -           | -            | -                                                                                   |

## Project 5: _apache/sling-org-apache-sling-commons-metrics_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-commons-metrics.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-commons-metrics) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-commons-metrics) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-commons-metrics.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                 | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                                       |
|:---------------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:---------------------------------------------------------------------------------|
| MetricsServiceImpl.java    | 2              | 0             | 2           | 0      | 0           | 0           | 0            | src/main/java/org/apache/sling/commons/metrics/internal/MetricsServiceImpl.java  |
| BundleMetricsMapper.java   | 1              | 0             | 1           | 0      | 0           | 0           | 0            | src/main/java/org/apache/sling/commons/metrics/internal/BundleMetricsMapper.java |
| MetricsServiceFactory.java | 1              | 0             | 0           | 0      | 1           | 0           | 0            | src/main/java/org/apache/sling/commons/metrics/MetricsServiceFactory.java        |
| JSONReporter.java          | 1              | 0             | 1           | 0      | 0           | 0           | 0            | src/main/java/org/apache/sling/commons/metrics/internal/JSONReporter.java        |
| JmxUtil.java               | 1              | 0             | 0           | 0      | 1           | 0           | 0            | src/main/java/org/apache/sling/commons/metrics/internal/JmxUtil.java             |
| -                          | -              | -             | -           | -      | -           | -           | -            | -                                                                                |
| -                          | -              | -             | -           | -      | -           | -           | -            | -                                                                                |
| -                          | -              | -             | -           | -      | -           | -           | -            | -                                                                                |
| -                          | -              | -             | -           | -      | -           | -           | -            | -                                                                                |
| -                          | -              | -             | -           | -      | -           | -           | -            | -                                                                                |

## Project 6: _apache/sling-org-apache-sling-i18n_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-i18n.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-i18n) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-i18n) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-i18n.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                     | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                              |
|:-------------------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:------------------------------------------------------------------------|
| JcrResourceBundleProvider.java | 3              | 0             | 1           | 0      | 2           | 0           | 0            | src/main/java/org/apache/sling/i18n/impl/JcrResourceBundleProvider.java |
| JcrResourceBundle.java         | 1              | 1             | 0           | 0      | 0           | 0           | 0            | src/main/java/org/apache/sling/i18n/impl/JcrResourceBundle.java         |
| LocaleResolver.java            | 1              | 0             | 0           | 0      | 1           | 0           | 0            | src/main/java/org/apache/sling/i18n/LocaleResolver.java                 |
| -                              | -              | -             | -           | -      | -           | -           | -            | -                                                                       |
| -                              | -              | -             | -           | -      | -           | -           | -            | -                                                                       |
| -                              | -              | -             | -           | -      | -           | -           | -            | -                                                                       |
| -                              | -              | -             | -           | -      | -           | -           | -            | -                                                                       |
| -                              | -              | -             | -           | -      | -           | -           | -            | -                                                                       |
| -                              | -              | -             | -           | -      | -           | -           | -            | -                                                                       |
| -                              | -              | -             | -           | -      | -           | -           | -            | -                                                                       |

## Project 7: _apache/sling-org-apache-sling-jcr-contentloader_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-jcr-contentloader.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-jcr-contentloader) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-jcr-contentloader) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-jcr-contentloader.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name               | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                                         |
|:-------------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:-----------------------------------------------------------------------------------|
| XmlReader.java           | 14             | 0             | 3           | 0      | 10          | 1           | 0            | src/main/java/org/apache/sling/jcr/contentloader/internal/readers/XmlReader.java   |
| PathEntry.java           | 3              | 3             | 0           | 0      | 0           | 0           | 0            | src/main/java/org/apache/sling/jcr/contentloader/internal/PathEntry.java           |
| ContentTypeUtil.java     | 1              | 0             | 0           | 0      | 1           | 0           | 0            | src/main/java/org/apache/sling/jcr/contentloader/ContentTypeUtil.java              |
| ImportOptions.java       | 1              | 0             | 0           | 0      | 1           | 0           | 0            | src/main/java/org/apache/sling/jcr/contentloader/ImportOptions.java                |
| BundleContentLoader.java | 1              | 0             | 0           | 0      | 1           | 0           | 0            | src/main/java/org/apache/sling/jcr/contentloader/internal/BundleContentLoader.java |
| -                        | -              | -             | -           | -      | -           | -           | -            | -                                                                                  |
| -                        | -              | -             | -           | -      | -           | -           | -            | -                                                                                  |
| -                        | -              | -             | -           | -      | -           | -           | -            | -                                                                                  |
| -                        | -              | -             | -           | -      | -           | -           | -            | -                                                                                  |
| -                        | -              | -             | -           | -      | -           | -           | -            | -                                                                                  |

## Project 8: _apache/sling-org-apache-sling-jcr-repoinit_
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

## Project 9: _apache/sling-org-apache-sling-pipes_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-pipes.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-pipes) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-pipes) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-pipes.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name             |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified class name                                           |
|:-----------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------|
| GogoCommands.java      |              7 |             0 |           1 |      0 |           0 |           0 |            6 | src/main/java/org/apache/sling/pipes/internal/GogoCommands.java      |
| JsonUtil.java          |              5 |             0 |           4 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/pipes/internal/JsonUtil.java          |
| PlumberImpl.java       |              4 |             0 |           4 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/pipes/internal/PlumberImpl.java       |
| MultiPropertyPipe.java |              4 |             0 |           2 |      0 |           0 |           0 |            2 | src/main/java/org/apache/sling/pipes/internal/MultiPropertyPipe.java |
| PipeBuilder.java       |              4 |             0 |           4 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/pipes/PipeBuilder.java                |
| CommandUtil.java       |              2 |             0 |           1 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/pipes/internal/CommandUtil.java       |
| SuperPipe.java         |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/pipes/SuperPipe.java                  |
| Plumber.java           |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/pipes/Plumber.java                    |
| Pipe.java              |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/pipes/Pipe.java                       |
| ReferencePipe.java     |              2 |             0 |           2 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/pipes/internal/ReferencePipe.java     |

