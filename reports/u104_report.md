
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="./plots/apache_sling-org-apache-sling-feature-io.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-feature-io) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-feature-io) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-feature-io.json)</p>|<img src="./plots/apache_sling-org-apache-sling-installer-core.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-installer-core) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-installer-core) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-installer-core.json)</p>|<img src="./plots/apache_sling-org-apache-sling-installer-provider-jcr.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-installer-provider-jcr) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-installer-provider-jcr) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-installer-provider-jcr.json)</p>
 | |

# Project report summaries
## Project: _apache/sling-org-apache-sling-feature-io_
|./plots/apache_sling-org-apache-sling-feature-io.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-feature-io) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-feature-io) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-feature-io.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name            |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                            |
|:----------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------|
| ConfiguratorUtil.java |              3 |             0 |           2 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/feature/io/ConfiguratorUtil.java |

## Project: _apache/sling-org-apache-sling-installer-core_
|./plots/apache_sling-org-apache-sling-installer-core.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-installer-core) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-installer-core) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-installer-core.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name             |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                      |
|:-----------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:--------------------------------------------------------------------------|
| OsgiInstallerImpl.java |              5 |             0 |           0 |      0 |           5 |           0 |            0 | src/main/java/org/apache/sling/installer/core/impl/OsgiInstallerImpl.java |
| Util.java              |              4 |             0 |           0 |      0 |           4 |           0 |            0 | src/main/java/org/apache/sling/installer/core/impl/Util.java              |

## Project: _apache/sling-org-apache-sling-installer-provider-jcr_
|./plots/apache_sling-org-apache-sling-installer-provider-jcr.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-installer-provider-jcr) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-installer-provider-jcr) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-installer-provider-jcr.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                         |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:----------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| src/main/java/org/apache/sling/installer/provider/jcr/impl/JcrInstaller.java      |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/installer/provider/jcr/impl/FileNodeConverter.java |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/installer/provider/jcr/impl/JcrUtil.java           |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/installer/provider/jcr/impl/WatchedFolder.java     |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/installer/provider/jcr/impl/FolderNameFilter.java  |             1 |           0 |         0 |           0 |           0 |            0 |     1 |

