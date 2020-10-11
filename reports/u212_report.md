
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
|||
|-|-|
|<img src="./plots/pdfbox-reactor.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/pdfbox) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=pdfbox-reactor) <br> [Complete issue report (JSON)](./json/pdfbox-reactor.json)</p>|<img src="./plots/poi-parent.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/poi) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=poi-parent) <br> [Complete issue report (JSON)](./json/poi-parent.json)</p>
# Project report summaries
## Project: _apache/pdfbox_
|./plots/pdfbox-reactor.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/pdfbox) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=pdfbox-reactor) <br> [Complete issue report (JSON)](./json/pdfbox-reactor.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                   |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                                   |
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
|./plots/poi-parent.jpg|<p style="text-align:left">[Project on Github](https://github.com/apache/poi) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=poi-parent) <br> [Complete issue report (JSON)](./json/poi-parent.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                         |
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

