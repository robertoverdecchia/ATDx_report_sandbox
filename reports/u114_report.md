
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="./plots/apache_sling-kickstart-maven-plugin.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-kickstart-maven-plugin) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-kickstart-maven-plugin) <br> [Complete issue report (JSON)](./json/apache_sling-kickstart-maven-plugin.json)</p>|<img src="./plots/apache_sling-org-apache-sling-scripting-core.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-scripting-core) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-scripting-core) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-scripting-core.json)</p>|<img src="./plots/apache_sling-org-apache-sling-servlets-resolver.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-servlets-resolver) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-servlets-resolver) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-servlets-resolver.json)</p>
 | |

# Project report summaries
## Project: _apache/sling-kickstart-maven-plugin_
|./plots/apache_sling-kickstart-maven-plugin.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-kickstart-maven-plugin) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-kickstart-maven-plugin) <br> [Complete issue report (JSON)](./json/apache_sling-kickstart-maven-plugin.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                      |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                               |
|:--------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------------------------|
| LauncherCallable.java           |              7 |             0 |           7 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/maven/kickstart/run/LauncherCallable.java           |
| ProcessDescriptionProvider.java |              4 |             0 |           4 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/maven/kickstart/run/ProcessDescriptionProvider.java |
| StartMojo.java                  |              3 |             0 |           2 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/maven/kickstart/run/StartMojo.java                  |

## Project: _apache/sling-org-apache-sling-scripting-core_
|./plots/apache_sling-org-apache-sling-scripting-core.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-scripting-core) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-scripting-core) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-scripting-core.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                                    |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:---------------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| src/main/java/org/apache/sling/scripting/core/impl/bundled/Script.java                       |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/scripting/core/impl/bundled/PrecompiledScript.java            |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/scripting/core/impl/InternalScriptHelper.java                 |             1 |           0 |         0 |           0 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/scripting/core/impl/BindingsValuesProvidersByContextImpl.java |             0 |           0 |         0 |           0 |           0 |            0 |     0 |

## Project: _apache/sling-org-apache-sling-servlets-resolver_
|./plots/apache_sling-org-apache-sling-servlets-resolver.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-servlets-resolver) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-servlets-resolver) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-servlets-resolver.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                                                     |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:--------------------------------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| src/main/java/org/apache/sling/servlets/resolver/internal/helper/LocationIterator.java                        |             1 |           0 |         0 |           0 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/servlets/resolver/internal/resolution/ResolutionCache.java                     |             0 |           1 |         0 |           0 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/servlets/resolver/bundle/tracker/internal/BundledRenderUnitCapabilityImpl.java |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/servlets/resolver/internal/helper/ResourceCollector.java                       |             0 |           0 |         0 |           1 |           0 |            0 |     1 |

