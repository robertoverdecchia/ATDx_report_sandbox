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
||||
|-|-|-|
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/commons-compress.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/commons-compress) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=commons-compress) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/commons-compress.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/commons-geometry.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/commons-geometry) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=commons-geometry) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/commons-geometry.json)</p>|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/commons-numbers.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/commons-numbers) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=commons-numbers) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/commons-numbers.json)</p>
 | |
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/commons-rng.jpg"/> <p style="text-align:left">[Project on Github](https://github.com/apache/commons-rng) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=commons-rng) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/commons-rng.json)</p>
# Project report summaries
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

## Project: _apache/commons-geometry_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/commons-geometry.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/commons-geometry) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=commons-geometry) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/commons-geometry.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                   | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                                                                             |
|:-----------------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:-----------------------------------------------------------------------------------------------------------------------|
| Matrices.java                | 1              | 0             | 0           | 0      | 1           | 0           | 0            | commons-geometry-euclidean/src/main/java/org/apache/commons/geometry/euclidean/internal/Matrices.java                  |
| QuaternionRotation.java      | 1              | 0             | 0           | 0      | 1           | 0           | 0            | commons-geometry-euclidean/src/main/java/org/apache/commons/geometry/euclidean/threed/rotation/QuaternionRotation.java |
| AffineTransformMatrix3D.java | 1              | 0             | 0           | 0      | 1           | 0           | 0            | commons-geometry-euclidean/src/main/java/org/apache/commons/geometry/euclidean/threed/AffineTransformMatrix3D.java     |
| Vector2D.java                | 1              | 0             | 0           | 0      | 1           | 0           | 0            | commons-geometry-euclidean/src/main/java/org/apache/commons/geometry/euclidean/twod/Vector2D.java                      |
| Vector3D.java                | 1              | 0             | 0           | 0      | 1           | 0           | 0            | commons-geometry-euclidean/src/main/java/org/apache/commons/geometry/euclidean/threed/Vector3D.java                    |
| Vector1D.java                | 1              | 0             | 0           | 0      | 1           | 0           | 0            | commons-geometry-euclidean/src/main/java/org/apache/commons/geometry/euclidean/oned/Vector1D.java                      |
| -                            | -              | -             | -           | -      | -           | -           | -            | -                                                                                                                      |
| -                            | -              | -             | -           | -      | -           | -           | -            | -                                                                                                                      |
| -                            | -              | -             | -           | -      | -           | -           | -            | -                                                                                                                      |
| -                            | -              | -             | -           | -      | -           | -           | -            | -                                                                                                                      |

## Project: _apache/commons-numbers_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/commons-numbers.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/commons-numbers) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=commons-numbers) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/commons-numbers.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name             | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                                                    |
|:-----------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:----------------------------------------------------------------------------------------------|
| LinearCombination.java | 1              | 0             | 0           | 0      | 1           | 0           | 0            | commons-numbers-arrays/src/main/java/org/apache/commons/numbers/arrays/LinearCombination.java |
| -                      | -              | -             | -           | -      | -           | -           | -            | -                                                                                             |
| -                      | -              | -             | -           | -      | -           | -           | -            | -                                                                                             |
| -                      | -              | -             | -           | -      | -           | -           | -            | -                                                                                             |
| -                      | -              | -             | -           | -      | -           | -           | -            | -                                                                                             |
| -                      | -              | -             | -           | -      | -           | -           | -            | -                                                                                             |
| -                      | -              | -             | -           | -      | -           | -           | -            | -                                                                                             |
| -                      | -              | -             | -           | -      | -           | -           | -            | -                                                                                             |
| -                      | -              | -             | -           | -      | -           | -           | -            | -                                                                                             |
| -                      | -              | -             | -           | -      | -           | -           | -            | -                                                                                             |

## Project: _apache/commons-rng_
|<img src="https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/plots/commons-rng.jpg"/>|<p style="text-align:left">[Project on Github](https://github.com/apache/commons-rng) <br> [Project on SonarCloud ](https://sonarcloud.io/dashboard?id=commons-rng) <br> [Complete issue report (JSON)](https://github.com/robertoverdecchia/ATDx_report_sandbox/blob/master/jsons/commons-rng.json)</p>
|-|-|
### Top classes with architectural debt violations
| Class name                     | Total issues   | Inheritance   | Exception   | JVMS   | Interface   | Threading   | Complexity   | Fully qualified class name                                                                                     |
|:-------------------------------|:---------------|:--------------|:------------|:-------|:------------|:------------|:-------------|:---------------------------------------------------------------------------------------------------------------|
| NumberFactory.java             | 3              | 0             | 0           | 0      | 3           | 0           | 0            | commons-rng-core/src/main/java/org/apache/commons/rng/core/util/NumberFactory.java                             |
| LargeMeanPoissonSampler.java   | 1              | 0             | 0           | 0      | 1           | 0           | 0            | commons-rng-sampling/src/main/java/org/apache/commons/rng/sampling/distribution/LargeMeanPoissonSampler.java   |
| PoissonSamplerCache.java       | 1              | 0             | 0           | 0      | 1           | 0           | 0            | commons-rng-sampling/src/main/java/org/apache/commons/rng/sampling/distribution/PoissonSamplerCache.java       |
| BaseProvider.java              | 1              | 0             | 0           | 0      | 1           | 0           | 0            | commons-rng-core/src/main/java/org/apache/commons/rng/core/BaseProvider.java                                   |
| AbstractXoShiRo512.java        | 1              | 0             | 0           | 0      | 1           | 0           | 0            | commons-rng-core/src/main/java/org/apache/commons/rng/core/source64/AbstractXoShiRo512.java                    |
| BoxMullerLogNormalSampler.java | 1              | 0             | 0           | 0      | 1           | 0           | 0            | commons-rng-sampling/src/main/java/org/apache/commons/rng/sampling/distribution/BoxMullerLogNormalSampler.java |
| BoxMullerGaussianSampler.java  | 1              | 0             | 0           | 0      | 1           | 0           | 0            | commons-rng-sampling/src/main/java/org/apache/commons/rng/sampling/distribution/BoxMullerGaussianSampler.java  |
| SamplerBase.java               | 1              | 0             | 0           | 0      | 1           | 0           | 0            | commons-rng-sampling/src/main/java/org/apache/commons/rng/sampling/distribution/SamplerBase.java               |
| -                              | -              | -             | -           | -      | -           | -           | -            | -                                                                                                              |
| -                              | -              | -             | -           | -      | -           | -           | -            | -                                                                                                              |

