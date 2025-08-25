![](media/image1.png){width="4.330555555555556in"
height="3.2152777777777777in"}

FAIRICUBE --\
F.A.I.R. INFORMATION CUBES

WP4 Share

D4.3 Public Listing (Catalog) of FAIRiCUBE processing/analysis resources

Deliverable Lead: Stefania Morrone (EPS)

Deliverable due date: 31/12/2024

Version: 3.2

2024-12-23

# Document Control Page

+-------------+--------------------------------------------------------+
| Document    |                                                        |
| Control     |                                                        |
| Page        |                                                        |
+=============+========================================================+
| Title       | Public Listing (Catalog) of FAIRiCUBE                  |
|             | processing/analysis resources                          |
+-------------+--------------------------------------------------------+
| Creator     | Stefania Morrone                                       |
+-------------+--------------------------------------------------------+
| Description | First version (EPS)                                    |
+-------------+--------------------------------------------------------+
| Publisher   | "FAIRICUBE -- F.A.I.R. information cubes" Consortium   |
+-------------+--------------------------------------------------------+
| C           | Stefania Morrone, Fabio Vinci, Liliana Martirano,      |
| ontributors | Antonio Cozzolino, Kathi Schleidt (EPS), Stefan        |
|             | Jetschny, Jaume Targa, Cristina Carnerero, Christian   |
|             | Schiller                                               |
+-------------+--------------------------------------------------------+
| Date of     | 10/12/2024                                             |
| delivery    |                                                        |
+-------------+--------------------------------------------------------+
| Type        | Text                                                   |
+-------------+--------------------------------------------------------+
| Language    | EN-GB                                                  |
+-------------+--------------------------------------------------------+
| Rights      | Copyright "FAIRICUBE -- F.A.I.R. information cubes"    |
+-------------+--------------------------------------------------------+
| Audience    | ☒ Public                                               |
|             |                                                        |
|             | ☐ Confidential                                         |
|             |                                                        |
|             | ☐ Classified                                           |
+-------------+--------------------------------------------------------+
| Status      | ☐In Progress                                           |
|             |                                                        |
|             | ☐ For Review                                           |
|             |                                                        |
|             | ☒ For Approval                                         |
|             |                                                        |
|             | ☐ Approved                                             |
+-------------+--------------------------------------------------------+

