# ATDx Report Summary
Our ATDx analysis targets a portfolio of software projects and identifies the pain points of each project in terms of Architectural Technical Debt (ATD). This evaluation is based on a statistical analysis of the violations of SonarCloud rules.

ATDx provides an overview of the architectural technical debt in a project  in 6 distinct dimensions:
* **Inheritance**: flaws concerning inheritance mechanisms between classes, such as overrides and inheritance of methods or fields
* **Exception**: flaws regarding the management of Java exceptions and the subclassing of the “Exception” Java class.
* **JVMS**: potential misuses of the Java Virtual Machine, e.g., the incorrect usage of the specific Java class “Serializable”
* **Threading**: flaws arising from the implementation of multiple execution threads, which could potentially lead to concurrency problems
* **Interface**: flaws related to the usage of Java interfaces
* **Complexity**: flaws derived from prominent complexity measures, such as McCabe’s cyclomatic complexity

For each project, the dimensions assume a value between 0 and 5, where 0 denotes minimum architectural debt of the project in that dimension, and 5 maximum architectural debt.

In the reminder of this report, we firstly provide a set of radar charts (one for each project). Then for each project we give:
1. The same radar chart as shown at the beginning
2. A table showing the top-10 classes of the project with the highest architectural technical debt.

Note that if numerous classes with 1 violation are reported, this might point to a widespread problem (only a maximum of 10 classes are provided per project for the sake of readability). Similarly, empty rows indicate that only a few classes are affected by ATDx violations.

## Radar charts
|||
|-|-|
|<p align="center">Project 1</p><img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/commons-compress.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/commons-compress) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=commons-compress) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/commons-compress.json)</p>|<p align="center">Project 2</p><img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/cxf.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/cxf) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=cxf) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/cxf.json)</p>
# Project report summaries
## Project 1: _apache/commons-compress_
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

## Project 2: _apache/cxf_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/cxf.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/cxf) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=cxf) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/cxf.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                    |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified class name                                                                                                  |
|:------------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:----------------------------------------------------------------------------------------------------------------------------|
| IDLLexer.java                 |            196 |             0 |          38 |      0 |           0 |           0 |          158 | tools/corba/src/main/generated/org/apache/cxf/tools/corba/processors/idl/IDLLexer.java                                      |
| ASMHelper.java                |             55 |             0 |           5 |      0 |          50 |           0 |            0 | core/src/main/java/org/apache/cxf/common/util/ASMHelper.java                                                                |
| UriBuilderImpl.java           |             46 |             2 |          42 |      0 |           2 |           0 |            0 | rt/frontend/jaxrs/src/main/java/org/apache/cxf/jaxrs/impl/UriBuilderImpl.java                                               |
| AbstractDelegatingLogger.java |             40 |            36 |           0 |      0 |           4 |           0 |            0 | core/src/main/java/org/apache/cxf/common/logging/AbstractDelegatingLogger.java                                              |
| CorbaObjectReader.java        |             37 |             0 |          25 |      0 |           0 |           0 |           12 | rt/bindings/corba/src/main/java/org/apache/cxf/binding/corba/runtime/CorbaObjectReader.java                                 |
| CryptoUtils.java              |             34 |             0 |          32 |      0 |           2 |           0 |            0 | rt/security/src/main/java/org/apache/cxf/rt/security/crypto/CryptoUtils.java                                                |
| StaxUtils.java                |             28 |             0 |          23 |      0 |           1 |           0 |            4 | core/src/main/java/org/apache/cxf/staxutils/StaxUtils.java                                                                  |
| ModelEncryptionSupport.java   |             28 |             0 |          28 |      0 |           0 |           0 |            0 | rt/rs/security/oauth-parent/oauth2/src/main/java/org/apache/cxf/rs/security/oauth2/utils/crypto/ModelEncryptionSupport.java |
| JAXBDataBinding.java          |             25 |            15 |          10 |      0 |           0 |           0 |            0 | tools/wsdlto/databinding/jaxb/src/main/java/org/apache/cxf/tools/wsdlto/databinding/jaxb/JAXBDataBinding.java               |
| CorbaObjectWriter.java        |             23 |             0 |          23 |      0 |           0 |           0 |            0 | rt/bindings/corba/src/main/java/org/apache/cxf/binding/corba/runtime/CorbaObjectWriter.java                                 |

