
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
|||
|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/ant-master.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/ant) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=ant-master) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/ant-master.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/commons-compress.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/commons-compress) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=commons-compress) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/commons-compress.json)</p>
# Project report summaries
## Project: _apache/ant_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/ant-master.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/ant) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=ant-master) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/ant-master.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name               |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                       |
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

