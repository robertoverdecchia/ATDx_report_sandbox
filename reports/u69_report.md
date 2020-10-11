
# ATDx Report Summary

Introduction, meaning of dimensions, other?

## ATDx of your projects
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/commons-compress.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/commons-compress) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=commons-compress) <br> [Complete issue report (JSON)](./json/commons-compress.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/commons-geometry.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/commons-geometry) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=commons-geometry) <br> [Complete issue report (JSON)](./json/commons-geometry.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/commons-numbers.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/commons-numbers) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=commons-numbers) <br> [Complete issue report (JSON)](./json/commons-numbers.json)</p>
 | |
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/commons-rng.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/commons-rng) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=commons-rng) <br> [Complete issue report (JSON)](./json/commons-rng.json)</p>
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

## Project: _apache/commons-geometry_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/commons-geometry.jpg/>|<p style="text-align:left">[Project on Github](https://github.com/apache/commons-geometry) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=commons-geometry) <br> [Complete issue report (JSON)](./json/commons-geometry.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                                                              |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:-----------------------------------------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| commons-geometry-euclidean/src/main/java/org/apache/commons/geometry/euclidean/internal/Matrices.java                  |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| commons-geometry-euclidean/src/main/java/org/apache/commons/geometry/euclidean/threed/rotation/QuaternionRotation.java |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| commons-geometry-euclidean/src/main/java/org/apache/commons/geometry/euclidean/threed/AffineTransformMatrix3D.java     |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| commons-geometry-euclidean/src/main/java/org/apache/commons/geometry/euclidean/twod/Vector2D.java                      |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| commons-geometry-euclidean/src/main/java/org/apache/commons/geometry/euclidean/threed/Vector3D.java                    |             0 |           0 |         0 |           1 |           0 |            0 |     1 |
| commons-geometry-euclidean/src/main/java/org/apache/commons/geometry/euclidean/oned/Vector1D.java                      |             0 |           0 |         0 |           1 |           0 |            0 |     1 |

## Project: _apache/commons-numbers_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/commons-numbers.jpg/>|<p style="text-align:left">[Project on Github](https://github.com/apache/commons-numbers) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=commons-numbers) <br> [Complete issue report (JSON)](./json/commons-numbers.json)</p>
|-|-|
### Top classes with architectural debt violations
| component                                                                                     |   inheritance |   exception |   vmsmell |   interface |   threading |   complexity |   sum |
|:----------------------------------------------------------------------------------------------|--------------:|------------:|----------:|------------:|------------:|-------------:|------:|
| commons-numbers-arrays/src/main/java/org/apache/commons/numbers/arrays/LinearCombination.java |             0 |           0 |         0 |           1 |           0 |            0 |     1 |

## Project: _apache/commons-rng_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/commons-rng.jpg/>|<p style="text-align:left">[Project on Github](https://github.com/apache/commons-rng) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=commons-rng) <br> [Complete issue report (JSON)](./json/commons-rng.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name         |   Total issues |   Inheritance |   Exception |   JVMS |   Interface |   Threading |   Complexity | Fully qualified name                                                               |
|:-------------------|---------------:|--------------:|------------:|-------:|------------:|------------:|-------------:|:-----------------------------------------------------------------------------------|
| NumberFactory.java |              3 |             0 |           0 |      0 |           3 |           0 |            0 | commons-rng-core/src/main/java/org/apache/commons/rng/core/util/NumberFactory.java |

