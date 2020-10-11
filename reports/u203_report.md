
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
|||
|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/commons-compress.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/commons-compress) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=commons-compress) <br> [Complete issue report (JSON)](./json/commons-compress.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/cxf.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/cxf) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=cxf) <br> [Complete issue report (JSON)](./json/cxf.json)</p>
# Project report summaries
## Project: _apache/commons-compress_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/commons-compress.jpg/>|<p style="text-align:left">[Project on Github](https://github.com/apache/commons-compress) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=commons-compress) <br> [Complete issue report (JSON)](./json/commons-compress.json)</p>
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

## Project: _apache/cxf_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/cxf.jpg/>|<p style="text-align:left">[Project on Github](https://github.com/apache/cxf) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=cxf) <br> [Complete issue report (JSON)](./json/cxf.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                    |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                                                        |
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

