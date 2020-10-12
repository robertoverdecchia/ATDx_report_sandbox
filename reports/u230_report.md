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
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/ant-master.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/ant) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=ant-master) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/ant-master.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/commons-compress.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/commons-compress) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=commons-compress) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/commons-compress.json)</p>
# Project report summaries
## Project: _apache/ant_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/ant-master.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/ant) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=ant-master) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/ant-master.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name               |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified class name                                                 |
|:-------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------|
| Project.java             |             40 |             0 |          20 |      0 |          20 |           0 |            0 | src/main/org/apache/tools/ant/Project.java                                 |
| IntrospectionHelper.java |             21 |             0 |          20 |      0 |           1 |           0 |            0 | src/main/org/apache/tools/ant/IntrospectionHelper.java                     |
| FTP.java                 |             20 |             0 |          19 |      0 |           1 |           0 |            0 | src/main/org/apache/tools/ant/taskdefs/optional/net/FTP.java               |
| ProjectHelperImpl.java   |             17 |            16 |           1 |      0 |           0 |           0 |            0 | src/main/org/apache/tools/ant/helper/ProjectHelperImpl.java                |
| FTPTaskMirrorImpl.java   |             16 |             0 |          16 |      0 |           0 |           0 |            0 | src/main/org/apache/tools/ant/taskdefs/optional/net/FTPTaskMirrorImpl.java |
| PropertyHelper.java      |             16 |             0 |           5 |      0 |          11 |           0 |            0 | src/main/org/apache/tools/ant/PropertyHelper.java                          |
| FixCrLfFilter.java       |             16 |            15 |           1 |      0 |           0 |           0 |            0 | src/main/org/apache/tools/ant/filters/FixCrLfFilter.java                   |
| XSLTProcess.java         |             15 |             0 |          14 |      0 |           1 |           0 |            0 | src/main/org/apache/tools/ant/taskdefs/XSLTProcess.java                    |
| JUnitTask.java           |             14 |             0 |          10 |      0 |           4 |           0 |            0 | src/main/org/apache/tools/ant/taskdefs/optional/junit/JUnitTask.java       |
| ProjectHelper.java       |             14 |             0 |           9 |      0 |           5 |           0 |            0 | src/main/org/apache/tools/ant/ProjectHelper.java                           |

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

