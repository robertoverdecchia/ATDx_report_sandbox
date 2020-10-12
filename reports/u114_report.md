# ATDx Report Summary
Following the overview of the ATDx analysis of your projects.

In short, the ATDx analysis is based on software metrics aggregation, and statistical severity evaluation of the aggregated values across a portfolio of software projects.

ATDx provides an overview of the project Architectural Technical Debt (ATD) in 6 distinct dimensions:
* **Inheritance**: flaws concerning inheritance mechanisms between classes, such as overrides and inheritance of methods or fields
* **Exception**: flaws regarding the Java throwable class “Exception” and its subclasses
* **JVMS**: potential misuse of the Java Virtual Machine, e.g., the incorrect usage of the specific Java class “Serializable”
* **Threading**: flaws arising from the implementation of multiple execution threads, which could potentially lead to concurrency problems
* **Interface**: flaws related to the usage of Java interfaces
* **Complexity**: flaws derived from prominent complexity measures, such as McCabe’s cyclomatic complexity

For each project, an overview of the ATDx values is presented, followed by the top classes of the project contributing to the ATDx values.

Note that if numerous classes with 1 violation are reported, this might point to a widespread problematics (only a maximum of 10 classes are provided per project). Similarly, empty rows may indicate that only few classes are affected by ATDx violations.
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-kickstart-maven-plugin.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-kickstart-maven-plugin) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-kickstart-maven-plugin) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-kickstart-maven-plugin.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-scripting-core.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-scripting-core) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-scripting-core) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-scripting-core.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-servlets-resolver.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-servlets-resolver) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-servlets-resolver) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-servlets-resolver.json)</p>
 | |

# Project report summaries
## Project: _apache/sling-kickstart-maven-plugin_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-kickstart-maven-plugin.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-kickstart-maven-plugin) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-kickstart-maven-plugin) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-kickstart-maven-plugin.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                      | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                                         |
|:--------------------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:-----------------------------------------------------------------------------------|
| LauncherCallable.java           | 7              | 0             | 7           | 0      | 0           | 0           | 0            | src/main/java/org/apache/sling/maven/kickstart/run/LauncherCallable.java           |
| ProcessDescriptionProvider.java | 4              | 0             | 4           | 0      | 0           | 0           | 0            | src/main/java/org/apache/sling/maven/kickstart/run/ProcessDescriptionProvider.java |
| StartMojo.java                  | 3              | 0             | 2           | 0      | 1           | 0           | 0            | src/main/java/org/apache/sling/maven/kickstart/run/StartMojo.java                  |
| BuildConstants.java             | 1              | 0             | 0           | 0      | 1           | 0           | 0            | src/main/java/org/apache/sling/maven/kickstart/BuildConstants.java                 |
| PortHelper.java                 | 1              | 0             | 0           | 0      | 1           | 0           | 0            | src/main/java/org/apache/sling/maven/kickstart/run/PortHelper.java                 |
| ProcessDescription.java         | 1              | 0             | 1           | 0      | 0           | 0           | 0            | src/main/java/org/apache/sling/maven/kickstart/run/ProcessDescription.java         |
| Main.java                       | 1              | 0             | 1           | 0      | 0           | 0           | 0            | src/main/java/org/apache/sling/maven/kickstart/launcher/Main.java                  |
| -                               | -              | -             | -           | -      | -           | -           | -            | -                                                                                  |
| -                               | -              | -             | -           | -      | -           | -           | -            | -                                                                                  |
| -                               | -              | -             | -           | -      | -           | -           | -            | -                                                                                  |

## Project: _apache/sling-org-apache-sling-scripting-core_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-scripting-core.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-scripting-core) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-scripting-core) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-scripting-core.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                                        |
|:--------------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:----------------------------------------------------------------------------------|
| ServiceCache.java         | 2              | 0             | 0           | 0      | 2           | 0           | 0            | src/main/java/org/apache/sling/scripting/core/impl/ServiceCache.java              |
| ScriptHelper.java         | 2              | 0             | 1           | 0      | 1           | 0           | 0            | src/main/java/org/apache/sling/scripting/core/ScriptHelper.java                   |
| Script.java               | 1              | 0             | 0           | 0      | 1           | 0           | 0            | src/main/java/org/apache/sling/scripting/core/impl/bundled/Script.java            |
| PrecompiledScript.java    | 1              | 0             | 0           | 0      | 1           | 0           | 0            | src/main/java/org/apache/sling/scripting/core/impl/bundled/PrecompiledScript.java |
| InternalScriptHelper.java | 1              | 1             | 0           | 0      | 0           | 0           | 0            | src/main/java/org/apache/sling/scripting/core/impl/InternalScriptHelper.java      |
| -                         | -              | -             | -           | -      | -           | -           | -            | -                                                                                 |
| -                         | -              | -             | -           | -      | -           | -           | -            | -                                                                                 |
| -                         | -              | -             | -           | -      | -           | -           | -            | -                                                                                 |
| -                         | -              | -             | -           | -      | -           | -           | -            | -                                                                                 |
| -                         | -              | -             | -           | -      | -           | -           | -            | -                                                                                 |

## Project: _apache/sling-org-apache-sling-servlets-resolver_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/apache_sling-org-apache-sling-servlets-resolver.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-servlets-resolver) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-servlets-resolver) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/apache_sling-org-apache-sling-servlets-resolver.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                           | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                                                                    |
|:-------------------------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:--------------------------------------------------------------------------------------------------------------|
| SlingScriptResolverImpl.java         | 2              | 0             | 1           | 0      | 1           | 0           | 0            | src/main/java/org/apache/sling/servlets/resolver/internal/SlingScriptResolverImpl.java                        |
| ScriptResourceResolver.java          | 2              | 2             | 0           | 0      | 0           | 0           | 0            | src/main/java/org/apache/sling/servlets/resolver/internal/ScriptResourceResolver.java                         |
| LocationIterator.java                | 1              | 1             | 0           | 0      | 0           | 0           | 0            | src/main/java/org/apache/sling/servlets/resolver/internal/helper/LocationIterator.java                        |
| ResolutionCache.java                 | 1              | 0             | 1           | 0      | 0           | 0           | 0            | src/main/java/org/apache/sling/servlets/resolver/internal/resolution/ResolutionCache.java                     |
| BundledRenderUnitCapabilityImpl.java | 1              | 0             | 0           | 0      | 1           | 0           | 0            | src/main/java/org/apache/sling/servlets/resolver/bundle/tracker/internal/BundledRenderUnitCapabilityImpl.java |
| ResourceCollector.java               | 1              | 0             | 0           | 0      | 1           | 0           | 0            | src/main/java/org/apache/sling/servlets/resolver/internal/helper/ResourceCollector.java                       |
| -                                    | -              | -             | -           | -      | -           | -           | -            | -                                                                                                             |
| -                                    | -              | -             | -           | -      | -           | -           | -            | -                                                                                                             |
| -                                    | -              | -             | -           | -      | -           | -           | -            | -                                                                                                             |
| -                                    | -              | -             | -           | -      | -           | -           | -            | -                                                                                                             |

