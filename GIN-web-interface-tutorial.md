# GIN Web Interface Tutorial

[GIN (G-Node Infrastructure)](https://gin.g-node.org/G-Node/Info/wiki) is a free and open neuroscientific data management system developed by the [German Neuroinformatics Node (G-Node)](https://www.g-node.org/). It offers a public service in the form of [research data repository](https://gin.g-node.org/) that can be used to share your own research data with collaborators and/or share it with the scientific community during research output publication. GIN can also be installed locally ([in-house-GIN](https://gin.g-node.org/G-Node/Info/wiki/In+House)) on a personal computer or on a local university server accessible via your institution's intranet or even made accessible publicly via an internet domain name.

The latter set up is appealing to us because it gives us:
- an extra layer of data security which is important when dealing with sensitive data;
- a potential to develop our GIN-based data sharing platform in a way that is uniquely suited to our own needs;
- a drive for increasing data sharing and collaboration within neuroscience research groups at the University of Bristol;
- a nudge for data standardisation.

## Benefits
There is a number of **benefits of using GIN** in addition to a traditional way of managing your research data using a file manager software:
- a more organised and disciplined way of working with the research data (relevant for PhDs and postdocs);
- a data versioning system (think of Github);
- a more secure data repository as access rights can be controlled by repository owners;
- a research collaboration platform;
- a project management system (relevant for PIs);
- a publication repository supporting DOIs for data (when our local GIN goes online);
- a data standardisation tool offering standard research data folder templates with automated repository sync'ing;
- a resource on good data management practices (when we create documentation).

## Future directions:
Currently we have GIN set up locally on one of our Linux machines (front-end) and hooked up to the university's Research Data Storage Facility (RDSF) to store the bulk data (back-end). This set up is a temporary solution useful for development and testing purposes while we are waiting for the university to allocate us a virtual machine running on a server (3-8 months queue). This is how we see our UoB Team Neuroscience Data Sharing Platform developing in the mean time and further:
- Designing GIN front page
  - Front page
  - Header, footer, and navbar
  - Help, News, About, Imprint, Contact, Terms of Use, Privacy
- Creating a [Jupyter Book](https://jupyterbook.org) documentation for the GIN web interface
5.	JB documentation for GIN client (CLI)
6.	JB tutorials for GIN: lab-tailored examples
7.	JB tutorials for metadata
8.	JB tutorials for NWB
9.	JB tutorials for BIDS
10.	Lab handbooks
11.	Creating GIN services to automate repository creation and management. Requires programming in GO.

