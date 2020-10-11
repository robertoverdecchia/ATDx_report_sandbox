
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="./plots/apache_sling-jspc-maven-plugin.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-jspc-maven-plugin) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-jspc-maven-plugin) <br> [Complete issue report (JSON)](./json/apache_sling-jspc-maven-plugin.json)</p>|<img src="./plots/apache_sling-org-apache-sling-commons-scheduler.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-commons-scheduler) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-commons-scheduler) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-commons-scheduler.json)</p>|<img src="./plots/apache_sling-org-apache-sling-feature-analyser.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-feature-analyser) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-feature-analyser) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-feature-analyser.json)</p>
 | |
|<img src="./plots/apache_sling-org-apache-sling-feature.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-feature) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-feature) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-feature.json)</p>|<img src="./plots/apache_sling-org-apache-sling-scripting-core.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-scripting-core) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-scripting-core) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-scripting-core.json)</p>|<img src="./plots/apache_sling-org-apache-sling-scripting-jsp.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-scripting-jsp) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-scripting-jsp) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-scripting-jsp.json)</p>
 | |
|<img src="./plots/apache_sling-org-apache-sling-scripting-sightly-js-provider.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-scripting-sightly-js-provider) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-scripting-sightly-js-provider) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-scripting-sightly-js-provider.json)</p>|<img src="./plots/apache_sling-org-apache-sling-scripting-sightly.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-scripting-sightly) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-scripting-sightly) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-scripting-sightly.json)</p>|<img src="./plots/apache_sling-org-apache-sling-serviceusermapper.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-serviceusermapper) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-serviceusermapper) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-serviceusermapper.json)</p>

# Project report summaries
## Project: _apache/sling-jspc-maven-plugin_
|./plots/apache_sling-jspc-maven-plugin.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-jspc-maven-plugin) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-jspc-maven-plugin) <br> [Complete issue report (JSON)](./json/apache_sling-jspc-maven-plugin.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name              |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                              |
|:------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:------------------------------------------------------------------|
| JspCServletContext.java |              4 |             0 |           0 |      0 |           4 |           0 |            0 | src/main/java/org/apache/sling/maven/jspc/JspCServletContext.java |
| JspcMojo.java           |              3 |             0 |           2 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/maven/jspc/JspcMojo.java           |

## Project: _apache/sling-org-apache-sling-commons-scheduler_
|./plots/apache_sling-org-apache-sling-commons-scheduler.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-commons-scheduler) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-commons-scheduler) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-commons-scheduler.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                   |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                               |
|:-----------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------------------------|
| Scheduler.java               |             14 |             0 |           6 |      0 |           8 |           0 |            0 | src/main/java/org/apache/sling/commons/scheduler/Scheduler.java                    |
| WebConsolePrinter.java       |              9 |             0 |           0 |      0 |           9 |           0 |            0 | src/main/java/org/apache/sling/commons/scheduler/impl/WebConsolePrinter.java       |
| InternalScheduleOptions.java |              6 |             0 |           0 |      0 |           6 |           0 |            0 | src/main/java/org/apache/sling/commons/scheduler/impl/InternalScheduleOptions.java |
| QuartzScheduler.java         |              4 |             0 |           2 |      0 |           2 |           0 |            0 | src/main/java/org/apache/sling/commons/scheduler/impl/QuartzScheduler.java         |

## Project: _apache/sling-org-apache-sling-feature-analyser_
|./plots/apache_sling-org-apache-sling-feature-analyser.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-feature-analyser) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-feature-analyser) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-feature-analyser.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                     |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                     |
|:-------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------------------------------|
| CheckBundleExportsImports.java |              6 |             0 |           0 |      0 |           6 |           0 |            0 | src/main/java/org/apache/sling/feature/analyser/task/impl/CheckBundleExportsImports.java |

## Project: _apache/sling-org-apache-sling-feature_
|./plots/apache_sling-org-apache-sling-feature.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-feature) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-feature) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-feature.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name            |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                            |
|:----------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------|
| ConfiguratorUtil.java |              3 |             0 |           2 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/feature/io/ConfiguratorUtil.java |
| Extension.java        |              3 |             0 |           0 |      0 |           3 |           0 |            0 | src/main/java/org/apache/sling/feature/Extension.java           |

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

