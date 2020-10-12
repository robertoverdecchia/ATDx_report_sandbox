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
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/pdfbox-reactor.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/pdfbox) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=pdfbox-reactor) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/pdfbox-reactor.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/poi-parent.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/poi) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=poi-parent) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/poi-parent.json)</p>
# Project report summaries
## Project: _apache/pdfbox_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/pdfbox-reactor.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/pdfbox) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=pdfbox-reactor) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/pdfbox-reactor.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                   |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified class name                                                             |
|:-----------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:---------------------------------------------------------------------------------------|
| PDPageContentStream.java     |             34 |             0 |           0 |      0 |          34 |           0 |            0 | pdfbox/src/main/java/org/apache/pdfbox/pdmodel/PDPageContentStream.java                |
| CMapParser.java              |             17 |             0 |           0 |      0 |           0 |           0 |           17 | fontbox/src/main/java/org/apache/fontbox/cmap/CMapParser.java                          |
| PDFDebugger.java             |             13 |             0 |          12 |      0 |           1 |           0 |            0 | debugger/src/main/java/org/apache/pdfbox/debugger/PDFDebugger.java                     |
| CCITTFactory.java            |             12 |             0 |           0 |      0 |           0 |           0 |           12 | pdfbox/src/main/java/org/apache/pdfbox/pdmodel/graphics/image/CCITTFactory.java        |
| PDFStreamParser.java         |             10 |             0 |           0 |      0 |           0 |           0 |           10 | pdfbox/src/main/java/org/apache/pdfbox/pdfparser/PDFStreamParser.java                  |
| BaseParser.java              |              8 |             0 |           0 |      0 |           0 |           0 |            8 | pdfbox/src/main/java/org/apache/pdfbox/pdfparser/BaseParser.java                       |
| OSXAdapter.java              |              6 |             0 |           6 |      0 |           0 |           0 |            0 | debugger/src/main/java/org/apache/pdfbox/debugger/ui/OSXAdapter.java                   |
| StandardSecurityHandler.java |              6 |             0 |           0 |      0 |           6 |           0 |            0 | pdfbox/src/main/java/org/apache/pdfbox/pdmodel/encryption/StandardSecurityHandler.java |
| Type2CharString.java         |              4 |             0 |           0 |      0 |           0 |           0 |            4 | fontbox/src/main/java/org/apache/fontbox/cff/Type2CharString.java                      |
| GlyphSubstitutionTable.java  |              4 |             0 |           0 |      0 |           0 |           0 |            4 | fontbox/src/main/java/org/apache/fontbox/ttf/GlyphSubstitutionTable.java               |

## Project: _apache/poi_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/poi-parent.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/poi) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=poi-parent) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/poi-parent.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified class name                                                   |
|:--------------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------------------|
| FileInformationBlock.java |             34 |             0 |           0 |      0 |          34 |           0 |            0 | scratchpad/src/main/java/org/apache/poi/hwpf/model/FileInformationBlock.java |
| ClassID.java              |             28 |             0 |           1 |      0 |          27 |           0 |            0 | main/src/main/java/org/apache/poi/hpsf/ClassID.java                          |
| SXSSFCell.java            |             20 |             0 |           2 |      0 |           1 |           0 |           17 | ooxml/src/main/java/org/apache/poi/xssf/streaming/SXSSFCell.java             |
| XSSFChart.java            |             15 |             0 |           0 |      0 |          15 |           0 |            0 | ooxml/src/main/java/org/apache/poi/xssf/usermodel/XSSFChart.java             |
| HSLFShape.java            |             14 |             0 |           0 |      0 |           4 |           0 |           10 | scratchpad/src/main/java/org/apache/poi/hslf/usermodel/HSLFShape.java        |
| TableStyleType.java       |             13 |            13 |           0 |      0 |           0 |           0 |            0 | main/src/main/java/org/apache/poi/ss/usermodel/TableStyleType.java           |
| Range.java                |             13 |             0 |           0 |      0 |          13 |           0 |            0 | scratchpad/src/main/java/org/apache/poi/hwpf/usermodel/Range.java            |
| HeaderStories.java        |             13 |             0 |           0 |      0 |          13 |           0 |            0 | scratchpad/src/main/java/org/apache/poi/hwpf/usermodel/HeaderStories.java    |
| XSSFWorkbook.java         |             11 |             0 |           6 |      0 |           5 |           0 |            0 | ooxml/src/main/java/org/apache/poi/xssf/usermodel/XSSFWorkbook.java          |
| SXSSFWorkbook.java        |             11 |             0 |           5 |      0 |           6 |           0 |            0 | ooxml/src/main/java/org/apache/poi/xssf/streaming/SXSSFWorkbook.java         |

