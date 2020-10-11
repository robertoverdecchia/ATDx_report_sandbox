
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-kickstart-maven-plugin.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-kickstart-maven-plugin) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-kickstart-maven-plugin) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-kickstart-maven-plugin.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-scripting-core.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-scripting-core) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-scripting-core) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-scripting-core.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-servlets-resolver.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-servlets-resolver) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-servlets-resolver) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-servlets-resolver.json)</p>
 | |

# Project report summaries
## Project: _apache/sling-kickstart-maven-plugin_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-kickstart-maven-plugin.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-kickstart-maven-plugin) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-kickstart-maven-plugin) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-kickstart-maven-plugin.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                      |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                               |
|:--------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------------------------|
| LauncherCallable.java           |              7 |             0 |           7 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/maven/kickstart/run/LauncherCallable.java           |
| ProcessDescriptionProvider.java |              4 |             0 |           4 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/maven/kickstart/run/ProcessDescriptionProvider.java |
| StartMojo.java                  |              3 |             0 |           2 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/maven/kickstart/run/StartMojo.java                  |
| BuildConstants.java             |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/maven/kickstart/BuildConstants.java                 |
| PortHelper.java                 |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/maven/kickstart/run/PortHelper.java                 |
| ProcessDescription.java         |              1 |             0 |           1 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/maven/kickstart/run/ProcessDescription.java         |
| Main.java                       |              1 |             0 |           1 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/maven/kickstart/launcher/Main.java                  |

## Project: _apache/sling-org-apache-sling-scripting-core_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-scripting-core.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-scripting-core) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-scripting-core) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-scripting-core.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                              |
|:--------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------------------------|
| ServiceCache.java         |              2 |             0 |           0 |      0 |           2 |           0 |            0 | src/main/java/org/apache/sling/scripting/core/impl/ServiceCache.java              |
| ScriptHelper.java         |              2 |             0 |           1 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/scripting/core/ScriptHelper.java                   |
| Script.java               |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/scripting/core/impl/bundled/Script.java            |
| PrecompiledScript.java    |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/scripting/core/impl/bundled/PrecompiledScript.java |
| InternalScriptHelper.java |              1 |             1 |           0 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/scripting/core/impl/InternalScriptHelper.java      |

## Project: _apache/sling-org-apache-sling-servlets-resolver_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-servlets-resolver.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-servlets-resolver) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-servlets-resolver) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-servlets-resolver.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                           |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                          |
|:-------------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:--------------------------------------------------------------------------------------------------------------|
| SlingScriptResolverImpl.java         |              2 |             0 |           1 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/servlets/resolver/internal/SlingScriptResolverImpl.java                        |
| ScriptResourceResolver.java          |              2 |             2 |           0 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/servlets/resolver/internal/ScriptResourceResolver.java                         |
| LocationIterator.java                |              1 |             1 |           0 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/servlets/resolver/internal/helper/LocationIterator.java                        |
| ResolutionCache.java                 |              1 |             0 |           1 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/servlets/resolver/internal/resolution/ResolutionCache.java                     |
| BundledRenderUnitCapabilityImpl.java |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/servlets/resolver/bundle/tracker/internal/BundledRenderUnitCapabilityImpl.java |
| ResourceCollector.java               |              1 |             0 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/servlets/resolver/internal/helper/ResourceCollector.java                       |

