
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-feature-cpconverter.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-feature-cpconverter) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-feature-cpconverter) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-feature-cpconverter.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-resourceresolver.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-resourceresolver) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-resourceresolver) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-resourceresolver.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-slingfeature-maven-plugin.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-slingfeature-maven-plugin) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-slingfeature-maven-plugin) <br> [Complete issue report (JSON)](./json/apache_sling-slingfeature-maven-plugin.json)</p>
 | |

# Project report summaries
## Project: _apache/sling-org-apache-sling-feature-cpconverter_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-feature-cpconverter.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-feature-cpconverter) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-feature-cpconverter) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-feature-cpconverter.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                   |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                   |
|:-----------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------------|
| BaseVaultPackageScanner.java |              3 |             0 |           3 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/feature/cpconverter/vltpkg/BaseVaultPackageScanner.java |

## Project: _apache/sling-org-apache-sling-resourceresolver_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-resourceresolver.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-resourceresolver) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-resourceresolver) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-resourceresolver.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                            |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                       |
|:--------------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-------------------------------------------------------------------------------------------|
| URI.java                              |             56 |             1 |          54 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/resourceresolver/impl/helper/URI.java                       |
| ResourceResolverFactoryActivator.java |              4 |             0 |           0 |      0 |           4 |           0 |            0 | src/main/java/org/apache/sling/resourceresolver/impl/ResourceResolverFactoryActivator.java |
| MapEntries.java                       |              3 |             0 |           3 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/resourceresolver/impl/mapping/MapEntries.java               |
| FactoryPreconditions.java             |              3 |             0 |           0 |      0 |           3 |           0 |            0 | src/main/java/org/apache/sling/resourceresolver/impl/FactoryPreconditions.java             |

## Project: _apache/sling-slingfeature-maven-plugin_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-slingfeature-maven-plugin.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-slingfeature-maven-plugin) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-slingfeature-maven-plugin) <br> [Complete issue report (JSON)](./json/apache_sling-slingfeature-maven-plugin.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name              |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                       |
|:------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------|
| ProjectHelper.java      |             16 |             0 |          15 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/feature/maven/ProjectHelper.java            |
| Aggregate.java          |             11 |             0 |           0 |      0 |          11 |           0 |            0 | src/main/java/org/apache/sling/feature/maven/mojos/Aggregate.java          |
| UpdateVersionsMojo.java |              9 |             0 |           1 |      0 |           8 |           0 |            0 | src/main/java/org/apache/sling/feature/maven/mojos/UpdateVersionsMojo.java |
| Preprocessor.java       |              7 |             0 |           7 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/feature/maven/Preprocessor.java             |
| Environment.java        |              4 |             0 |           0 |      0 |           4 |           0 |            0 | src/main/java/org/apache/sling/feature/maven/Environment.java              |
| FeatureProjectInfo.java |              4 |             0 |           0 |      0 |           4 |           0 |            0 | src/main/java/org/apache/sling/feature/maven/FeatureProjectInfo.java       |
| ApisJarMojo.java        |              3 |             0 |           3 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/feature/maven/mojos/ApisJarMojo.java        |

