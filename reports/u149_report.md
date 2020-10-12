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
|||
|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/JMeter.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/jmeter) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=JMeter) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/JMeter.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/commons-compress.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/commons-compress) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=commons-compress) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/commons-compress.json)</p>
# Project report summaries
## Project: _apache/jmeter_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/JMeter.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/jmeter) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=JMeter) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/JMeter.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                     |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified class name                                                                        |
|:-------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:--------------------------------------------------------------------------------------------------|
| LoggingManager.java            |             16 |             0 |           0 |      0 |          16 |           0 |            0 | src/jorphan/src/main/java/org/apache/jorphan/logging/LoggingManager.java                          |
| SampleResult.java              |             10 |             1 |           0 |      0 |           9 |           0 |            0 | src/core/src/main/java/org/apache/jmeter/samplers/SampleResult.java                               |
| Logger.java                    |             10 |             0 |           0 |      0 |          10 |           0 |            0 | src/jorphan/src/main/java/org/apache/log/Logger.java                                              |
| JMeterUtils.java               |              8 |             0 |           5 |      0 |           3 |           0 |            0 | src/core/src/main/java/org/apache/jmeter/util/JMeterUtils.java                                    |
| XMLDefaultMutableTreeNode.java |              5 |             0 |           4 |      0 |           1 |           0 |            0 | src/components/src/main/java/org/apache/jmeter/visualizers/XMLDefaultMutableTreeNode.java         |
| PreciseThroughputTimer.java    |              5 |             1 |           0 |      0 |           4 |           0 |            0 | src/components/src/main/java/org/apache/jmeter/timers/poissonarrivals/PreciseThroughputTimer.java |
| TableEditor.java               |              5 |             0 |           5 |      0 |           0 |           0 |            0 | src/core/src/main/java/org/apache/jmeter/testbeans/gui/TableEditor.java                           |
| TestBeanGUI.java               |              4 |             0 |           3 |      0 |           1 |           0 |            0 | src/core/src/main/java/org/apache/jmeter/testbeans/gui/TestBeanGUI.java                           |
| JMeterContext.java             |              4 |             0 |           0 |      0 |           4 |           0 |            0 | src/core/src/main/java/org/apache/jmeter/threads/JMeterContext.java                               |
| HTTPSamplerBase.java           |              4 |             0 |           0 |      0 |           4 |           0 |            0 | src/protocol/http/src/main/java/org/apache/jmeter/protocol/http/sampler/HTTPSamplerBase.java      |

## Project: _apache/commons-compress_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/commons-compress.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/commons-compress) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=commons-compress) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/commons-compress.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                       |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified class name                                                                   |
|:---------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------------------|
| SevenZFile.java                  |             17 |             0 |           3 |      0 |           3 |           0 |           11 | src/main/java/org/apache/commons/compress/archivers/sevenz/SevenZFile.java                   |
| Charsets.java                    |              7 |             0 |           0 |      0 |           7 |           0 |            0 | src/main/java/org/apache/commons/compress/utils/Charsets.java                                |
| TarArchiveOutputStream.java      |              5 |             0 |           1 |      0 |           4 |           0 |            0 | src/main/java/org/apache/commons/compress/archivers/tar/TarArchiveOutputStream.java          |
| TarArchiveEntry.java             |              5 |             0 |           0 |      0 |           2 |           0 |            3 | src/main/java/org/apache/commons/compress/archivers/tar/TarArchiveEntry.java                 |
| SevenZArchiveEntry.java          |              4 |             0 |           0 |      0 |           4 |           0 |            0 | src/main/java/org/apache/commons/compress/archivers/sevenz/SevenZArchiveEntry.java           |
| BZip2CompressorOutputStream.java |              3 |             1 |           0 |      0 |           0 |           0 |            2 | src/main/java/org/apache/commons/compress/compressors/bzip2/BZip2CompressorOutputStream.java |
| LocalFileHeader.java             |              3 |             0 |           0 |      0 |           3 |           0 |            0 | src/main/java/org/apache/commons/compress/archivers/arj/LocalFileHeader.java                 |
| Expander.java                    |              3 |             0 |           0 |      0 |           3 |           0 |            0 | src/main/java/org/apache/commons/compress/archivers/examples/Expander.java                   |
| JarArchiveEntry.java             |              2 |             0 |           0 |      0 |           2 |           0 |            0 | src/main/java/org/apache/commons/compress/archivers/jar/JarArchiveEntry.java                 |
| ZipArchiveEntry.java             |              2 |             1 |           1 |      0 |           0 |           0 |            0 | src/main/java/org/apache/commons/compress/archivers/zip/ZipArchiveEntry.java                 |

