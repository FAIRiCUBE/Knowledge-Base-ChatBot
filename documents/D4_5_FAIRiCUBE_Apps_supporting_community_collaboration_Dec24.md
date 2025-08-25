![](media/image1.png){width="4.330555555555556in"
height="3.2152777777777777in"}

FAIRICUBE --\
F.A.I.R. INFORMATION CUBES

WP4 Share

D4.5 Apps to support community collaboration platform

Deliverable Lead: EOX

Deliverable due date: 31/12/2024

Version: 2.4

11/12/2024

# Document Control Page

+-------------+--------------------------------------------------------+
| > Document  |                                                        |
| > Control   |                                                        |
| > Page      |                                                        |
+=============+========================================================+
| > Title     | > D4.5 Apps to support community collaboration         |
|             | > platform                                             |
+-------------+--------------------------------------------------------+
| > Creator   | > EOX                                                  |
+-------------+--------------------------------------------------------+
| >           | > Based on the collected requirements, new apps, based |
| Description | > on existing Open-Source software, are configured,    |
|             | > and offered for deployment in users' workspaces on   |
|             | > the FAIRiCUBE HUB. The apps themselves will be       |
|             | > released as Open-Source on GitHub again. Care will   |
|             | > be taken to assure close integration of ML           |
|             | > capabilities with the data resources being provided. |
+-------------+--------------------------------------------------------+
| > Publisher | > "FAIRICUBE -- F.A.I.R. information cubes" Consortium |
+-------------+--------------------------------------------------------+
| > C         | > All partners                                         |
| ontributors |                                                        |
+-------------+--------------------------------------------------------+
| > Date of   | > 2024-12-31                                           |
| > delivery  |                                                        |
+-------------+--------------------------------------------------------+
| > Type      | > Text                                                 |
+-------------+--------------------------------------------------------+
| > Language  | > EN-GB                                                |
+-------------+--------------------------------------------------------+
| > Rights    | > Copyright "FAIRICUBE -- F.A.I.R. information cubes"  |
+-------------+--------------------------------------------------------+
| > Audience  | > ☒ Public                                             |
|             | >                                                      |
|             | > ☐ Confidential                                       |
|             | >                                                      |
|             | > ☐ Classified                                         |
+-------------+--------------------------------------------------------+
| > Status    | > ☐ In Progress                                        |
|             | >                                                      |
|             | > ☐ For Review                                         |
|             | >                                                      |
|             | > ☒ For Approval                                       |
|             | >                                                      |
|             | > ☐ Approved                                           |
+-------------+--------------------------------------------------------+

+-------+----------+-------------------+------------------------------+
| > Rev |          |                   |                              |
| ision |          |                   |                              |
| > Hi  |          |                   |                              |
| story |          |                   |                              |
+=======+==========+===================+==============================+
| > Ve  | > Date   | > Modified by     | Comments                     |
| rsion |          |                   |                              |
+-------+----------+-------------------+------------------------------+
| > 0.1 | > 24     | > Christian       | Initial release              |
|       | /11/2023 | > Schiller (EOX)  |                              |
+-------+----------+-------------------+------------------------------+
| > 0.2 | > 27     | > Christian       | Added Apache Superset        |
|       | /11/2023 | > Schiller (EOX)  | description                  |
+-------+----------+-------------------+------------------------------+
| > 0.3 | > 07     | > Christian       | Added Requirements collected |
|       | /12/2023 | > Schiller (EOX)  | at Meeting 05/12/2023        |
+-------+----------+-------------------+------------------------------+
| > 1.0 | > 15     | > Jaume Targa     | Internal review              |
|       | /12/2023 |                   |                              |
+-------+----------+-------------------+------------------------------+
| > 1.1 | > 28     | > Christian       | Restructuring Chapters       |
|       | /05/2024 | > Schiller (EOX)  |                              |
|       |          |                   | Add introduction of          |
|       |          |                   | collaborative setup          |
|       |          |                   |                              |
|       |          |                   | Description of collaborative |
|       |          |                   | tools\                       |
|       |          |                   | added chapter on rasdaman    |
|       |          |                   | ML-tools & UDF\              |
|       |          |                   | List of Requirements placed  |
|       |          |                   | in Annex                     |
+-------+----------+-------------------+------------------------------+
| > 2.0 | > 22     | > Jaume Targa,    | Review and format checking   |
|       | /06/2024 | > Stefan Jetschny |                              |
+-------+----------+-------------------+------------------------------+
| > 2.1 | > 22     | > Christian       | Updated to reflect latest    |
|       | /11/2024 | > Schiller (EOX)  | status; added Sections:      |
|       |          |                   | Landing page, Knowledge      |
|       |          |                   | Base, Java Runtime           |
|       |          |                   | Environment, Headless        |
|       |          |                   | Execution of notebooks,      |
|       |          |                   | Common tools developed       |
+-------+----------+-------------------+------------------------------+
| > 2.2 | > 28     | > Stefan Jetschny | Review and format checking   |
|       | /11/2024 |                   |                              |
+-------+----------+-------------------+------------------------------+
| > 2.3 | > 29     | > Christian       | changes in Introduction\     |
|       | /11/2024 | > Schiller (EOX)  | added Catalog Editor\        |
|       |          |                   | added Section Summary and    |
|       |          |                   | Outlook                      |
+-------+----------+-------------------+------------------------------+
| > ‍2.4 | > 11     | > Stefan          | Final review                 |
|       | /12/2024 | > Jetschny, Jaume |                              |
|       |          | > Targa           |                              |
+-------+----------+-------------------+------------------------------+
| > ‍    |          |                   |                              |
+-------+----------+-------------------+------------------------------+