: []{#_Ref126431127 .anchor}Table 1 : Initial list of metadata
information requirements

  --------------------------------------------------------------------------
  Revision                                         
  History                                          
  ---------- -------------- ---------------------- -------------------------
  Version    Date           Modified by            Comments

  0.1        11/01/2023     Kathi Schleidt         Initial Document

  0.2        04/02/2023     Giacomo Martirano      First draft

  0.3        14/02/2023     Giacomo Martirano      Consolidated draft,
                                                   inputs from Kathi
                                                   Schleidt, Stephan
                                                   Jetschny, Rob Knapen,
                                                   Stephan Meißl, Liliana
                                                   Martirano, Antonio
                                                   Cozzolino

  0.4        22/02/2023     Stefania Morrone       Final draft

  1.0        28/02/2023     Stefania Morrone       Consolidated version,
                                                   inputs from Kathi
                                                   Schleidt, Rob Knapen,
                                                   Liliana Martirano,
                                                   Antonio Cozzolino

  1.1        01/03/2023     Jaume Targa, Cristina  Review
                            Carnerero              

  1.2        06/03/2023     Stefania Morrone,      Accepting changes from
                            Stefan Jetschny        review, final version for
                                                   delivery

  2.0        12/09/2023     Stefania Morrone,      New draft
                            Antonio Cozzolino      

  2.1        29/11/2023     Christian Schiller     updated Chapter 5

  2.2        22/12/2023     Stefania Morrone,      Draft version 2.2
                            Antonio Cozzolino,     
                            Liliana Martirano      

  2.3        12/01/2024     Jaume Targa            Review

  3.0        10/12/2024     Stefania Morrone,      Added 'Validation' to
                            Antonio Cozzolino      list of MD requirements
                                                   and deleted 'Other
                                                   category' -- Updated
                                                   section 4 and section 5

  3.1        23/12/2024     Stefania Morrone       Further updates

  3.2        23/12/2024     Jaume Targa and Stefan Final review and format
                            Jetschny               checking

                                                   
  --------------------------------------------------------------------------

  : []{#_Ref127294712 .anchor}Table 2 : Initial values of codelists
  (1/3)

# Disclaimer

This document is issued within the frame and for the purpose of the
FAIRICUBE project. This project has received funding from the European
Union's Horizon research and innovation programme under grant agreement
No. 101059238. The opinions expressed and arguments employed herein do
not necessarily reflect the official views of the European Commission.

This document and its content are the property of the FAIRICUBE
Consortium. All rights relevant to this document are determined by the
applicable laws. Access to this document does not grant any right or
license on the document or its contents. This document or its contents
are not to be used or treated in any manner inconsistent with the rights
or interests of the FAIRICUBE Consortium or the Partners' detriment and
are not to be disclosed externally without prior written consent from
the FAIRICUBE Partners. Each FAIRICUBE Partner may use this document in
conformity with the FAIRICUBE Consortium Grant Agreement provisions.

# Table of Contents

[Document Control Page
[2](#document-control-page)](#document-control-page)

[Disclaimer [4](#disclaimer)](#disclaimer)

[Table of Contents [5](#table-of-contents)](#table-of-contents)

[List of Figures [7](#list-of-figures)](#list-of-figures)

[List of Tables [8](#list-of-tables)](#list-of-tables)

[1 Introduction [9](#introduction)](#introduction)

[2 Processing/analysis resources
[10](#processinganalysis-resources)](#processinganalysis-resources)

[3 Metadata Information Requirements for Processing-Analysis Resources
[11](#metadata-information-requirements-for-processing-analysis-resources)](#metadata-information-requirements-for-processing-analysis-resources)

[3.1 Codelists governance
[14](#codelists-governance)](#codelists-governance)

[3.2 Examples [17](#examples)](#examples)

[4 Standard for the encoding of metadata of Processing/Analysis
Resources
[22](#standard-for-the-encoding-of-metadata-of-processinganalysis-resources)](#standard-for-the-encoding-of-metadata-of-processinganalysis-resources)

[5 FAIRiCUBE Catalog for Processing/Analysis Resources
[27](#fairicube-catalog-for-processinganalysis-resources)](#fairicube-catalog-for-processinganalysis-resources)

[6 Summary and outlook [34](#summary-and-outlook)](#summary-and-outlook)

[Annex 1: Existing Standards for Processing-Analysis Resources
[35](#annex-1-existing-standards-for-processing-analysis-resources)](#annex-1-existing-standards-for-processing-analysis-resources)

[PROV [35](#prov)](#prov)

[Entities [35](#entities)](#entities)

[Activities [35](#activities)](#activities)

[Usage and Generation
[35](#usage-and-generation)](#usage-and-generation)

[Agents and Responsibility
[36](#agents-and-responsibility)](#agents-and-responsibility)

[Roles [36](#roles)](#roles)

[Derivation and Revision
[36](#derivation-and-revision)](#derivation-and-revision)

[Plans [36](#plans)](#plans)

[Time [37](#time)](#time)

[Classical / Shallow ML
[37](#classical-shallow-ml)](#classical-shallow-ml)

[PyTorch Model Zoo [37](#pytorch-model-zoo)](#pytorch-model-zoo)

[Hugging Face Models [38](#hugging-face-models)](#hugging-face-models)

[ONNX Open Neural Network Exchange
[39](#onnx-open-neural-network-exchange)](#onnx-open-neural-network-exchange)

[Weights and Biases [40](#weights-and-biases)](#weights-and-biases)

[Provenance on Notebooks
[40](#provenance-on-notebooks)](#provenance-on-notebooks)

[Annex 2: STAC UML [41](#annex-2-stac-uml)](#annex-2-stac-uml)

[Annex 3: Example of STAC-JSON file
[42](#annex-3-example-of-stac-json-file)](#annex-3-example-of-stac-json-file)

# List of Figures

Figure 1 : Codelist change proposal template [15](#_Ref154052243)

Figure 2 : stac-fastapi [27](#_Ref154052310)

Figure 3 : FAIRiCUBE Knowledge Base Query Tool [28](#_Ref154052327)

Figure 4 : webGUI -- Landing page [28](#_Ref154052344)

Figure 5 : Screenshot of the a/p metadata webform (1)
[29](#_Ref154052368)

Figure 6 : Screenshot of the a/p metadata webform (2)
[30](#_Ref154052378)

Figure 7 : Screenshot of the a/p metadata webform (3)
[30](#_Ref154052382)

Figure 8 : Screenshot of the a/p metadata webform (4)
[31](#_Ref154052384)

Figure 9: Screenshot of the a/p metadata webform (5)
[32](#_Ref185846163)

Figure 10 : successful upload message [33](#_Ref154052438)

Figure 11 : PROV Core model [35](#_Toc187696117)

![SqueezeNet
Visualization](media/image2.png){width="6.298611111111111in"
height="1.0763888888888888in"}Figure 12 : ONNX example visualizing a
SqueezeNet model exported from PyTorch [40](#_Toc187696118)

# List of Tables

Table 1 : Initial list of metadata information requirements
[11](#_Ref126431127)

Table 2 : Initial values of codelists (1/3) [15](#_Ref127294712)

Table 3 : Initial values of codelists (2/3) [16](#_Ref127294720)

Table 4 : Initial values of codelists (3/3) [17](#_Ref127977969)

Table 5 : Example 1: Wildfire/no wildfire image classification with
LeNet [18](#_Ref127977415)

Table 6 : Example 2: Dataset balancing [19](#_Ref127977421)

Table 7 : Example 3: JPEG images to NumPy array transformation
[20](#_Ref127977428)

Table 8 : Mapping of metadata information requirements toward STAC
[23](#_Ref127297407)

# Introduction

This document outlines the metadata requirements necessary for the
identification and use of processing/analysis (a/p) resources created
within FAIRiCUBE. In addition, it describes how these user requirements
can be supported using STAC (SpatioTemporal Asset Catalog)[^1] catalogs,
mapping each concept from the identified metadata requirements to
concepts from the STAC standard. Finally, it explains how the
STAC-encoded metadata for processing/analysis resources are exposed via
both APIs (Application Programming Interfaces) as well as human readable
interfaces, allowing potential users to easily identify available
processing/analysis resources.

*Document structure:*

Section 2 Processing/analysis resources explains what a/p resources are
and what types of a/p resources have been created in FAIRiCUBE.

Section 3 Metadata Information Requirements for Processing-Analysis
Resources details the list of information requirements for the metadata
documents describing the a/p resources.

Section 4 Standard for the encoding of metadata of Processing/Analysis
Resources describes how the metadata concepts identified for the
description of processing/analysis resources can be mapped to concepts
derived from the STAC standard. This mapping concerns both the core STAC
model, and the various extensions identified as suitable for the
FAIRiCUBE requirements.

Section 5 FAIRiCUBE Catalog for Processing/Analysis Resources details
the STAC metadata catalog that has been created to facilitate the re-use
of FAIRiCUBE a/p resources in other geographical areas and other
thematic contexts. Interested users can consult the a/p resources
Catalog to easily find the resources most suited to their needs. The a/p
resources Catalog is complemented by the data Catalog, whose description
is provided in Deliverable D4.2.

Section 6 Summary and outlook summarises the work done and its
importance in terms of reuse beyond the project.

Annex1 contains an overview of existing standards for
processing/analysis resources, which have been investigated to support
the finalization of the information requirements for the resource
metadata.

Annex 2 provides the STAC UML diagram.

Annex 3 provides an example of STAC-JSON metadata file.

This document represents the third version, due at M30, i.e., by
31.12.2024, of the deliverable D4.3 "Public Listing (Catalog) of
FAIRiCUBE processing/analysis resources". The three deliverables report
the activities carried out within the Task 4.3 "Enable FAIRiCUBE
Processing/Analysis".

# Processing/analysis resources

Processing/analysis resources refer to the computational infrastructure,
software tools and techniques used to prepare, transform and analyse
large datasets for model training and evaluation. These resources play a
critical role in the ML pipeline to extract insights, identify patterns
and build accurate models. The FAIRiCUBE a/p resources are the building
blocks that were created during the project lifetime to extract insights
from the data processed and/or analysed by the use cases.

Two types of processing/analysis resources are identified within
FAIRiCUBE: resources performing learning tasks and resources performing
non-learning tasks, such as ingestion, statistical analysis or
pre-processing processes. All resources are described by metadata
documents published in the
[Catalog](https://catalog.eoxhub.fairicube.eu/) accessible from the
[FAIRiCUBE Hub](https://hub.fairicube.eu/) and based on the STAC
standard. The a/p metadata document provide information about the
intended use of the resources, their technical characteristics, the
input data used, the output data generated and other relevant aspects.
They play an essential role in enabling findability, accessibility,
interoperability and reuse of the analysis/processing resources,
according to the FAIR principles for digital assets management.

Metadata of data is dealt with in Task 4.2 "Enable FAIRiCUBE Data
Access" and the associated deliverable D4.2 "Public Listing (Catalog) of
FAIRiCUBE data resources", whereby care has been taken to ensure that
the same encoding is used for parallel metadata concepts between the
descriptions of the data vs. processing/analysis resources.

# Metadata Information Requirements for Processing-Analysis Resources

The list of metadata information requirements is provided in Table 1.
For each metadata element (or concept), its name, type, multiplicity and
additional notes are provided. This list, which is independent of the
standard used for metadata encoding, has been based on the initial
iteration loop with the two platform owners (EOX and rasdaman) and use
case owners. It has been finalized based on a second iteration loop, in
which the resource owners tested the creation of their metadata. To
guarantee semantic harmonization, the metadata elements whose type is
'codelist' are valorised by selecting values from corresponding
enumerations managed by the project consortium, according to the
procedures agreed. More details on codelists governance are provided in
section 3.1 'Codelists governance' together with the initial values for
the codelists.

+------------+-------------+-----------+-------------------------------+
| **Element  | **Element   | **Multi   | **Notes**                     |
| name**     | type**      | plicity** |                               |
+============+=============+===========+===============================+
| Use case   | Codelist    | 1         | Use case to which the         |
|            |             |           | resource belongs              |
+------------+-------------+-----------+-------------------------------+
| Name of    | Char        | 1         | Textual name identifying the  |
| resource   | acterString |           | resource.                     |
|            |             |           |                               |
|            |             |           | The resource can be the       |
|            |             |           | algorithm, the model, or the  |
|            |             |           | pre-processing pipeline.      |
+------------+-------------+-----------+-------------------------------+
| Identifier | Char        | 1         | Globally random, unique and   |
|            | acterString |           | persistent identifier of the  |
|            |             |           | resource                      |
+------------+-------------+-----------+-------------------------------+
| D          | Char        | 1         | Description of the resource.  |
| escription | acterString |           |                               |
+------------+-------------+-----------+-------------------------------+
| Main       | Codelist    | 1         | The main category of the      |
| category   |             |           | resource, e.g., ML,           |
|            |             |           | ingestion, pre-processing.    |
|            |             |           | Notice that the codelist also |
|            |             |           | contains some specific        |
|            |             |           | elements to further specify   |
|            |             |           | the resource (e.g., \"DL\" as |
|            |             |           | a special case of \"ML\").    |
+------------+-------------+-----------+-------------------------------+
| P          | Date        | 1         | Date of publication - i.e.,   |
| ublication |             |           | first sharing with the        |
| date       |             |           | scientific community - of the |
|            |             |           | resource. This field is       |
|            |             |           | strongly recommended for ML   |
|            |             |           | resources                     |
+------------+-------------+-----------+-------------------------------+
| Objective  | Codelist    | 1         | This element is used to       |
|            |             |           | provide information about the |
|            |             |           | purpose of the resource.      |
|            |             |           |                               |
|            |             |           | The list of allowed values is |
|            |             |           | still incomplete, and new     |
|            |             |           | values could be included in   |
|            |             |           | the list with the support of  |
|            |             |           | the consortium.               |
|            |             |           |                               |
|            |             |           | Note: the same \'algorithm\'  |
|            |             |           | can be used for different     |
|            |             |           | \'objectives\', - e.g., the   |
|            |             |           | DecisionTreeClassifier        |
|            |             |           | algorithm can be used in the  |
|            |             |           | context of both               |
|            |             |           | 'classification' and 'gap     |
|            |             |           | filling'.                     |
+------------+-------------+-----------+-------------------------------+
| Platform   | Codelist    | 1         | Platform hosting the          |
|            |             |           | resource.                     |
+------------+-------------+-----------+-------------------------------+
| Framework  | Codelist    | 1         | This field is generally       |
|            |             |           | intended as a collection of   |
|            |             |           | reusable code written by      |
|            |             |           | others. In this respect, it   |
|            |             |           | includes both frameworks,     |
|            |             |           | intended as program scaffolds |
|            |             |           | that supply the blueprint of  |
|            |             |           | a product, and libraries,     |
|            |             |           | intended as collections of    |
|            |             |           | pre-defined methods and       |
|            |             |           | classes. Notice that the same |
|            |             |           | processing can be done using  |
|            |             |           | multiple libraries. For       |
|            |             |           | example, both PyTorch and     |
|            |             |           | Tensorflow allow to build an  |
|            |             |           | artificial neural network, or |
|            |             |           | both NumPy and OpenCV allow   |
|            |             |           | transformations on an image.  |
+------------+-------------+-----------+-------------------------------+
| Ar         | Codelist    | 0...1 C   | This is a conditional         |
| chitecture |             |           | element, applied only to ML   |
|            |             |           | algorithms.                   |
|            |             |           |                               |
|            |             |           | This field has a different    |
|            |             |           | meaning than \"algorithm\"    |
|            |             |           | because there are often       |
|            |             |           | multiple \"implementations\"  |
|            |             |           | of an architecture.           |
|            |             |           |                               |
|            |             |           | For example, the DecisionTree |
|            |             |           | architecture has an           |
|            |             |           | implementation for regression |
|            |             |           | (algorithm is                 |
|            |             |           | DecisionTreeRegressor) and an |
|            |             |           | implementation for            |
|            |             |           | classification (algorithm is  |
|            |             |           | DecisionTreeClassifier).      |
+------------+-------------+-----------+-------------------------------+
| Approach   | Codelist    | 0...1 C   | This is a conditional         |
|            |             |           | element, applied only to ML   |
|            |             |           | algorithms, identifying the   |
|            |             |           | learning modality             |
+------------+-------------+-----------+-------------------------------+
| Algorithm  | Codelist    | 1         | This field contains the name  |
|            |             |           | of the algorithm, i.e., an    |
|            |             |           | implementation of an          |
|            |             |           | architecture.                 |
|            |             |           |                               |
|            |             |           | This field has a different    |
|            |             |           | meaning than 'architecture'   |
|            |             |           | because there are often       |
|            |             |           | multiple \"implementations\"  |
|            |             |           | of an architecture. For       |
|            |             |           | example,                      |
|            |             |           | DecisionTreeClassifier and    |
|            |             |           | DecisionTreeRegressor are     |
|            |             |           | different algorithms (with    |
|            |             |           | very different outputs), but  |
|            |             |           | they have the same            |
|            |             |           | architecture.                 |
|            |             |           |                               |
|            |             |           | Note that this field is       |
|            |             |           | mandatory. If any known       |
|            |             |           | algorithm was used, you can   |
|            |             |           | use the value 'custom-method' |
+------------+-------------+-----------+-------------------------------+
| Processor  | Codelist    | 1         | Type of processor used (e.g., |
|            |             |           | cpu, gpu, tpu) for training   |
|            |             |           | or inference in learning      |
|            |             |           | tasks, or for running a       |
|            |             |           | pre-processing notebook.      |
|            |             |           |                               |
|            |             |           | If more than one processor is |
|            |             |           | used to perform the task,     |
|            |             |           | indicate the one with the     |
|            |             |           | highest computing power.      |
+------------+-------------+-----------+-------------------------------+
| OS         | Codelist    | 1         | Operating System used (e.g.,  |
|            |             |           | Windows, Linux or macOS)      |
+------------+-------------+-----------+-------------------------------+
| Keyword    | Codelist    | 1...\*    | A series of keywords aimed to |
|            |             |           | facilitate the resource       |
|            |             |           | discoverability. These        |
|            |             |           | keywords can be used for a    |
|            |             |           | quick search of resources and |
|            |             |           | should highlight the foremost |
|            |             |           | characteristics of the        |
|            |             |           | resource.                     |
|            |             |           |                               |
|            |             |           | Note: For the categorization  |
|            |             |           | of resources via keywords to  |
|            |             |           | be effective, we recommend    |
|            |             |           | that a maximum of 5 keywords  |
|            |             |           | is provided.                  |
+------------+-------------+-----------+-------------------------------+
| Reference  | URI         | 0...\*    | Link(s) to resource web page  |
| link       |             |           | and/or download page          |
+------------+-------------+-----------+-------------------------------+
| Example    | URI         | 0...\*    | Link(s) to websites           |
|            |             |           | (including publications)      |
|            |             |           | providing examples of how the |
|            |             |           | resource has been used.       |
+------------+-------------+-----------+-------------------------------+
| Input data | URI         | 1...\*    | Link to data (or related      |
| used       |             |           | metadata) to which the a/p    |
|            |             |           | resource has been applied.    |
|            |             |           | This information is required  |
|            |             |           | for a better understanding of |
|            |             |           | the context and domain of the |
|            |             |           | a/p resource.                 |
+------------+-------------+-----------+-------------------------------+
| Chara      | Char        | 1...\*    | This field contains a textual |
| cteristics | acterString |           | description of the main       |
| of input   |             |           | characteristics of each input |
| data       |             |           | data to the resource. This    |
|            |             |           | field also includes e.g., a   |
|            |             |           | description of sampling       |
|            |             |           | techniques, a version of the  |
|            |             |           | data (if multiple versions    |
|            |             |           | are available), and, in the   |
|            |             |           | case of ML resources, the     |
|            |             |           | percentages of training,      |
|            |             |           | validation and testing sets.  |
|            |             |           | This field may contain        |
|            |             |           | details on the suitability of |
|            |             |           | the resource for the chosen   |
|            |             |           | geographic area and thematic  |
|            |             |           | context.                      |
+------------+-------------+-----------+-------------------------------+
| Biases and | Char        | 0\...\*   | This field may contain        |
| ethical    | acterString |           | observations on the data      |
| aspects    |             |           | and/or any biases found       |
|            |             |           | (e.g., class imbalances).     |
|            |             |           |                               |
|            |             |           | This field is optional but    |
|            |             |           | strongly recommended for      |
|            |             |           | pre-processing resources.     |
|            |             |           |                               |
|            |             |           | In the case of ML resources,  |
|            |             |           | this field is closely related |
|            |             |           | to the performance field.     |
+------------+-------------+-----------+-------------------------------+
| Model      | Char        | 0..1      | This field contains the       |
| con        | acterString |           | configuration/initialisation  |
| figuration |             |           | data and how the model has    |
|            |             |           | been parameterized            |
+------------+-------------+-----------+-------------------------------+
| Output     | URI         | 1...\*    | Link to output data (or       |
| data       |             |           | related metadata) produced by |
| obtained   |             |           | the execution of the a/p      |
|            |             |           | resource. This information is |
|            |             |           | required for a better         |
|            |             |           | understanding of the a/p      |
|            |             |           | resource.                     |
+------------+-------------+-----------+-------------------------------+
| Chara      | Char        | 1\...\*   | Textual description of the    |
| cteristics | acterString |           | output data from the          |
| of output  |             |           | resource.                     |
| data       |             |           |                               |
+------------+-------------+-----------+-------------------------------+
| Validation | URI         | 0..1      | Link to a validation report   |
+------------+-------------+-----------+-------------------------------+
| P          | Char        | 0..1 C    | This is a conditional         |
| erformance | acterString |           | element, applied only to ML   |
|            |             |           | algorithms. This field        |
|            |             |           | contains result description   |
|            |             |           | and explanation, including a  |
|            |             |           | detailed description of the   |
|            |             |           | hyperparameters used, the run |
|            |             |           | times, the metrics used for   |
|            |             |           | evaluation, and the           |
|            |             |           | respective scores and         |
|            |             |           | performance.                  |
+------------+-------------+-----------+-------------------------------+
| Conditions | Codelist    | 1         | Type of distribution license  |
| for access |             |           | for the resource (e.g., MIT   |
| and use    |             |           | or CC-BY).                    |
+------------+-------------+-----------+-------------------------------+
| C          | Char        | 0..1      | This element can be used to   |
| onstraints | acterString |           | provide information about     |
|            |             |           | possible constraints related  |
|            |             |           | to the use of the resource    |
|            |             |           | (e.g., the resource works     |
|            |             |           | only for certain Input data,  |
|            |             |           | the resource needs specific   |
|            |             |           | computational power).         |
+------------+-------------+-----------+-------------------------------+

: []{#_Ref127294720 .anchor}Table 3 : Initial values of codelists (2/3)

## Codelists governance

The proposed approach to governance of the codelists accounts for the
way STAC works with the list of values (i.e., using enumerations).
Possible integration of external codelists, if needed, will be
investigated on a case-by-case basis, considering the governance
mechanisms already in place. The current values for the a/p metadata
codelists are provided in Table 2, Table 3 and Table 4. The codelists
are managed in the
[\'resource-metadata](https://github.com/FAIRiCUBE/resource-metadata)\'
GitHub repository in the [FAIRiCUBE GitHub
organization](https://github.com/FAIRiCUBE). It is possible to propose
the addition of new codelist values or the updating of existing ones by
opening issues in the issue tracker of this repository, using the [ad
hoc
template](https://github.com/FAIRiCUBE/resource-metadata/issues/new?assignees=&labels=&projects=&template=codelist_change_proposal.yml)
illustrated in Figure 1 below.

![A screenshot of a computer Description automatically
generated](media/image3.png){width="3.714621609798775in"
height="3.937007874015748in"}

[]{#_Ref154052243 .anchor}Figure 1 : Codelist change proposal template

Any feedback on proposals should be provided via replies to the related
GitHub issues. A proposal is assumed as approved by the consortium after
an agreed period without negative feedback, after which the code lists
are updated with the new/amended values.

  ------------------------------------------------------------------------------------------------------------
  **Main           **Objective**              **Platform**      **Framework**   **Architecture**
  category**                                                                    
  ---------------- -------------------------- ----------------- --------------- ------------------------------
  Machine Learning object-detection           EOX               pytorch         random forest

  Deep Learning    classification             Rasdaman          tensorflow      DNN -- Deep-Neural-Network

  Pre-processing   segmentation               Google Colab      scikit-learn    decision-tree

  Ingestion        regression                 Kaggle            keras           ensemble

  Analytics        outliers-removing          Microsoft Azure   pandas          gradient-based

                   gap-filling                Amazon AWS        numpy           density-based

                   feature-selection          Local Jupyter     openCV          datacubes
                                              Notebook                          

                   dimensionality-reduction                     XGBoost         RNN --
                                                                                Recurrent-Neural-Network

                   feature-scaling                              theano          CNN --
                                                                                Convolutional-Neural-Network

                   dataset-balancing                            imblearn        Feed-Forward-Neural-Network

                   data-transformation                          pillow          DBN -- Deep-Belief-Network

                   analytics                                    Rasdaman        DSN -- Deep-Stacking-Network

                   clustering                                   MXNet           SVM -- Support-Vector-Machine

                   anomaly-detection                            Apache-Spark    probabilistic model

                                                                gdal            Perceptron

                                                                no-framework    Multilayer-Perceptron
  ------------------------------------------------------------------------------------------------------------

  : []{#_Ref127977969 .anchor}Table 4 : Initial values of codelists
  (3/3)

  -------------------------------------------------------------------------------------------------------------------------------
  **Approach**             **Algorithm**                                                 **Processor**   **OS**      **Use case**
  ------------------------ ------------------------------------------------------------- --------------- ----------- ------------
  supervised               Random-Forest-Classifier                                      cpu             aix         UC1

  unsupervised             CNN - Convolutional-Neural-Network                            gpu             linux       UC2

  semi-supervised          K-means                                                       tpu             windows     UC3

  reinforcement-learning   Min-max-normalization                                                         cygwin      UC4

                           DBSCAN -                                                                      darwin      UC5
                           Density-Based-Spatial-Clustering-of-Applications-with-Noise                               

                           Decision-Tree-Classifier                                                      macOS       common

                           Random-Forest-Regression                                                                  

                           SGD - classifier -- Stochastic-Gradient-Descent                                           

                           KNN -- classifier -- K-nearest-neighbors                                                  

                           SegNet                                                                                    

                           LeNet                                                                                     

                           Decision-Tree-Regression                                                                  

                           Voting-Classifier                                                                         

                           AdaBoost-Classifier                                                                       

                           AdaBoost-Regression                                                                       

                           SMOTE -- Synthetic-Minority-Oversampling-TEchnique                                        

                           custom-method                                                                             

                           WCPS                                                                                      

                           Naïve-Bayes                                                                               

                           Logistic-regression                                                                       

                           Gaussian-Mixture                                                                          
  -------------------------------------------------------------------------------------------------------------------------------

  : []{#_Ref127977415 .anchor}Table 5 : Example 1: Wildfire/no wildfire
  image classification with LeNet

  -----------------------------------------------------------------------------------------------------------
  **Conditions for access and                                                                    
  use**                                                                                          
  --------------------------- ----------------- ----------------------- ----------- ------------ ------------
  afl-3.0                     cc                cc-by-nc-nd-4.0         epl-1.0     lgpl-3.0     osl-3.0

  agpl-3.0                    cc0-1.0           cc-by-nc-sa-2.0         epl-2.0     lgpl-lr      pddl

  artistic-2.0                cc-by-2.0         cc-by-nc-sa-3.0         eupl-1.1    mpl-2.0      postgresql

  bigscience-bloom-rail-1.0   cc-by-2.5         cc-by-nc-sa-4.0         gfdl        ms-pl        wtfpl

  bigscience-openrail-m       cc-by-3.0         cc-by-nd-4.0            gpl         ncsa         

  bsd                         cc-by-4.0         cc-by-sa-3.0            gpl-2.0     odbl         

  bsd-2-clause                cc-by-nc-2.0      cc-by-sa-4.0            gpl-3.0     odc-by       

  bsd-3-clause                cc-by-nc-3.0      creativeml-openrail-m   isc         ofl-1.1      

  bsd-3-clause-clear          cc-by-nc-4.0      c-uda                   lgpl        openrail     

  bsl-1.0                     cc-by-nc-nd-3.0   ecl-2.0                 lgpl-2.1    openrail++   
  -----------------------------------------------------------------------------------------------------------

  : []{#_Ref127297407 .anchor}Table 8 : Mapping of metadata information
  requirements toward STAC

## Examples

To illustrate an example on processing/analysis resources, find below
examples for the population of information requirements forms related to
three processing/analysis resources:

-   image classification with LeNet (Table 5),

-   dataset balancing (Table 6) and

-   transformation of non-georeferenced images into NumPy arrays (Table
    7).

These are, however, purely illustrative examples and have no
relationship with the FAIRiCUBE use cases. An ad-hoc pipeline has been
conceived with wildfire/no-wildfire image classification as the final
task, requiring some data manipulations. The focus is on the ML (Machine
Learning) resource, but all the 3 building-blocks of the pipeline are
illustrated to highlight the flexibility of the information requirements
template and the importance of all its elements (all the URIs used in
the examples are resolvable):

-   The first block of the pipeline is a pre-processing consisting of a
    transformation of satellite jpeg images (with coordinates provided
    in the filename) to NumPy arrays for building a new machine-readable
    dataset.[^2]

-   The second block is a pre-processing consisting of a (NumPy arrays)
    dataset balancing.

-   The last block is a learning task (DL) building and training a LeNet
    ANN and saving the model for predictions.

  -------------------------------------------------------------------------------------------------------
  **Element name**  **Element value example**
  ----------------- -------------------------------------------------------------------------------------
  Use case          common

  Name of resource  LeNet Classifier

  Identifier        lenet_classifier

  Description       Multi-layer Convolutional Neural Network for image classification

  Main category     Deep Learning

  Publication date  2023-04-04

  Objective         classification

  Platform          Google Colab

  Framework         keras

  Architecture      CNN - Convolutional-Neural-Network

  Approach          supervised

  Algorithm         LeNet

  Processor         gpu

  OS                Linux

  Keyword           classification, CNN, LeNet

  Reference link    <https://en.wikipedia.org/wiki/LeNet>

  Example           <https://github.com/cozzolinoac11/wildfire_prediction/blob/main/ann.ipynb>

  Input data used   <https://public.epsilon-italia.it/FAIRiCUBE/wildfire-classification/data_numpy.zip>

  Characteristics   Numpy arrays. (Perfectly) balanced classes.
  of input data     

  Biases and        
  ethical aspects   

  Output data       <http://www.epsilon-italia.it/public/model.zip>
  obtained          

  Characteristics   Keras model for wildfire or no wildfire classification. The model gets in input a
  of output data    dataset as numpy arrays (dimension 100x100x3) and returns the predicted labels.

  Validation        

  Performance       Accuracy score: 0.9505 (validation). Running time: 2 min for 23 training epochs with
                    early stopping (total number of epochs: 50) on a gpu Nvidia a100. Modified
                    hyperparameters: Input shape: (100,100,3); Optimizer: 'adam'; batch size: 128.
                    Train-test-valid split: 70-15-15. Loss function: sparse_categorical_crossentropy.

  Conditions for    CC-BY-4.0
  access and use    

  Constraints       
  -------------------------------------------------------------------------------------------------------

[]{#_Ref127977421 .anchor}Table 6 : Example 2: Dataset balancing

  ----------------------------------------------------------------------------------------------------------------
  **Element name**  **Element value example**
  ----------------- ----------------------------------------------------------------------------------------------
  Use case          common

  Name of resource  SMOTE dataset balancing

  Identifier        SMOTE dataset balancing

  Description       Dataset balancing using SMOTE oversampling technique. A balanced dataset is a dataset where
                    each output class (or target class) is represented by the same number of input samples.
                    Imbalanced data is not always a bad thing and there is always some degree of imbalance in real
                    data sets. That said, if the level of imbalance is relatively low, there should not be much
                    impact on the performance of the model but, in some cases, working on unbalanced data could
                    introduce a high error rate. Imbalanced data is one of the potential problems in the field of
                    data mining and machine learning. This problem can be approached by properly analyzing the
                    data. One way to solve this problem is to oversample the examples in the minority class. This
                    can be achieved by simply duplicating examples from the minority class in the training dataset
                    before fitting a model. This can balance the class distribution but does not provide any
                    additional information to the model. An improvement in duplicating examples from the minority
                    class is to synthesize new examples from the minority class. SMOTE works by selecting examples
                    that are close in the feature space, drawing a line between the examples in the feature space
                    and drawing a new sample at a point along that line. Specifically, a random example from the
                    minority class is first chosen. Then k of the nearest neighbors for that example are found
                    (typically k=5). A randomly selected neighbor is chosen, and a synthetic example is created at
                    a randomly selected point between the two examples in the feature space.

  Main category     pre-processing

                    

  Publication date  2023-08-05

  Objective         dataset-balancing

  Platform          Google Colab

  Framework         imblearn

  Architecture      

  Approach          

  Algorithm         SMOTE - Synthetic-Minority-Oversampling-TEchnique

  Processor         cpu

  OS                linux

  Keyword           dataset_balancing, SMOTE

  Reference link    <https://imbalanced-learn.org/stable/references/generated/imblearn.over_sampling.SMOTE.html>

  Example           <https://github.com/cozzolinoac11/wildfire_prediction/blob/main/dataset_balancing.ipynb>

  Input data used   <https://public.epsilon-italia.it/FAIRiCUBE/wildfire-classification/data_numpy.zip>

  Characteristics   Numpy arrays with unbalanced classes (47.9% - 52.1%)
  of input data     

  Biases and        Initial unbalanced dataset
  ethical aspects   

  Output data       <https://public.epsilon-italia.it/FAIRiCUBE/wildfire-classification/balanced_data_numpy.zip>
  obtained          

  Characteristics   Numpy arrays with balanced classes (50% - 50%)
  of output data    

  Validation        

  Performance       

  Conditions for    CC-BY-4.0
  access and use    

  Constraints       
  ----------------------------------------------------------------------------------------------------------------

[]{#_Ref127977428 .anchor}Table 7 : Example 3: JPEG images to NumPy
array transformation

+-----------+----------------------------------------------------------+
| **Element | **Element value example**                                |
| name**    |                                                          |
+===========+==========================================================+
| Use case  | common                                                   |
+-----------+----------------------------------------------------------+
| Name of   | JPEG images to numpy array transformation                |
| resource  |                                                          |
+-----------+----------------------------------------------------------+
| I         | JPEG_to_numpy_transformation                             |
| dentifier |                                                          |
+-----------+----------------------------------------------------------+
| De        | Building dataset as numpy array. In machine learning,    |
| scription | Python uses image data in the form of a NumPy array,     |
|           | i.e., \[Height, Width, Channel\] format. Therefore, the  |
|           | images must be transformed in this format. In this case, |
|           | the images are in JPEG format and, through pillow, NumPy |
|           | and OpenCV functions, the transformation is performed.   |
|           | The cv2 package (OpenCV) has the method imread() which   |
|           | is used to load the image and it also reads the given    |
|           | image (PIL image) in the NumPy array format. Because the |
|           | images within the dataset (i.e., the NumPy arrays) must  |
|           | all be the same size to be used, and as a matter of      |
|           | efficiency and calculation power, using cv2\'s resize () |
|           | the images are resized from 350x350 pixels into 100x100  |
|           | (this dimension can be easily changed). The channel is   |
|           | three because the images are RGB. This method then       |
|           | returns a dataset containing the images in the form of   |
|           | NumPy arrays and their respective class labels.          |
+-----------+----------------------------------------------------------+
| Main      | pre-processing                                           |
| category  |                                                          |
+-----------+----------------------------------------------------------+
| Pu        |                                                          |
| blication |                                                          |
| date      |                                                          |
+-----------+----------------------------------------------------------+
| Objective | Data-transformation                                      |
+-----------+----------------------------------------------------------+
| Platform  | Google Colab                                             |
+-----------+----------------------------------------------------------+
| Framework | openCV                                                   |
+-----------+----------------------------------------------------------+
| Arc       |                                                          |
| hitecture |                                                          |
+-----------+----------------------------------------------------------+
| Approach  |                                                          |
+-----------+----------------------------------------------------------+
| Algorithm | custom-method                                            |
+-----------+----------------------------------------------------------+
| Processor | cpu                                                      |
+-----------+----------------------------------------------------------+
| OS        | linux                                                    |
+-----------+----------------------------------------------------------+
| Keyword   | numpy array, data transformation, jpeg                   |
+-----------+----------------------------------------------------------+
| Reference |                                                          |
| link      |                                                          |
+-----------+----------------------------------------------------------+
| Example   | <https://github.com/cozzolinoac11/wildfi                 |
|           | re_prediction/blob/main/img_to_NPY_transformation.ipynb> |
+-----------+----------------------------------------------------------+
| Input     | <https://open.canada.                                    |
| data used | ca/data/en/dataset/9d8f219c-4df0-4481-926f-8a2a532ca003> |
+-----------+----------------------------------------------------------+
| Charac    | Refer to Canada\'s website for the original wildfires    |
| teristics | data.                                                    |
| of input  |                                                          |
| data      | The dataset is composed by satellite images (shape is    |
|           | 350x350)                                                 |
+-----------+----------------------------------------------------------+
| Biases    |                                                          |
| and       |                                                          |
| ethical   |                                                          |
| aspects   |                                                          |
+-----------+----------------------------------------------------------+
| Output    | <https://public.epsilon-ita                              |
| data      | lia.it/FAIRiCUBE/wildfire-classification/data_numpy.zip> |
| obtained  |                                                          |
+-----------+----------------------------------------------------------+
| Charac    | Dataset in format Numpy arrays. The images are resized   |
| teristics | in 100x100.                                              |
| of output |                                                          |
| data      |                                                          |
+-----------+----------------------------------------------------------+
| V         |                                                          |
| alidation |                                                          |
+-----------+----------------------------------------------------------+
| Pe        |                                                          |
| rformance |                                                          |
+-----------+----------------------------------------------------------+
| C         | CC-BY-4.0                                                |
| onditions |                                                          |
| for       |                                                          |
| access    |                                                          |
| and use   |                                                          |
+-----------+----------------------------------------------------------+
| Co        |                                                          |
| nstraints |                                                          |
+-----------+----------------------------------------------------------+

# Standard for the encoding of metadata of Processing/Analysis Resources

After an analysis of several possible metadata standards, STAC[^3] has
been selected for the encoding of the metadata of processing/analysis
resources for the following reasons:

-   it is the standard used for the encoding of datasets metadata used
    in the context of Task 4.2,

-   it contains the ML Model extension[^4], whose goal is to provide a
    way of cataloguing ML models that operate on Earth observation (EO)
    data, and

-   it allows the user to propose new custom extensions to encode
    information requirements not covered by existing extensions.

To detail processing/analysis resources created within FAIRiCUBE, STAC
core, STAC-ML and STAC customized extensions are used. Table 8 provides
detailed mapping of the metadata information requirements towards STAC,
differentiating between STAC core, STAC-ML and STAC Custom Extension.
The integration of new concepts into the current STAC-ML has been
documented in the GitHub repository
[https://github.com/stac-extensions/ml-model.](https://github.com/stac-extensions/ml-model.%20%20Alt)

Although it was considered necessary to document what was done within
the project in the STAC-ML repository on GitHub using a [dedicated
issue](https://github.com/stac-extensions/ml-model/issues/21), it was
decided not to proceed with the creation of an extended schema
specifically for ML resources, as this would have overloaded the
FAIRiCUBE a/p metadata creation process. In fact, since ML and non-ML
resource types share some common characteristics, to avoid using ML
schema properties for a non-ML resource, the use of different schemas
(and associated input forms) would be necessary.

At the time of writing this Deliverable, we discovered that an extension
to STAC called [Machine Learning Model
Extension](https://github.com/stac-extensions/mlm) has recently (30
September 2024) been published. This extension is similar to the model
developed and implemented in the FAIRiCUBE project. The process leading
to these two implementations was parallel and somehow confirms the
validity of the work carried out in FAIRiCUBE, as there are no
significant differences between the concepts expressed in the two
extensions of the STAC ML model. Although terminological harmonization
could be useful for the interoperability of the metadata produced, it is
not feasible to update the FAIRICUBE a/p metadata model because:

-   Migration to STAC-Machine Learning Model Extension would require
    reimplementation of all ingestion and metadata creation processes.

-   Migration to STAC-Machine Learning Model Extension would require
    reimplementation of all the metadata already created.

+-----------+------------+-----+-------------------------+-----------+
| **Element | **Element  | *   | **Notes**               | **STAC    |
| name**    | type**     | *Mu |                         | Mapping** |
|           |            | lti |                         |           |
|           |            | pli |                         |           |
|           |            | cit |                         |           |
|           |            | y** |                         |           |
+===========+============+=====+=========================+===========+
| Use case  | Codelist   | 1   | Use case to which the   | New STAC  |
|           |            |     | resource belongs        | property  |
+-----------+------------+-----+-------------------------+-----------+
| Name of   | Chara      | 1   | Textual name            | STAC:     |
| resource  | cterString |     | identifying the         | title     |
|           |            |     | resource.               |           |
|           |            |     |                         |           |
|           |            |     | The resource can be the |           |
|           |            |     | algorithm, the model,   |           |
|           |            |     | or the pre-processing   |           |
|           |            |     | pipeline.               |           |
+-----------+------------+-----+-------------------------+-----------+
|           |            |     |                         |           |
+-----------+------------+-----+-------------------------+-----------+
| I         | Chara      | 1   | Globally random, unique | STAC: id  |
| dentifier | cterString |     | and persistent          |           |
|           |            |     | identifier of the       |           |
|           |            |     | resource.               |           |
+-----------+------------+-----+-------------------------+-----------+
| De        | Chara      | 1   | Description of the      | STAC:     |
| scription | cterString |     | resource.               | de        |
|           |            |     |                         | scription |
+-----------+------------+-----+-------------------------+-----------+
| Main      | Codelist   | 1   | The main category of    | New STAC  |
| category  |            |     | the resource, e.g., ML, | property  |
|           |            |     | ingestion,              |           |
|           |            |     | pre-processing. Notice  |           |
|           |            |     | that the codelist also  |           |
|           |            |     | contains some specific  |           |
|           |            |     | elements to further     |           |
|           |            |     | specify the resource    |           |
|           |            |     | (e.g., \"DL\" as a      |           |
|           |            |     | special case of         |           |
|           |            |     | \"ML\").                |           |
+-----------+------------+-----+-------------------------+-----------+
| Pu        | Date       | 1   | Date of publication,    | STAC      |
| blication |            |     | i.e., first sharing     | datetime  |
| date      |            |     | with the scientific     |           |
|           |            |     | community, of the       |           |
|           |            |     | resource. This field is |           |
|           |            |     | strongly recommended    |           |
|           |            |     | for ML resources        |           |
+-----------+------------+-----+-------------------------+-----------+
| Objective | Codelist   | 1   | Information about the   | STAC-ML:  |
|           |            |     | purpose of the resource | ml-mod    |
|           |            |     | (i.e., what does the    | el:predic |
|           |            |     | resource perform).      | tion_type |
|           |            |     |                         |           |
|           |            |     | Note: the same          | New STAC  |
|           |            |     | \'algorithm\' can be    | property  |
|           |            |     | used for different      | in case   |
|           |            |     | \'objectives\', - e.g., | of non-ML |
|           |            |     | the                     | resource  |
|           |            |     | DecisionTreeClassifier  |           |
|           |            |     | algorithm can be used   |           |
|           |            |     | in the context of both  |           |
|           |            |     | 'classification' and    |           |
|           |            |     | 'gap filling'.          |           |
+-----------+------------+-----+-------------------------+-----------+
| Platform  | Codelist   | 1   | Platform hosting the    | New STAC  |
|           |            |     | resource. It is         | property  |
|           |            |     | possible to use a       |           |
|           |            |     | combination of values   |           |
|           |            |     | (e.g., EOX and AWS).    |           |
+-----------+------------+-----+-------------------------+-----------+
| Framework | Codelist   | 1   | This field is generally | New STAC  |
|           |            |     | intended as a           | property  |
|           |            |     | collection of reusable  |           |
|           |            |     | code written by others. |           |
|           |            |     | It includes both        |           |
|           |            |     | frameworks, intended as |           |
|           |            |     | program scaffolds that  |           |
|           |            |     | supply the blueprint of |           |
|           |            |     | a product, and          |           |
|           |            |     | libraries, intended as  |           |
|           |            |     | collections of          |           |
|           |            |     | pre-defined methods and |           |
|           |            |     | classes. Notice that    |           |
|           |            |     | the same processing can |           |
|           |            |     | be done using multiple  |           |
|           |            |     | libraries. For example, |           |
|           |            |     | both PyTorch and        |           |
|           |            |     | Tensorflow allow to     |           |
|           |            |     | build an artificial     |           |
|           |            |     | neural network, or both |           |
|           |            |     | NumPy and OpenCV allow  |           |
|           |            |     | to do transformations   |           |
|           |            |     | on an image.            |           |
+-----------+------------+-----+-------------------------+-----------+
|           |            |     |                         |           |
+-----------+------------+-----+-------------------------+-----------+
| Arc       | Codelist   | 0.. | Conditional element     | STAC-ML:  |
| hitecture |            | 1 C | applied only to ML      | ml-       |
|           |            |     | algorithms.             | model:arc |
|           |            |     |                         | hitecture |
|           |            |     | This field has a        |           |
|           |            |     | different meaning than  |           |
|           |            |     | \"algorithm\" because   |           |
|           |            |     | there are often         |           |
|           |            |     | multiple                |           |
|           |            |     | \"implementations\" of  |           |
|           |            |     | an architecture.        |           |
|           |            |     |                         |           |
|           |            |     | For example, the        |           |
|           |            |     | DecisionTree            |           |
|           |            |     | architecture has an     |           |
|           |            |     | implementation for      |           |
|           |            |     | regression (algorithm   |           |
|           |            |     | is                      |           |
|           |            |     | DecisionTreeRegressor)  |           |
|           |            |     | and an implementation   |           |
|           |            |     | for classification      |           |
|           |            |     | (algorithm is           |           |
|           |            |     | D                       |           |
|           |            |     | ecisionTreeClassifier). |           |
+-----------+------------+-----+-------------------------+-----------+
| Approach  | Codelist   | 0   | Conditional element,    | STAC-ML:  |
|           |            | ..1 | applied only to ML      | ml-model  |
|           |            | C   | algorithms, identifying | :learning |
|           |            |     | the learning modality   | _approach |
+-----------+------------+-----+-------------------------+-----------+
| Algorithm | Codelist   | 1   | Name of the algorithm,  | New STAC  |
|           |            |     | i.e., an implementation | property  |
|           |            |     | of an architecture.     |           |
|           |            |     |                         |           |
|           |            |     | This field has a        |           |
|           |            |     | different meaning than  |           |
|           |            |     | 'architecture' because  |           |
|           |            |     | there are often         |           |
|           |            |     | multiple                |           |
|           |            |     | \"implementations\" of  |           |
|           |            |     | an architecture. For    |           |
|           |            |     | example,                |           |
|           |            |     | DecisionTreeClassifier  |           |
|           |            |     | and                     |           |
|           |            |     | DecisionTreeRegressor   |           |
|           |            |     | are different           |           |
|           |            |     | algorithms (with very   |           |
|           |            |     | different output), but  |           |
|           |            |     | they have the same      |           |
|           |            |     | architecture.           |           |
|           |            |     |                         |           |
|           |            |     | Note that this field is |           |
|           |            |     | mandatory. If no known  |           |
|           |            |     | algorithm was used, you |           |
|           |            |     | can use the value       |           |
|           |            |     | 'custom-method'.        |           |
+-----------+------------+-----+-------------------------+-----------+
| Processor | Codelist   | 1   | Type of processor used  | STAC-ML:  |
|           |            |     | (e.g., cpu, gpu, tpu)   | ml-mo     |
|           |            |     | for training or         | del:train |
|           |            |     | inference in learning   | ing-proce |
|           |            |     | tasks, or for running a | ssor-type |
|           |            |     | pre-processing          |           |
|           |            |     | notebook.               | New STAC  |
|           |            |     |                         | property  |
|           |            |     | If more than one        | in case   |
|           |            |     | processor is used to    | of non-ML |
|           |            |     | perform the task,       | resource  |
|           |            |     | indicate the one with   |           |
|           |            |     | the highest computing   |           |
|           |            |     | power.                  |           |
+-----------+------------+-----+-------------------------+-----------+
| OS        | Codelist   | 1   | Operating System used   | STAC-ML:  |
|           |            |     | (e.g., Windows, Linux   | ml        |
|           |            |     | or macOS)               | -model:tr |
|           |            |     |                         | aining-os |
|           |            |     |                         |           |
|           |            |     |                         | New STAC  |
|           |            |     |                         | property  |
|           |            |     |                         | in case   |
|           |            |     |                         | of non-ML |
|           |            |     |                         | resource  |
+-----------+------------+-----+-------------------------+-----------+
| Keyword   | Chara      | 1.. | A series of keywords    | STAC      |
|           | cterString | .\* | aimed to facilitate the | keywords  |
|           |            |     | resource                |           |
|           |            |     | discoverability. These  |           |
|           |            |     | keywords can be used    |           |
|           |            |     | for a quick search of   |           |
|           |            |     | resources and should    |           |
|           |            |     | highlight foremost      |           |
|           |            |     | characteristics of the  |           |
|           |            |     | resource.               |           |
|           |            |     |                         |           |
|           |            |     | Note: For the           |           |
|           |            |     | categorization of the   |           |
|           |            |     | resources via keywords  |           |
|           |            |     | to be effective, we     |           |
|           |            |     | recommend that a        |           |
|           |            |     | maximum of 5 keywords   |           |
|           |            |     | is provided.            |           |
+-----------+------------+-----+-------------------------+-----------+
| Reference | URI        | 0.. | Link(s) to resource web | STAC:     |
| link      |            | .\* | page and/or download    | link      |
|           |            |     | page                    |           |
+-----------+------------+-----+-------------------------+-----------+
| Imple     | URI        | 0.. | Link(s) to websites     | STAC:     |
| mentation |            | .\* | (including              | link      |
| Example   |            |     | publications) providing |           |
|           |            |     | examples of how the     |           |
|           |            |     | resource has been used. |           |
+-----------+------------+-----+-------------------------+-----------+
| Input     | URI        | 1.. | Link to data (or        | STAC:     |
| data used |            | .\* | related metadata) to    | Asset     |
|           |            |     | which the a/p resource  |           |
|           |            |     | has been applied. This  |           |
|           |            |     | information is required |           |
|           |            |     | for a better            |           |
|           |            |     | understanding of        |           |
|           |            |     | context and domain of   |           |
|           |            |     | the a/p resource.       |           |
+-----------+------------+-----+-------------------------+-----------+
| Charac    | Chara      | 1.. | Textual description of  | STAC      |
| teristics | cterString | .\* | the main                | asset     |
| of input  |            |     | characteristics of each | (de       |
| data      |            |     | input data to the       | scription |
|           |            |     | resource. This field    | field)    |
|           |            |     | also include e.g.,      |           |
|           |            |     | description of sampling |           |
|           |            |     | techniques, version of  |           |
|           |            |     | the data (if multiple   |           |
|           |            |     | versions are            |           |
|           |            |     | available), and, in the |           |
|           |            |     | case of ML resources,   |           |
|           |            |     | also the percentages of |           |
|           |            |     | training, validation    |           |
|           |            |     | and testing sets. This  |           |
|           |            |     | field may contain       |           |
|           |            |     | details on the          |           |
|           |            |     | suitability of the      |           |
|           |            |     | resource for the chosen |           |
|           |            |     | geographic area and     |           |
|           |            |     | thematic context.       |           |
+-----------+------------+-----+-------------------------+-----------+
| Biases    | Chara      | 0   | Observations on the     | STAC      |
| and       | cterString | ..n | data and/or any biases  | asset     |
| ethical   |            |     | found (e.g., class      | (de       |
| aspects   |            |     | imbalances).            | scription |
|           |            |     |                         | field)    |
|           |            |     | This field is optional  |           |
|           |            |     | but strongly            |           |
|           |            |     | recommended for         |           |
|           |            |     | pre-processing          |           |
|           |            |     | resources.              |           |
|           |            |     |                         |           |
|           |            |     | In the case of ML       |           |
|           |            |     | resources, this field   |           |
|           |            |     | is closely related to   |           |
|           |            |     | the performance field.  |           |
+-----------+------------+-----+-------------------------+-----------+
| V         | URI        | 0   | Link to a validation    | New STAC  |
| alidation |            | ..1 | report                  | property  |
+-----------+------------+-----+-------------------------+-----------+
| Model     | Chara      | 0   | Confi                   | New STAC  |
| conf      | cterString | ..1 | guration/initialisation | property  |
| iguration |            |     | data. How the model has |           |
|           |            |     | been parameterized      |           |
+-----------+------------+-----+-------------------------+-----------+
| Output    | URI        | 1.. | Link to output data (or | STAC      |
| data      |            | .\* | related metadata)       | asset     |
| obtained  |            |     | produced by execution   |           |
|           |            |     | of the a/p resource.    |           |
|           |            |     | This information is     |           |
|           |            |     | required for a better   |           |
|           |            |     | understanding of the    |           |
|           |            |     | a/p resource.           |           |
+-----------+------------+-----+-------------------------+-----------+
| Charac    | Chara      | 1   | Textual description of  | STAC      |
| teristics | cterString |     | the output data from    | asset     |
| of output |            |     | the resource.           | de        |
| data      |            |     |                         | scription |
+-----------+------------+-----+-------------------------+-----------+
| Pe        | Chara      | 0   | Result description and  | STAC      |
| rformance | cterString | ..1 | explanation, including  | Asset     |
|           |            |     | a detailed description  | (new      |
|           |            |     | of the hyperparameters  | sub-      |
|           |            |     | used, the run times,    | property) |
|           |            |     | the metrics used for    |           |
|           |            |     | evaluation, and the     |           |
|           |            |     | respective scores and   |           |
|           |            |     | performance.            |           |
+-----------+------------+-----+-------------------------+-----------+
| C         | Codelist   | 1   | Type of distribution    | STAC:     |
| onditions |            |     | license for the         | license   |
| for       |            |     | resource (e.g., MIT or  |           |
| access    |            |     | CC-BY).                 |           |
| and use   |            |     |                         |           |
+-----------+------------+-----+-------------------------+-----------+
| UseCo     | Chara      | 0.  | Possible constraints    | New STAC  |
| nstraints | cterString | ..1 | related to the use of   | property  |
|           |            |     | the resource (e.g., the |           |
|           |            |     | resource works only for |           |
|           |            |     | certain Input data      |           |
|           |            |     |                         |           |
|           |            |     | the resource            |           |
|           |            |     | needs specific Process  |           |
|           |            |     | of providing            |           |
|           |            |     | computational power)    |           |
+-----------+------------+-----+-------------------------+-----------+

# FAIRiCUBE Catalog for Processing/Analysis Resources

The architecture of the catalog for the processing/analysis resources
and the details of its implementation as well as its integration into
the FAIRiCUBE Hub and the procedure for metadata publication in the
catalog, are in all respects parallel to those described for the dataset
metadata in D4.2 Public Listing (Catalog) of FAIRiCUBE data resources.
Therefore, for these general aspects of the Catalog, reference is made
to D4.2, while the focus of this section is on where the metadata for
a/p resources can be accessed and queried, and the process for its
ingestion and update. The a/p resources metadata are accessible via the
[FAIRICUBE stac-fastapi browser](https://catalog.eoxhub.fairicube.eu/)
(see Figure 2 below).

![A white background with black text Description automatically
generated](media/image4.png){width="6.298611111111111in"
height="2.1805555555555554in"}

[]{#_Ref154052310 .anchor}Figure 2 : stac-fastapi

To facilitate discoverability by the users, they have been grouped into
two collections, one containing all machine learning resources ([ML
collection](https://catalog.eoxhub.fairicube.eu/collections/ML%20collection))
and the other containing all other types of resources e.g. preprocessing
algorithms ([no-ML
collection](https://catalog.eoxhub.fairicube.eu/collections/no-ML%20collection)).
In addition, aiming to facilitate the sharing of information on a/p
resources, a query tool has been developed that allows the metadata
information to be queried according to different criteria, e.g. based on
the type of algorithm used. This [query
tool](https://fairicube-kb.dev.epsilon-italia.it/query-tool),
illustrated in Figure 3 below, is part of the [FAIRICUBE Knowledge
Base](https://fairicube-kb.dev.epsilon-italia.it/) Services, which is
described in Deliverable 3.4.

![A screenshot of a computer Description automatically
generated](media/image5.png){width="6.298611111111111in"
height="1.9416666666666667in"}

[]{#_Ref154052327 .anchor}Figure 3 : FAIRiCUBE Knowledge Base Query Tool

**Process for the ingestion and update of the a/p resource MD**

Creating metadata for a new a/p resource as well as updating existing
metadata files is handled via a dedicated web application. Specifically,
the entry point for the user to create/update a metadata file is the
webGUI illustrated in Figure 4 below, analogous in all respects to the
webGUI for managing dataset metadata described in deliverable D5.2
Description of the datacube ingestion pipelines. This webGUI is
accessible only to logged users.

![](media/image6.png){width="5.057772309711286in"
height="2.867066929133858in"}

[]{#_Ref154052344 .anchor}Figure 4 : webGUI -- Landing page

Adding and updating of the a/p metadata happens via a dedicated a/p
metadata entry webform, which is displayed when clicking on the Add or
the Edit buttons. When the Edit button is clicked, the webform is
prefilled with the information of the metadata file to be updated.

**The a/p metadata entry webform**

The Python programming language, the Flask web micro-framework and the
Keycloak identity and access management solution were the software used
to create the a/p metadata entry form application. The a/p metadata
entry form application has an authentication system that verifies the
identity of a user either via GitHub credentials or via customized
credentials provided to partners on request.

This form contains all the fields for documenting an analysis and
processing resource described in Table 1, plus additional fields (namely
"Jupyter Notebook available" and "Compute resources consumed") that are
used to complete information about the a/p resource and for quality
checking the information provided in the form. In particular, the
"Compute resources consumed" allows the uploading of the CSV file with
the measurements of the computational resources consumed by the a/p
resource (see Figure 8). For the sake of readability, the web form is
illustrated using several figures, namely Figure 5, Figure 6, Figure 7,
Figure 8 and Figure 9: Screenshot of the a/p metadata webform (5).

![](media/image7.png){width="6.256944444444445in"
height="5.435416666666667in"}

[]{#_Ref154052368 .anchor}Figure 5 : Screenshot of the a/p metadata
webform (1)

![](media/image8.png){width="6.298611111111111in"
height="3.550762248468941in"}

[]{#_Ref154052378 .anchor}Figure 6 : Screenshot of the a/p metadata
webform (2)

![](media/image9.png){width="6.298611111111111in"
height="3.119770341207349in"}

[]{#_Ref154052382 .anchor}Figure 7 : Screenshot of the a/p metadata
webform (3)

![](media/image10.png){width="6.27566491688539in"
height="4.21259842519685in"}

[]{#_Ref154052384 .anchor}Figure 8 : Screenshot of the a/p metadata
webform (4)

![](media/image11.png){width="6.27566491688539in"
height="4.21259842519685in"}

[]{#_Ref185846163 .anchor}Figure 9: Screenshot of the a/p metadata
webform (5)

When the user confirms that the entry phase is completed, a check is
made to ensure that there are no inconsistencies in the information
provided and that the resource does not already exist in the Catalog.

A non-exhaustive list of inconsistencies for which quality checks are
implemented is provided below:

a.  A mandatory field is empty.

b.  The resource has the main category "Machine Learning" or "Deep
    Learning" and one or more of the related mandatory fields, namely
    "Architecture", "Approach" or "Performance", is empty.

c.  A Jupyter Notebook is available, but the "Example" field is empty.

d.  "Input data used" has a different number of items compared to
    "Characteristics of input data".

e.  "Output data obtained" has a different number of items compared to
    "Characteristics of output data".

> Should any of these test fail, the system shows an error page and
> allows the user to go back and edit the data.
>
> When no errors are raised, a page with a summary of the inserted
> information shows up. The user can choose whether to edit the entered
> values or start the process for creating and ingesting the metadata
> file by clicking on the \"Submit\" button.

The a/p metadata file ingestion is composed by four automatic (hidden to
the user) sub steps:

1.  Creation of the STAC-JSON metadata file, whose structure implements
    Table 1 and for which an example is provided in Annex 2.

2.  Uploading of the metadata file in the
    [FAIRiCUBE/resource-metadata/stac](https://github.com/FAIRiCUBE/resource-metadata/tree/main/stac)
    GitHub folder. This step is necessary for making the a/p resource
    metadata files available in the [FAIRiCUBE STAC Metadata
    Catalog](https://catalog.eoxhub.fairicube.eu/?.language=en). The
    contents of this catalog, in fact, are maintained in deputed GitHub
    repositories as static STAC-JSON files and exposed via GitHub pages
    through a dynamic web interface - i.e. the stac-fastapi Browser.

3.  Uploading of the required fields of the metadata file in the
    Knowledge Base PostgreSQL database. This step is necessary to make
    the resource available for the query tool in the FAIRiCUBE Knowledge
    Base. In particular, the database contains two tables, one with
    information on the resources and the other with information on the
    measurements (linked to the related resource by the "resource_id"
    foreign key). In this way, it is possible to query the measurements
    related to the computational resources consumed by the a/p resource
    using the Knowledge Base query tool.

4.  Uploading of the metadata file in a MongoDB database. This step
    allows to do a backup of the STAC-JSON file.

At the end of the four steps above, if no error is found, the system
shows an "upload successfully" message, with the link of the related a/p
resource metadata in the FAIRiCUBE Metadata Catalog as shown in Figure
10 below. The same procedure applies when updating a metadata, as the
existing file is replaced.

![](media/image12.png){width="4.225291994750656in"
height="3.0946380139982503in"}

[]{#_Ref154052438 .anchor}Figure 10 : successful upload message

# Summary and outlook 

To facilitate the sharing and reuse of FAIRiCUBE a/p resources, a
FAIRiCUBE Catalogue has been created, based on the STAC standard and
accessible from the FAIRiCUBE Hub, where all the resources can be
described by associated metadata documents. These describe the intended
use of the resources, their technical characteristics, the input data
used, the output data generated and all the other characteristics
necessary to accurately describe the resource. The specific metadata
elements have been formulated on the basis of a comprehensive list of
requirements from the use cases.

A dedicated web application has been developed to facilitate the
creation of metadata for new resources and the updating of existing
metadata files. At the time of writing, the development of the Catalog
has been finalized, and the list of metadata elements is complete, but
the metadata files for the a/p resources have yet to be provided by the
various use cases. Providing as complete and accurate metadata as
possible will be essential to facilitate the sharing and reuse of the
project\'s a/p resources and, more generally, of the use cases results.
As accurate a compilation as possible, including optional elements, is
the key to the effective reusability of the resources described.

# Annex 1: Existing Standards for Processing-Analysis Resources {#annex-1-existing-standards-for-processing-analysis-resources .list-paragraph}

## PROV {#prov .list-paragraph}

PROV, the W3C (semantic) standard for provenance data
(<https://www.w3.org/TR/2013/NOTE-prov-primer-20130430/> ) is widely
used within the research community. The core model consists of Entities,
Activities performed thereon, as well as the Agents executing these
activities upon the Entities as shown in Figure 11. While not directly
geared at describing the models utilized for data generation, as PROV is
meant to describe how things were created or delivered, we see the
concepts from this standard as relevant towards exposing details of the
Processing-Analysis Resources available within FAIRiCUBE.

![](media/image13.png){width="2.4722222222222223in"
height="1.5270833333333333in"}

The main concepts of PROV are described in the following subsections.

### Entities {#entities .list-paragraph}

In PROV, physical, digital, conceptual objects are called entities.
Examples of such entities are a web page, a chart, and a spellchecker.
Provenance records can describe the provenance of entities, and an
entity's provenance may refer to many other entities. For example, a
document D is an entity whose provenance refers to other entities such
as a chart inserted into D, and the dataset that was used to create that
chart. Entities may be described as having different attributes and be
described from different perspectives. For example, document D as stored
in my file system, the second version of document D, and D as an
evolving document, are three distinct entities for which we may describe
provenance.

### Activities {#activities .list-paragraph}

Activities are how entities come into existence and how their attributes
change to become new entities, often making use of previously existing
entities to achieve this. They are dynamic aspects of the world, such as
actions, processes, etc. For example, if the second version of document
D was generated by a translation from the first version of the document
in another language, then this translation is an activity.

### Usage and Generation {#usage-and-generation .list-paragraph}

Activities generate new entities. For example, writing a document brings
the document into existence, while revising the document brings a new
version into existence. Activities also make use of entities. For
example, revising a document to fix spelling mistakes uses the original
version of the document as well as a list of corrections. Generation
does not always occur at the end of an activity, and an activity may
generate entities part-way through. Likewise, usage does not always
occur at the beginning of an activity.

### Agents and Responsibility {#agents-and-responsibility .list-paragraph}

An agent can be a person, a piece of software, an inanimate object, an
organization, or other entities that may be ascribed responsibility.
When an agent has some responsibility for an activity, PROV says the
agent was associated with the activity, where several agents may be
associated with an activity and vice versa. Consider a chart displaying
some statistics regarding crime rates over time in a linear regression.
To represent the provenance of that chart, we could state that the
person who created the chart was an agent involved in its creation, and
that the software used to create the chart was also an agent involved in
that activity. An agent may be acting on behalf of others, e.g., an
employee on behalf of their organization, and we can express such chains
of responsibility in the provenance.

We can also describe that an entity is attributed to an agent to express
the agent\'s responsibility for that entity, possibly along with other
agents. This description can be understood as shorthand for saying that
the agent was responsible for the activity which generated the entity.
One may want to describe the provenance of an agent. For example, an
organization responsible for the creation of a report may evolve over
time as the report is written as some members leave and others join. To
make provenance assertions about an agent in PROV, the agent must be
declared explicitly both as an agent and as an entity.

### Roles {#roles .list-paragraph}

A role is a description of the function or the part that an entity
played in an activity. Roles specify the relationship between an entity
and an activity, i.e., how the activity used or generated the entity.
Roles also specify how agents are involved in an activity, qualifying
their participation in the activity or specifying for what aspect of it
each agent was responsible. For example, an agent may play the role of
\"editor\" in an activity that uses one entity in the role of \"document
to be edited\" and another in the role of \"addition to be made to the
document\", to generate a further entity in the role of \"edited
document\". Roles are application specific, so PROV does not define any
particular roles.

### Derivation and Revision {#derivation-and-revision .list-paragraph}

When one entity\'s existence, content, characteristics and so on are at
least partly due to another entity, then we say that the former was
derived from the latter. For example, one document may contain material
copied from another, and a chart was derived from the data that it
illustrates. PROV allows some common, specialized kinds of derivation to
be described. For example, a given entity, such as a document, may go
through multiple revisions over time. Between revisions, one or more
attributes of the entity may change. In PROV, the result of each
revision is a new entity. PROV allows one to relate those entities by
making a description that one was a revision of another. Another kind of
derivation is to say that one entity, a quotation, was quoted from
another entity, commonly a document.

### Plans {#plans .list-paragraph}

Activities may follow pre-defined procedures, such as recipes,
tutorials, instructions, or workflows. PROV refers to these, in general,
as plans, and allows the description that a plan was followed by agents
in executing an activity.

### Time {#time .list-paragraph}

Time is often a critical aspect of provenance. PROV allows the timing of
significant events to be described, including when an entity was
generated or used, or when an activity started and finished. For
example, the model can be used to describe when a new version of a
document was created (generation time), or when a document was edited
(start and end of the editing activity).

## Classical / Shallow ML {#classical-shallow-ml .list-paragraph}

For classical / shallow machine learning most practitioners use the same
algorithms (RF, SVM, XGBoost, CatBoost, etc.) and just share the
parameters for trained models directly (e.g., dumped in Python Pickle
format or JSON), or via R or Python Notebooks. Some of the larger
(shallow) ML tools (e.g., CatBoost) have their own exchange formats and
methods.

## PyTorch Model Zoo {#pytorch-model-zoo .list-paragraph}

The Model Zoo approach provided by PyTorch provides the interested user
with a limited set of concepts describing the available models:

-   **Model**: name of the model

-   **Type**: type of the model, unclear if there is a LOV for this, or
    just free text. Currently contains the following options:

    -   Activity Recognition

    -   Image Classification

    -   Image Segmentation

    -   Object Detection

    -   Sequence Classification

    -   Text Classification

    -   Token Classification

-   **Dataset**: name of the dataset the model operates on, but no link
    to this data or further description of the dataset. Currently
    contains the following values:

    -   AG_NEWS

    -   CAPTUM

    -   Charades

    -   COCO

    -   ImageNet

    -   MNIST

-   **Size**: size of the model

-   **Download**: link to mar or war file

-   **Sample Input**: suitable input data object. List contains images,
    texts and mp4 files

-   **Model Mode**: contains the following values:

    -   Eager

    -   Torchscripted

    -   Workflow

## Hugging Face Models {#hugging-face-models .list-paragraph}

Hugging Face has the mission to democratize good machine learning,
enabling wider uptake of the potential of ML. On the Hugging Face
Portal, models are described by the following tags:

-   **Tasks**: a wide array of different task types have been defined,
    utilizing the following classification:

    -   Computer Vision

        -   Image Classification

        -   Image Segmentation

        -   Zero-Shot Image Classification

        -   Image-to-Image

        -   Unconditional Image Generation

        -   Object Detection

        -   Video Classification

        -   Depth Estimation

    -   Natural Language Processing

        -   Translation

        -   Fill-Mask

        -   Token Classification

        -   Sentence Similarity

        -   Question Answering

        -   Summarization

        -   Zero-Shot Classification

        -   Text Classification

        -   Text2Text Generation

        -   Text Generation

        -   Conversational

        -   Table Question Answering

    -   Audio

        -   Automatic Speech Recognition

        -   Audio Classification

        -   Text-to-Speech

        -   Audio-to-Audio

        -   Voice Activity Detection

    -   Multimodal

        -   Feature Extraction

        -   Text-to-Image

        -   Visual Question Answering

        -   Image-to-Text

        -   Document Question Answering

    -   Tabular

        -   Tabular Classification

        -   Tabular Regression

    -   Reinforcement Learning

        -   Reinforcement Learning

        -   Robotics

-   **Libraries**: Contains the following list: PyTorch, TensorFlow,
    JAX, Transformers, TensorBoard, Stable-Baselines3, Diffusers,
    Sentence Transformers, ONNX, ML-Agents, Keras, Timm, ESPnet, spaCy,
    Sample Factory, Adapter Transformers, Rust, Scikit-learn, NeMo,
    Joblib, fastai, Flair, speechbrain, Graphcore, Safetensors, Fairseq,
    Stanza, PaddlePaddle, PaddleNLP, Core ML, TF Lite, Habana, Asteroid,
    TensorFlowTTS, allenNLP

-   **Datasets**: List of datasets utilized by the models being
    described

-   **Languages**: Tags for the human languages utilized in the models.
    These seem to be free text tags, as it's an eclectic mix of language
    (and dialect) names and language codes. Strange is that there are
    many languages with 0 models (if these are true tags, I'd expect to
    find values for all entries)

-   **Licenses**: Types of licenses under which the models are made
    available. Current list is comprised of: apache-2.0, mit,
    creativeml-openrail-m, afl-3.0, cc-by-4.0, openrail, other,
    cc-by-sa-4.0, cc-by-nc-sa-4.0, cc-by-nc-4.0, gpl-3.0, artistic-2.0,
    cc, bigscience-bloom-rail-1.0, bsd-3-clause, cc0-1.0,
    bigscience-openrail-m, wtfpl, agpl-3.0, unlicense, gpl, bsl-1.0,
    openrail++, cc-by-sa-3.0, bsd, cc-by-3.0, bsd-2-clause,
    cc-by-nc-3.0, lgpl-3.0, gpl-2.0, cc-by-2.0, osl-3.0,
    cc-by-nc-nd-4.0, cc-by-nc-sa-3.0, lgpl, bsd-3-clause-clear, lgpl-lr,
    ecl-2.0, pddl, c-uda, isc, gfdl, mpl-2.0, cc-by-nd-4.0, ms-pl,
    odc-by, zlib, odbl, cc-by-nc-sa-2.0, ncsa, cc-by-nc-2.0, cc-by-2.5,
    ofl-1.1, epl-1.0, cc-by-nc-nd-3.0, eupl-1.1, postgresql, lgpl-2.1,
    epl-2.0

-   **Other**: undefined grab-bag of concepts, current contents:
    AutoTrain Compatible, Eval Results, has a Space, Carbon Emissions

While not available for models, the **Subtask** concept is provided for
datasets, with the following tags contained: language-modeling,
multi-class-classification, extractive-qa, named-entity-recognition,
sentiment-classification, natural-language-inference, open-domain-qa,
multi-label-classification, topic-classification,
masked-language-modeling, multiple-choice-qa, closed-domain-qa,
text-scoring, closed-book-qa, open-book-qa,
tabular-multi-class-classification, tabular-multi-label-classification,
fact-checking-retrieval, entity-linking-retrieval,
semantic-similarity-scoring, fact-checking, intent-classification,
news-articles-summarization, multi-class-image-classification,
dialogue-modeling, semantic-similarity-classification, part-of-speech,
document-retrieval, image-captioning, parsing, hate-speech-detection,
text-simplification, sentiment-analysis, sentiment-scoring,
abstractive-qa, dialogue-generation, multi-input-text-classification,
acceptability-classification, speaker-identification, slot-filling,
explanation-generation, multi-label-image-classification, lemmatization,
coreference-resolution, semantic-segmentation,
open-domain-abstractive-qa, news-articles-headline-generation,
visual-question-answering, audio-emotion-recognition, rdf-to-text,
instance-segmentation, word-sense-disambiguation, keyword-spotting,
face-detection, multivariate-time-series-forecasting,
utterance-retrieval, multiple-choice-coreference-resolution,
univariate-time-series-forecasting, entity-linking-classification,
tabular-single-column-regression, audio-intent-classification,
document-question-answering, task-planning

## ONNX Open Neural Network Exchange {#onnx-open-neural-network-exchange .list-paragraph}

ONNX is a community project running under the Linux Foundation projects
for Open-Source Innovation in Artificial Intelligence and Data. ONNX is
an open format built to represent machine learning models. ONNX defines
a common set of operators - the building blocks of machine learning and
deep learning models - and a common file format to enable AI developers
to use models with a variety of frameworks, tools, runtimes, and
compilers.

ONNX provides a definition of an extensible computation graph model, as
well as definitions of built-in operators and standard data types. Each
computation dataflow graph is structured as a list of nodes that form an
acyclic graph. Nodes have one or more inputs and one or more outputs.
Each node is a call to an operator. The graph also has metadata to help
document its purpose, author, etc. Operators are implemented externally
to the graph, but the set of built-in operators are portable across
frameworks. Every framework supporting ONNX provides implementations of
these operators on the applicable data types.

![](media/image2.png){width="6.298611111111111in"
height="1.0763888888888888in"}Figure 12 we provide an example
visualization utilizing ONNX. For the purposes of the FAIRiCUBE Catalog
on processing-analysis resources, the level of detail foreseen by ONNX
seems excessive, as the focus of this standard is on explicitly
describing the individual processing steps instead of providing more
generalized information on the functionality of the model being
described.

## Weights and Biases {#weights-and-biases .list-paragraph}

Weights and Biases (https://wandb.ai) help keep track of machine
learning experimentation and repeatability. This is especially important
when including hyper-parameter sweeps.

## Provenance on Notebooks {#provenance-on-notebooks .list-paragraph}

There have also already been some attempts to record provenance on
Notebooks:

-   http://learningsys.org/nips17/assets/papers/paper_13.pdf

-   https://www.scitepress.org/PublicationsDetail.aspx?ID=oNxrDLTZgns=&t=1

    -   https://github.com/fusion-jena/MLProvLab

# Annex 2: STAC UML {#annex-2-stac-uml .list-paragraph}

![A screenshot of a computer Description automatically
generated](media/image14.png){width="6.298611111111111in"
height="4.836805555555555in"}

# Annex 3: Example of STAC-JSON file {#annex-3-example-of-stac-json-file .list-paragraph}

{

\"type\": \"Feature\",

\"stac_version\": \"1.0.0\",

\"stac_extensions\": \[

\"https://stac-extensions.github.io/ml-model/v1.0.0/schema.json\"

\],

\"id\": \"lenet_classifier\",

\"collection\": \"ML collection\",

\"geometry\": {

\"type\": \"Polygon\",

\"coordinates\": \[\[\[

\-180,-90\],\[-180,90\],\[180,90\],\[180,-90\],\[-180,-90\]\]\]},

\"properties\": {

\"provider\": \"epsit\",

\"use-case\": \"common\",

\"title\": \"LeNet Classifier\",

\"description\": \"Multi-layer Convolutional Neural Network for image
classification\",

\"main-category\": \"Deep Learning\",

\"datetime\": \"2023-04-04\",

\"keywords\": \[

\"classification\",

\"CNN\",

\"LeNet\"\],

\"platform\": \"Google Colab\",

\"framework\": \"Keras\",

\"algorithm\": \"LeNet\",

\"license\": \"CC-BY-4.0\",

"validation":"",

\"ml-model:type\": \"ml-model\",

\"ml-model:learning_approach\": \"supervised\",

\"ml-model:prediction_type\": \"classification\",

\"ml-model:architecture\": \"CNN - Convolutional-Neural-Network\",

\"ml-model:training-processor-type\": \"gpu\",

\"ml-model:training-os\": \"linux\",

\"use-constraints\": \"\",

\"model-configuration\": \"\"

},

\"links\": \[

{\"rel\": \"root\",

\"href\": \"./catalog.json\",

\"type\": \"application/json\",

\"title\": \"Root\"

},

{

\"rel\": \"parent\",

\"href\": \"./catalog.json\",

\"type\": \"application/json\",

\"title\": \"ML collection\"

},

{

\"href\": \"https://en.wikipedia.org/wiki/LeNet\",

\"rel\": \"about\",

\"type\": \"text/html\",

\"title\": \"Reference link\"

},

{

\"href\":
\"https://github.com/cozzolinoac11/wildfire_prediction/blob/main/ann.ipynb\",

\"rel\": \"about\",

\"type\": \"text/html\",

\"title\": \"Example\"}\],

\"assets\": {

\"input-data-used\": {

\"href\":
\"https://public.epsilon-italia.it/FAIRiCUBE/wildfire-classification/data_numpy.zip\",

\"type\": \"application/json\",

\"title\": \"Input data used\",

\"description\": \"Numpy arrays. (Perfectly) balanced classes.\",

\"biases-and-ethical-aspects\": \"\",

\"roles\": \[\"data\"\]},

\"model-checkpoint\": {

\"href\": \"http://www.epsilon-italia.it/public/model.zip\",

\"type\": \"application/octet-stream\",

\"title\": \"Model\",

\"description\": \"Keras model for wildfire or nowildfire
classification. The model gets in input a dataset as numpy arrays
(dimension 100x100x3) and returns the predicted labels.\",

\"performance\": \"Accuracy score: 0.9505 (validation). Running time: 2
min for 23 training epochs with early stopping (total number of epochs:
50) on a gpu Nvidia a100. Modified hyperparameters: Input shape:
(100,100,3); Optimizer: \'adam\'; batch size: 128. Train-test-valid
split: 70-15-15. Loss function: sparse_categorical_crossentropy.\",

\"roles\": \[\"ml-model:checkpoint\"\]

}}}

[^1]: <https://stacspec.org/en>

[^2]: This resource should be adapted in case of geo-referenced images.

[^3]: <https://stacspec.org/en>

[^4]: <https://github.com/stac-extensions/ml-model>