## Project: _apache/sling-org-apache-sling-scripting-jsp_
|./plots/apache_sling-org-apache-sling-scripting-jsp.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-scripting-jsp) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-scripting-jsp) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-scripting-jsp.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name               |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                   |
|:-------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------------|
| PageDataImpl.java        |             34 |            33 |           1 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/scripting/jsp/jasper/compiler/PageDataImpl.java         |
| Dumper.java              |             22 |            21 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/scripting/jsp/jasper/compiler/Dumper.java               |
| Collector.java           |             14 |            13 |           0 |      0 |           1 |           0 |            0 | src/main/java/org/apache/sling/scripting/jsp/jasper/compiler/Collector.java            |
| ELResolverImpl.java      |             13 |             0 |          13 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/scripting/jsp/jasper/el/ELResolverImpl.java             |
| JspValueExpression.java  |             13 |             0 |          13 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/scripting/jsp/jasper/el/JspValueExpression.java         |
| XMLEncodingDetector.java |             11 |             7 |           0 |      0 |           0 |           0 |            4 | src/main/java/org/apache/sling/scripting/jsp/jasper/xmlparser/XMLEncodingDetector.java |
| JspDocumentParser.java   |             11 |             8 |           1 |      0 |           2 |           0 |            0 | src/main/java/org/apache/sling/scripting/jsp/jasper/compiler/JspDocumentParser.java    |
| Generator.java           |             11 |             0 |          11 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/scripting/jsp/jasper/compiler/Generator.java            |
| ELFunctionMapper.java    |             11 |            11 |           0 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/scripting/jsp/jasper/compiler/ELFunctionMapper.java     |
| Compiler.java            |             10 |             0 |          10 |      0 |           0 |           0 |            0 | src/main/java/org/apache/sling/scripting/jsp/jasper/compiler/Compiler.java             |

## Project: _apache/sling-org-apache-sling-scripting-sightly-js-provider_
|./plots/apache_sling-org-apache-sling-scripting-sightly-js-provider.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-scripting-sightly-js-provider) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-scripting-sightly-js-provider) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-scripting-sightly-js-provider.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                           |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| src/main/java/org/apache/sling/scripting/sightly/js/impl/Variables.java             |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/scripting/sightly/js/impl/loop/EventLoopInterop.java |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/scripting/sightly/js/impl/rhino/JsUtils.java         |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/scripting/sightly/js/impl/Utils.java                 |             0 |           0 |         0 |           1 |           0 |            0 |     1 |

## Project: _apache/sling-org-apache-sling-scripting-sightly_
|./plots/apache_sling-org-apache-sling-scripting-sightly.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-scripting-sightly) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-scripting-sightly) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-scripting-sightly.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                                  |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:-------------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| src/main/java/org/apache/sling/scripting/sightly/impl/engine/extension/ExtensionUtils.java |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/scripting/sightly/impl/utils/BindingsUtils.java             |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/scripting/sightly/impl/utils/ScriptUtils.java               |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/scripting/sightly/engine/ResourceResolution.java            |             0 |           0 |         0 |           1 |           0 |            0 |     1 |

## Project: _apache/sling-org-apache-sling-serviceusermapper_
|./plots/apache_sling-org-apache-sling-serviceusermapper.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/sling-org-apache-sling-serviceusermapper) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-serviceusermapper) <br> [Complete issue report (JSON)](./json/apache_sling-org-apache-sling-serviceusermapper.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                                 |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:------------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| src/main/java/org/apache/sling/serviceusermapping/impl/MappingConfigAmendment.java        |             1 |           0 |         0 |           0 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/serviceusermapping/impl/ServiceUserMappedImpl.java         |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| src/main/java/org/apache/sling/serviceusermapping/impl/ServiceUserMappedBundleFilter.java |             0 |           1 |         0 |           0 |           0 |            0 |     1 |