# Disclaimer

This document is issued within the frame and for the purpose of the
FAIRICUBE project. This project has received funding from the European
Union's Horizon research and innovation programme under grant agreement
No. 101059238. The opinions expressed and arguments employed herein do
not necessarily reflect the official views of the European Commission.

This document and its content are the property of the FAIRICUBE
Consortium. All rights relevant to this document are determined by the
applicable laws. Access to this document does not grant any right or
license to the document or its contents. This document or its contents
are not to be used or treated in any manner inconsistent with the rights
or interests of the FAIRICUBE Consortium or the Partners' detriment and
are not to be disclosed externally without prior written consent from
the FAIRICUBE Partners. Each FAIRICUBE Partner may use this document in
conformity with the FAIRICUBE Consortium Grant Agreement provisions.

# Table of Contents

[1 Introduction [5](#introduction)](#introduction)

[1.1 Landing Page [5](#_Toc184757366)](#_Toc184757366)

[1.2 Setup for Collaboration
[6](#setup-for-collaboration)](#setup-for-collaboration)

[2 General applications provided
[8](#general-applications-provided)](#general-applications-provided)

[2.1 Apache Superset [8](#apache-superset)](#apache-superset)

[2.2 Grafana [8](#grafana)](#grafana)

[2.3 EO-Dashboard [8](#eo-dashboard)](#eo-dashboard)

[2.4 Jupyter Notebook Viewer
[8](#jupyter-notebook-viewer)](#jupyter-notebook-viewer)

[2.5 Read-the-Docs (Community Collaboration Platform)
[9](#read-the-docs-community-collaboration-platform)](#read-the-docs-community-collaboration-platform)

[2.6 Knowledge Base [9](#knowledge-base)](#knowledge-base)

[2.7 Java Runtime Environment (non-GUI)
[9](#java-runtime-environment-non-gui)](#java-runtime-environment-non-gui)

[2.8 Headless Execution of notebooks (scripts)
[10](#headless-execution-of-notebooks-scripts)](#headless-execution-of-notebooks-scripts)

[2.9 Common tools developed in FAIRiCUBE
[10](#common-tools-developed-in-fairicube)](#common-tools-developed-in-fairicube)

[2.10 Data Catalog and Catalog Editor
[10](#data-catalog-and-catalog-editor)](#data-catalog-and-catalog-editor)

[3 ML-Toolkits available on the FAIRiCUBE Hub
[14](#ml-toolkits-available-on-the-fairicube-hub)](#ml-toolkits-available-on-the-fairicube-hub)

[3.1 MLflow [14](#mlflow)](#mlflow)

[3.2 TensorBoard [15](#tensorboard)](#tensorboard)

[3.3 DVC [16](#dvc)](#dvc)

[3.4 rasdaman ML tools [17](#rasdaman-ml-tools)](#rasdaman-ml-tools)

[4 Summary and Outlook [18](#summary-and-outlook)](#summary-and-outlook)

# List of Figures

Figure 1: FAIRiCUBE Hub - Landing Page [5](#_Ref183680936)

Figure 2: (a) Landing sub-page providing access to FAIRiCUBE Datacube
catalogs. (b) showing the access to analytics and processing frameworks
(e.g. Jupyter Hubs) [6](#_Toc183680931)

Figure 3: (a) Landing sub-page providing access to the different
Documentations and the FAIRiCUBE general project information. (b)
showing the access to the Blog section of FAIRiCUBE [6](#_Ref183680937)

Figure 4: landing page of the FAIRiCUBE catalog, showing the collections
available in FAIRiCUBE [11](#_Ref1836809371)

Figure 5: First page of the data access catalog, showing some of the
available datasets [11](#_Ref18368093711)

Figure 6: (a) showing the landing page of the Catalog Editor. (b-l)
showing the Catalog Editor in editing mode with all the fields of
metadata information available for of a dataset [13](#_Ref183680937111)

Figure 7: MLflow - Experiments tracking interface [15](#_Toc183680933)

Figure 8: TensorBoard -- Time series evaluation [16](#_Toc170725604)

Figure 9: Sample model application as a query result (left) and
schematic WCPS query generating it. [17](#Ref_Figure32_label_and_number)

# Introduction

This deliverable describes the availability of software, tools,
notebooks, and applications provided via the FAIRiCUBE Hub and its
services. Since most of the tools will be run encapsulated (e.g. Docker
container) in the cloud, a detailed technical evaluation of each tool is
not required from the supplier/operator side. A dedicated feasibility
study for each software tool is therefore also not deemed necessary.
Highly specialised software (e.g. like \"vcftools\" for genetic
analysis) are simply placed inside container and then provided to the
user. However, is has to be noted that the FAIRiCUBE Hub and its
applications are web-based services which limit the choice of
application running inside of containers, i.e. software tools using
non-browser-based graphical interfaces are not possible, except running
solely from the command-line. The apps developed during FAIRiCUBE will
be released as Open-Source on GitHub again. Care will be taken to ensure
close integration of ML capabilities with the data resources being
provided.

## Landing Page

As a general entry point to all services and information provided by
FAIRiCUBE a common landing page is provided, which can be reached at:
<https://hub.fairicube.eu/>. From here all other FAIRiCUBE resources can
be reached. A visual overview of the services is shown in Figure 1 -
Figure 3. The FAIRiCUBE Hub landing page will be update to further
completion driven by the Use Case experience, i.e. a data driven Use
Case presentation, a common visualization for gridded data hosted on the
EOX Lab ([https://vis.fairicube.eu](https://vis.fairicube.eu/)) and the
validation framework. The snapshot images therefore represent the
current state as of publication date of this deliverable.

![](media/image2.png){width="3.5536034558180227in"
height="3.7281496062992128in"}

[]{#_Ref183680936 .anchor}Figure 1: FAIRiCUBE Hub - Landing Page

![](media/image3.png){width="2.5590277777777777in" height="1.93125in"}
(a) ![](media/image4.png){width="2.5590277777777777in"
height="1.926388888888889in"} (b)

[]{#_Toc183680931 .anchor}Figure 2: (a) Landing sub-page providing
access to FAIRiCUBE Data Cube catalogs. (b) showing the access to
analytics and processing frameworks (e.g. Jupyter Hubs)

![](media/image5.png){width="2.5590277777777777in"
height="1.929861111111111in"} (a)
![](media/image6.png){width="2.5590277777777777in"
height="1.2166666666666666in"} (b)

[]{#_Ref183680937 .anchor}Figure 3: (a) Landing sub-page providing
access to the different Documentations and the FAIRiCUBE general project
information. (b) showing the access to the Blog section of FAIRiCUBE

## Setup for Collaboration 

Although not directly an App it has to be mentioned here that the
FAIRiCUBE Lab does provide the direct opportunity to share data and code
within the FAIRiCUBE community. All Use Cases utilizing the JupyterLab
instance in FAIRiCUBE have access to a Use Case specific storage as well
as to a FAIRiCUBE-wide common storage space. These storage areas exist
beside the commonly available space to share information via the
available FAIRiCUBE GitHub repositories. Furthermore, the implemented
Jupyter Notebook Viewer (for details see Chapter 2.4) represents a tool
which renders Jupyter notebooks as static web pages. These are then
easily shared.

For the collaborative documentation of processes, code and know-how
within FAIRiCUBE, a Read-the-Docs
(<https://fairicube.readthedocs.io/en/latest/>) instance is setup to be
used and filled with information provided directly by any FAIRiCUBE user
(for details see Section 2.5). In addition, the Knowledge Base (for
details see Section 2.6) provides access to further information and
usage scenarios as well as provides extensive search capabilities.
Together, the Read-the-Docs collection and the Knowledge Base form a
\"Digital Library\".

While some tools are very Use Case specific (e.g. vcftools, for working
with complex genetic variation data), others are of general purpose. For
example, Grafana can be used for the presentations of measurement and
graphics of all kinds of information. Collaboration inside UC teams, as
well as across UC teams is fostered by either direct information
exchange between the UC\'s (e.g. commonly shared folders and buckets)
and/or by providing descriptions of the developed tools via the
Read-the-Docs collaboration platform or via the Knowledge Base. The
respective code of these developed tools is commonly available via the
GitHub repository (e.g. <https://github.com/FAIRiCUBE/common-code>)

Request for the provisioning of additional tools via the FAIRiCUBE Hub
can always be submitted to the operations team using GitHub Issues
(<https://github.com/FAIRiCUBE/FAIRiCUBE-Hub-issue-tracker)>

2.  # General applications provided

    1.  ## Apache Superset

Based on an already issued special request for a tool to support easy
data visualization by UC2 the Apache Superset has been deployed and made
available for UC-2 users. Apache Superset is an open-source software
application for data exploration and data visualization able to handle
data at a petabyte scale (big data). It makes it easy to explore your
data, using either a simple no-code viz builder or a state-of-the-art
SQL IDE. In addition, Superset can connect to any SQL-based databases
including modern cloud-native databases and engines. It ships with 40+
pre-installed visualization types that make it easy for users of all
skill sets to explore and visualize their data, from simple line charts
to highly detailed geospatial charts. Plug-in architecture makes it easy
to build custom visualizations.

## Grafana

Grafana is a multi-platform, open-source analytics, and interactive
visualization web application. The tool is very flexible and provides a
multitude of APIs to allow various data sources to be utilized and
integrated. In addition, it provides many possibilities to present the
data and also integrate additional external resources (e.g. Wikipedia)
directly or scrape their content to present it in a specific way. It can
produce charts, graphs, and alerts for the web when connected to
supported data sources. As a visualization tool, Grafana can be used as
a component in an application stack together with tools providing the
respective static or dynamic input. Complex dashboards can be built by
end users, with the aid of interactive query builders.

## EO-Dashboard

The Earth Observing Dashboard (EO-Dash) has been designed and developed
by EOX in the course of the coronavirus pandemic as an effort of the
three space agencies, ESA, JAXA, and NASA, to strengthen our global
understanding of global environmental changes and other societal
challenges impacting our planet. The initial
[Race-Dashboard[^1]](https://race.esa.int/), was first developed to
provide information observable from Space about the Covid-19 Crisis e.g.
the reduced discharge of CO2 due to traffic limitations, monitoring of
empty parking lost etc. However, EO-Dash has thereafter evolved further
and has been used for various purposes due to its flexibility and ease
of setup and use. EODash is intended to handle and present data provided
by users (third parties) who want to tell a story about a distinct event
or occurrence. EO-Dash demonstrates how the use of Earth observation
data can help shed new lights on societal and economic changes taking
place.

## Jupyter Notebook Viewer

Jupyter Notebooks extend the console-based approach to interactive
computing with a web-based application, with which the entire process
can be recorded: from developing and executing the code to documenting
and presenting the results. The Notebook Viewer renders the interactive
notebooks and creates static web pages. These static web pages can then
easily made available to other users for reading without the danger that
another user will destroy/change the notebook by accident. However,
since notebooks in FAIRiCUBE are stored in GitHub all offered notebooks
are fully accessible for usage by others.

## Read-the-Docs (Community Collaboration Platform)

Read-the-Docs is a simple tool for building, hosting, and sharing
documentation. It is based on Mark-down language and therefore does not
need special training. The documents can be hosted easily in
GitHub/GitLab and when connected to the read-the-docs site will be built
and deployed automatically after every change. All users which have
access to the GitHub/GitLab location can add and edit the documentation.
Texts, images, code, and even Jupyter Notebooks can all be included,
managed, and presented in a read-the-docs documentation.

The information provided is specifically aimed to the exchange of
information between experts using data cubes for environmental studies.
Additionally, it provides guidance on how to use the FAIRICBE Hub.
Currently it provides the following sections: Overview, Use Cases, User
Guide, Self-Training, AI Toolkit, GeoDatacubes Toolkit, Lessons Learnt
and Tips &Tricks, and External Resources. At the time of writing the
Read-the-Docs documentation aka. \"Community Collaboration Platform\"
can be reached at <https://fairicube.readthedocs.io/en/latest/>.

## Knowledge Base

Driven by the needs and built on the experience and understanding of the
project use cases, the Knowledge Base aims to provide knowledge enabling
the extraction of real value and insights from large and complex data
collections, with a focus on data-driven machine learning (ML) model
generation. The primary purpose of the KB is to help users with diverse
levels of expertise understand if and how it is possible to reuse the
experience of and the resources developed by the use cases for their
specific needs. To meet the needs of diverse types of users, the core of
the Knowledge Base is a query service (Query Tool), which allows the
project\'s processing resources to be interactively searched in a
variety of ways, depending on the user\'s level of expertise.

The Knowledge Base content is grouped into the following sections: Use
Cases, Query Tool, Self-training Library, Tips & Tricks, Metadata
Catalog, GitHub Project. At the time of writing, a demo application of
the [FAIRICUBE Processing Knowledge
Base](https://fairicube-kb.dev.epsilon-italia.it/)
(https://fairicube-kb.dev.epsilon-italia.it/) is made available online.

## Java Runtime Environment (non-GUI)

On request of a Use Case user to run specialised, Java based software a
Java Runtime Environment (JRE) was made available to the Use Case.
However, since FAIRiCUBE Hub is a Web-Application, regular Java
programs, having Graphical User Interfaces (GUI), cannot be run
natively. However, non-GUI Java applications can be run from a
command-line, supplying necessary parameters and data either via the
command-line or via a configuration file. This setup allows the Use Case
to perform the required calculation using their specialised software
tools.

## Headless Execution of notebooks (scripts)

Since FAIRiCUBE Hub is a Web-Application accessible via a Browser,
processing scripts will only run if the Browser is open and active. This
somehow prevents the usage of large datasets or complicated algorithms
which might require a long time. Therefore, FAIRiCUBE Hub provides a
\"Headless Execution Mode\" which allows the user to submit a script to
the underlying processing engine, without the requirement of an active
and open Browser. The scripts (Jupyter notebooks) need only some minor
additions (changes), which do not interfere with the regular,
interactive usage of a Jupyter Notebook, to be submitted to the headless
execution mode.

## Common tools developed in FAIRiCUBE

A whole set of notebooks has been and is actively developed during the
FAIRiCUBE project. These tools are made available by the via GitHub
(<https://github.com/FAIRiCUBE/common-code>) and can currently be used
by other FAIRiCUBE members. Since this is an ongoing activity a listing
of available tools is not provided here. However, a more comprehensive
description of the development process can be found in the deliverable
\"D3.3_Processing and ML applications.docx\". In general, the
descriptions of available tools and their usage can be found in the
FAIRiCUBE Read-the-Docs collection and are provided by the respective
developers. Also, the FAIRiCUBE catalog for a/p resources are a valuable
tool to search and find such common tools developed in FAIRiCUBE.

## Data Catalog and Catalog Editor

Users of FAIRiCUBE will frequently be confronted with metadata, either
to check the availability of a dataset in the catalog or to request or
provide metadata information about datasets needed or generated. The
FAIRiCUBE catalog is based on the newly evolving STAC (Spatiotemporal
Asset Catalog), which represents an open specification to describe
geospatial information, and has therefore been seen as \"in progress\"
since STAC is evolving fast and changes occur frequently.

In order to enable users to more easily handle the challenge of
providing the relevant information to the FAIRiCUBE catalog a \"Catalog
Editor\" Interface has been developed. This Catalog Editor supplies a
web-based GUI which provides a multitude of fields to be filled out. by
the user. These fields render helpful information concurrently with
plausibility checks while the information is entered by the user. The
metadata entries are stored for further processing or editing until the
datasets is deemed ready and gets submitted to a GitHub issue. There a
last manual check by the \"ingestion handling partners\" will be
performed prior to the final merge and closing of the respective issue.
Any comments which might have been associated with the merge respective
GitHub issue will remain available.

The Catalog is accessible publicly at
[https://catalog.eoxhub.fairicube.eu](https://catalog.eoxhub.fairicube.eu/),
and the Catalog Editor is accessible for FAIRiCUBE users at
<https://catalog-editor.eoxhub.fairicube.eu/>. The underlying meta data
concept and implementation details of the catalog and catalog editor are
described in *D4.2 Public Listing (Catalog) of FAIRiCUBE data*
resources.

![](media/image7.png){width="6.298611111111111in"
height="2.629861111111111in"}

[]{#_Ref1836809371 .anchor}Figure 4: landing page of the FAIRiCUBE
catalog, showing the collections available in FAIRiCUBE

![](media/image8.png){width="6.298611111111111in"
height="3.598611111111111in"}

[]{#_Ref18368093711 .anchor}Figure 5: First page of the data access
catalog, showing some of the available datasets

![](media/image9.png){width="2.9180555555555556in"
height="2.308333333333333in"}(a)
![](media/image10.png){width="2.923611111111111in"
height="2.7993055555555557in"}(b)

![](media/image11.png){width="2.9159722222222224in"
height="2.6743055555555557in"}(c)
![](media/image12.png){width="2.93125in"
height="2.9506944444444443in"}(d)

![](media/image13.png){width="2.923611111111111in"
height="2.5756944444444443in"}(e)
![](media/image14.png){width="2.972916666666667in"
height="2.582638888888889in"}(f)

![](media/image15.png){width="2.892361111111111in"
height="2.34375in"}(g)
![](media/image16.png){width="2.9159722222222224in"
height="2.5006944444444446in"}(h)

![](media/image17.png){width="2.959722222222222in"
height="2.829861111111111in"}(i)
![](media/image18.png){width="2.9444444444444446in"
height="2.83125in"}(j)

![](media/image19.png){width="2.873611111111111in"
height="2.810416666666667in"}(k)
![](media/image20.png){width="2.9854166666666666in"
height="2.7319444444444443in"}(l)

[]{#_Ref183680937111 .anchor}Figure 6: (a) showing the landing page of
the Catalog Editor. (b-l) showing the Catalog Editor in editing mode
with all the fields of metadata information available for of a dataset

# ML-Toolkits available on the FAIRiCUBE Hub

Each Use Case team decides which apps shall be made available. At the
time of writing two apps have been made available, currently associated
with UC2. Two of these apps are MLflow and TensorBoard, for which a
short introduction is provided in the next sub-chapters. An additional
option to use Machine learning is setup on rasdaman (3.4) using User
Defined Functions (UDFs) to provide the PyTorch framework to users. Not
ML but also a helpful tool is DVC, a Data Version Control system, for ML
modelling and collaborative data management like ML artefacts, is also
described here in this section.

## MLflow 

MLflow is an open-source platform for managing the end-to-end machine
learning life cycle. It allows the user to track experiments, package
code into reproducible runs, and share and deploy models. MLflow can be
incorporated into Jupyter notebooks or other code and supports multiple
programming languages. It is widely used in industry and academia and is
constantly evolving to support the latest trends and technologies in the
field of machine learning. MLflow supports the MLOps pipelines
particularly to log and evaluate experiment runs as well as to store
models in a registry​. Persistent MLflow deployments are made available
on the team level to allow each team member to compare their experiments
with those of the other team members and to use the trained models of
others. At a high level, MLflow consists of four main components:
tracking, projects, models, and registry. All components can be accessed
via Python code in the FAIRiCUBE Lab.

**MLflow Tracking:** The MLflow tracking component allows users to log
and track training parameters, code, and output metrics from their
machine learning experiments. It provides an API for Python, R, and
other languages, as well as a UI for visualising experiments and
comparing different runs. The tracking server can store data in various
backends, including a local file system, an Amazon S3 bucket, or a
PostgreSQL database. MLflow Tracking uses the concept of runs, which are
executions of some piece of data science code, e.g., training of models.
MLflow Tracking supports auto-logging for many classic libraries such as
TensorFlow, Scikit-Learn, Spark, or PyTorch, but manual logging is
available in other cases.

**MLflow Projects:** The MLflow projects component provides a standard
format for packaging and distributing machine learning code, including
dependencies, in a reproducible way. Projects can be run locally or in a
cluster, and MLflow can manage the environment and dependencies for each
run. In addition, the Projects component includes an API and
command-line tools for running projects, making it possible to chain
together projects into workflows. In the MLproject file, it is possible
to define the software environment and entry points with parameters to
define workflow.

**MLflow Models:** The models component allows users to easily package
models in a standard format for deployment. Models can be exported in
multiple formats, including TensorFlow, PyTorch, and ONNX, and can be
deployed using a variety of tools, including Docker, Kubernetes, and
Amazon SageMaker. It is also possible to access models in standard ways
such as REST API. The Model API allows saving, loading, and logging of
the model as well as adding different flavours.

**MLflow Model Registry:** The MLflow Model Registry component allows
users to store, manage, and deploy models in a central repository.
Models can be versioned, and access can be controlled using role-based
access control. The Model Registry works both in UI and API versions.

![](media/image21.png){width="5.1625in" height="3.484027777777778in"}

[]{#_Toc183680933 .anchor}Figure 7: MLflow - Experiments tracking
interface

## TensorBoard

To support model evaluation during training, the FAIRiCUBE Hub
processing environment is also extended by a **TensorBoard** to support
the tracking of individual experiments and training runs. This tool can
be used with PyTorch and TensorFlow, and it provides a state-of-the-art
toolset for data scientists to inspect the tuning and training process
and compare metrics. In machine learning, to improve something you often
need to be able to measure it. TensorBoard is a tool for providing the
measurements and visualizations needed during the machine learning
workflow. It enables tracking experiment metrics like loss and accuracy,
visualizing the model graph, projecting embeddings to a lower
dimensional space, and much more. TensorBoard provides the visualization
and tooling needed for machine learning experimentation:

-   Tracking and visualizing metrics such as loss and accuracy

-   Visualizing the model graph (ops and layers)

-   Viewing histograms of weights, biases, or other tensors as they
    change over time

-   Projecting embeddings to a lower dimensional space

-   Displaying images, text, and audio data

-   Profiling TensorFlow programs

![](media/image22.png){width="5.429166666666666in"
height="3.6534722222222222in"}

[]{#_Toc170725604 .anchor}Figure 8: TensorBoard -- Time series
evaluation

## DVC

DVC[^2] is a Data Version Control system for collaborative data
management like ML artefacts. It is a free and open-source,
platform-agnostic version system for data, machine learning models, and
experiments. It is designed to make ML models shareable, experiments
reproducible, and to track versions of models, data, and pipelines. DVC
works on top of Git repositories and cloud storage.

DVC\'s features can be divided into three categories: data management,
pipelines, and experiment tracking.

**Data management:** Data and model versioning is the base layer of DVC
for large files, datasets, and machine learning models. It allows the
use of a standard Git workflow, but without the need to store those
files in the repository. Large files, directories and ML models are
replaced with small meta-files, which in turn point to the original
data. Data is stored separately, allowing data scientists to transfer
large datasets or share a model with others.

**Pipelines:** DVC provides a mechanism to define and execute pipelines.
Pipelines represent the process of building ML datasets and models, from
how data is pre-processed to how models are trained and evaluated.
Pipelines can also be used to deploy models into production
environments. DVC pipeline is focused on the experimentation phase of
the ML process. Users can run multiple copies of a DVC pipeline by
cloning a Git repository with the pipeline or running ML experiments.
They can also record the workflow as a pipeline and reproduce it in the
future.

**Experiment tracking:** tracking allows developers to explore, iterate
and compare different machine learning experiments. Each experiment
represents a variation of a data science project defined by changes in
the workspace. Experiments maintain a link to the commit in the current
branch (Git HEAD) as their parent or baseline. However, they do not form
part of the regular Git tree (unless they are made persistent). This
stops temporary commits and branches from overflowing a user\'s
repository.

## rasdaman ML tools

A specific subset of pre-trained machine learning models created by the
Use Cases can be run directly inside the rasdaman server. The PyTorch
framework has been integrated into rasdaman so that now ML models build
with PyTorch can be activated from a query, together with the input data
for the inference.

Implementation was done using the rasdaman extensibility mechanism of
User Defined Functions (UDFs). This feature allows dynamic loading of
external code at query time, where this functionality can be invoked
seamlessly integrated as if it were a function of the query language. To
this end, some adapter code has to be written, originally in the only
supported language, C++. For PyTorch, the initial idea was to use torch
directly which is implemented in C++ and, therefore, allows for a direct
coupling. It turned out, however, that PyTorch is not just a python
wrapper but performs own data preparation, and so the torch coupling
delivered wrong results. Consequently, it was necessary to add Python as
an additional language for UDFs. This was accomplished in the project,
leading to a dual result:

-   Via a UDF function nn.predict(), models that have been registered
    with rasdaman can be passed to PyTorch as part of the query, and the
    result can be processed further in the query or delivered directly.

-   In general, any Python code can act as a UDF in rasdaman. As Python
    is so common among data scientists such a Python coupling provides
    an additional advantage for them.

Figure 9 shows a sample model application to a region in the Netherlands
using a model provided by WER. This close integration allows a very
simple, interactive application of models to any data cube, any region,
and any time -- if desired, combined with the full set of WCPS
operators. Current status is that models, in order to be available in
queries, have to be provided on the server in a designated directory by
someone authorized (such as WER). In future, it is planned to generalize
this to also allow passing of models on the fly, as part of a query.
Further, models should migrate into the database and get attributes
which allow users to meaningfully select their model of choice. One such
criterion is the region (in space and time) of applicability of a
particular model (minimizing the risk of applying a machine learning
model on out-of-distribution data).

  ------------------------------------------------------------------------- -----------------------------------------------------
  ![fairicube_demo_2.png](media/image23.png){width="1.1659722222222222in"   ![](media/image24.png){width="3.6805555555555554in"
  height="1.0458333333333334in"}                                            height="0.7763888888888889in"}

  ------------------------------------------------------------------------- -----------------------------------------------------

[]{#Ref_Figure32_label_and_number .anchor}Figure 9: Sample model
application as a query result (left) and schematic WCPS query generating
it.

# Summary and Outlook

Providing the FAIRiCUBE community with the basic functionality of the
FAIRiCUBE Hub within a very short time after the starting of the project
allowed the users to get acquainted with its underlying logic as well as
with the with the overall technology and functionality of the FAIRiCUBE
Hub. The aim was to get the users up to working speed as fast as
possible in order to explore its possibilities. In parallel users get an
insight about what parts and tools are missing to achieve their work.
Distinct user consultations to collect requirements have been organised
online and offline. I addition, needs for advanced, supplemental tools
required by users can always be presented to the FAIRiCUBE Hub
operations team either via GitHub issues or directly via email. This
option has been used multiple times, and the respective requirements
have been fulfilled wherever possible on a best effort basis.

It should also be noted that during the projects evolution new
requirements have been discovered which were not originally part of the
proposal. These requirements were processed during the course of the
project on a best effort basis. The Catalog Editor represents one
prominent example since the initial foreseen metadata handling process
had to be dismissed due to unforeseen limitations of GitHub.
Furthermore, this is especially true for tools which target the
operators of the FAIRiCUBE system rather than FAIRiCUBE users. One
example is an administrator interface to manage various aspects of user
management, kernel provisioning, resource control and monitoring (of
used online resources, e.g. in the context of NoR funding or usage of
cloud resources and cost control) and similar tasks. Such an interface
is currently undergoing the planning and design phase on a best effort
basis.

Overall, it can be summarised that the FAIRiCUBE Hub provides an
efficient baseline, with highly expandable possibilities, to easily
analyse large datasets, even combine them to data cubes, and present the
results with modern methods to customers. The comprehensive
documentation provided in the Knowledge Base and as Read-the-Docs,
together with the set of operator and user provided usage examples, made
available as Jupyter notebooks, form together a \"Digital Library\"
which should help users to get started and achieve first results easily
as well as to dive deeper into the possibilities offered by the
FAIRiCUBE Hub.

[^1]: https://race.esa.int/

[^2]: [https://dvc.org](https://dvc.org/)
