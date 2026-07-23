---
title: "INF-projects in CRCs Meet-Up 2026 (Online)"
layout: post
author: "Hamza Oukili, Florian Goth, Neele Drobnitzky, Ron Dockhorn"
menulang: en
---

Following the initial on-site workshop held during the deRSE26 conference in Stuttgart (March 3–5, 2026), the inf-in-CRCs Network organized its first virtual meet-up on Wednesday, June 10, 2026 https://inf-in-crcs-26.sciencesconf.org/.
The Meet-up served as an information-exchange platform for scientists, Research Software Engineers (RSEs), and Research Data Managers (RDMs) working within Collaborative Research Centers 
(SFBs/CRCs) across Germany. The event recorded 87 registered participants, with 75 actively attending the initial plenary session. The main objectives were to coordinate activities across 
different consortia, discuss common technical frameworks, address shared challenges in academic software development and data management, and create opportunities for networking and future 
collaboration between INF projects.

1. Plenary Sessions: National Frameworks and Poster Presentations

The introductory plenary was divided into general infrastructure reports and a series of rapid-fire technical pitches.

The INF-in-CRCs Network brings together members from several national communities, including de-RSE, Data Stewardship goes Germany (DSgG), and the NFDI. The plenary therefore began with short 
updates from these initiatives to give participants an overview of current developments, available services, and opportunities for collaboration.

National Infrastructure Reports
de-RSE e.V. Status: Frank Löffler presented the ongoing activities of de-RSE (see Slides https://zenodo.org/records/17047067).
Data Stewardship Development: Jens Dierkes outlined the current state of Data Stewardship goes Germany (DSgG) and the broader data stewardship community in Germany (see Slides https://cryptpad.fr/file/#/2/file/dcJSUP3aNHUvLiPSMG2arAbK/).
Base4NFDI Services: Bernd Flemisch discussed the integration of Base4NFDI basic services within individual CRC projects, highlighting the upcoming Base4NFDI User Conference scheduled for 
November 24–25, 2026 (see Slides https://pad.gwdg.de/p/NvXOkX2VpW#/).

Poster Blitz

The poster blitz featured 15 short presentations, each introducing an INF project, research infrastructure, or technical solution from different CRCs, TRRs, and NFDI initiatives. 
The presentations covered a broad range of topics, including research data management, metadata infrastructures, provenance tracking, AI-assisted RDM, legal compliance, multimodal data 
integration, scientific visualization, and domain-specific software platforms. Several speakers presented practical tools and services, such as the PUNCH4NFDI platform, 
the MaRDI Packaging System (MAPS), provenance workflows based on DataLad, and guides for organizing research data. Other presentations highlighted the activities of individual INF projects, 
including SFB 1313, CRC 1625, CRC 1629, TRR 172, and TRR 408, illustrating the diversity of research domains represented in the network. Together, the poster blitz provided a concise overview 
of the technical expertise, ongoing developments, and common challenges across INF projects in Germany.

2. Parallel Session 1: Tooling Clusters

The first parallel session brought participants together around common technical topics. Each breakout room focused on a specific aspect of research software engineering and research data management, allowing participants to exchange experiences, present tools, and discuss practical challenges across different CRCs and research domains.

 AI Tools for INF Projects

Moderated by Hamza Oukili (University of Stuttgart), this session explored the use of AI technologies within INF projects. Jan Frenzel (TU Dresden) presented the AI Services@TUD infrastructure, demonstrating automated knowledge-base ingestion using GitLab CI/CD pipelines and discussing the transition from small local language models to GPU-based deployments using Apptainer, vLLM, and SLURM. The discussion also covered challenges in adapting AI models to domain-specific applications, where limited training data often requires advanced prompting techniques instead of fine-tuning.

 Electronic Lab Notebooks (ELNs)

Moderated by Neele Drobnitzky (University of Heidelberg), this session focused on the adoption of Electronic Lab Notebooks, particularly eLabFTW and OpenBIS. 

 Container Technologies

Moderated by Aaruni Kaushik (RPTU Kaiserslautern), this breakout session was planned to discuss reproducible software environments, package management, and container technologies, including the MaRDI Packaging System.

 Git, Version Control, and Remote Repositories

Moderated by Florian Goth (University of Würzburg) and Harald von Waldow. We discussed the benefits of [federated gitlab](https://gitlab.com/groups/gitlab-org/-/work_items/16514) for the german research landscape. As a  competitor we discussed [forgejo](https://forgejo.org/) that is also supposed to offer federation mechanisms in the future.
As an infrastructure building on git-annex we discussed [datalad](https://www.datalad.org/)
 
 Cloud Services and Data Sharing

Moderated by Alvaro Aguilera, this session included presentations on scientific workflows in VIVO and the federated infrastructure developed within PUNCH4NFDI. Discussions emphasized the importance of provenance tracking for reproducible research and addressed the technical challenges associated with transferring and processing very large collections of small metadata files. Participants agreed that moving computation closer to the data can significantly improve performance.

 REDCap

Moderated by Lincoln Sherpa, this session focused on practical experiences with REDCap for research data collection. Participants discussed performance challenges in large longitudinal studies and shared optimization strategies, including more efficient API usage, query filtering, and customized database interfaces.

 Jupyter

This session featured presentations on Jupyter4NFDI Services by Vasundhara Shaw and Jupyter Notebooks: From Lectures to Research by Daniel Appel. Discussions covered resource management within Jupyter4NFDI, integration with external storage systems such as WebDAV and S3, and remaining challenges related to reproducibility, including persistent software environments and secure management of authentication credentials.

 DMPs & SMPs

Moderated by Ron Dockhorn, 

3. Parallel Session 2: Domain Clusters

The second parallel session grouped participants by research domain to discuss domain-specific workflows, metadata standards, repositories, and collaboration with the corresponding NFDI consortia. Although many challenges were shared across disciplines, each community highlighted its own 
requirements and priorities.

The Physics group, moderated by Florian Goth, discussed custom simulation software, engineering models, and the integration of Electronic Lab Notebooks, while also reviewing previous NFDI Physical Sciences workshops. In Medicine and Psychology, moderated by Alvaro Aguilera, the discussion 
focused on handling sensitive patient data under GDPR, knowledge graphs, and commonly used platforms such as REDCap, Neurocloud, Dataverse, OMERO, SODAR, and GraphDB. The Materials Science, Geosciences, and Engineering group, moderated by Hamza Oukili, exchanged experiences with scientific 
software such as DuMux, MuMax, and MATSim, emphasizing that domain-specific repositories such as NOMAD and Kadi4Mat provide richer metadata and search capabilities than general-purpose repositories for many research applications. The Humanities and Linguistics group, moderated by Mercedes 
Martinez-Bruera, discussed semantic metadata extraction, automation of legal consent forms, and the need for shared repositories of scripts and workflows. Finally, the Biology group explored imaging data management with OMERO and automated metadata extraction from Electronic Lab Notebooks.

4. Parallel Session 3: Regional Clusters
Eventually we split the participants into the different regions where we determined clusters from the registration data.
The following Clusters emerged:

Main-Donau area

Baden-Württemberg

Mitteldeutschland

Northern Germany

NRW

5. Fireplace chat
Finally, we concluded the meet-up with a fireplace chat that we kicked off with an plenary talk by Jeremy Cohen on "Providing effective support for digital research through RDM and RSE: A UK perspective".

