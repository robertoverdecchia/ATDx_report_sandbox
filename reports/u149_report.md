
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
|||
|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/JMeter.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/jmeter) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=JMeter) <br> [Complete issue report (JSON)](./json/JMeter.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/commons-compress.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/commons-compress) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=commons-compress) <br> [Complete issue report (JSON)](./json/commons-compress.json)</p>
# Project report summaries
## Project: _apache/jmeter_
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/JMeter.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/jmeter) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=JMeter) <br> [Complete issue report (JSON)](./json/JMeter.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                     |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                              |
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
|https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/commons-compress.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/commons-compress) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=commons-compress) <br> [Complete issue report (JSON)](./json/commons-compress.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                       |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                         |
|:---------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------------------|
| SevenZFile.java                  |             17 |             0 |           3 |      0 |           3 |           0 |           11 | src/main/java/org/apache/commons/compress/archivers/sevenz/SevenZFile.java                   |
| Charsets.java                    |              7 |             0 |           0 |      0 |           7 |           0 |            0 | src/main/java/org/apache/commons/compress/utils/Charsets.java                                |
| TarArchiveOutputStream.java      |              5 |             0 |           1 |      0 |           4 |           0 |            0 | src/main/java/org/apache/commons/compress/archivers/tar/TarArchiveOutputStream.java          |
| TarArchiveEntry.java             |              5 |             0 |           0 |      0 |           2 |           0 |            3 | src/main/java/org/apache/commons/compress/archivers/tar/TarArchiveEntry.java                 |
| SevenZArchiveEntry.java          |              4 |             0 |           0 |      0 |           4 |           0 |            0 | src/main/java/org/apache/commons/compress/archivers/sevenz/SevenZArchiveEntry.java           |
| BZip2CompressorOutputStream.java |              3 |             1 |           0 |      0 |           0 |           0 |            2 | src/main/java/org/apache/commons/compress/compressors/bzip2/BZip2CompressorOutputStream.java |
| LocalFileHeader.java             |              3 |             0 |           0 |      0 |           3 |           0 |            0 | src/main/java/org/apache/commons/compress/archivers/arj/LocalFileHeader.java                 |
| Expander.java                    |              3 |             0 |           0 |      0 |           3 |           0 |            0 | src/main/java/org/apache/commons/compress/archivers/examples/Expander.java                   |

