# Introduction to GIN at the University of Bristol

[GIN (G-Node Infrastructure)](https://gin.g-node.org/G-Node/Info/wiki) is a free and open neuroscientific data management system developed by the [German Neuroinformatics Node (G-Node)](https://www.g-node.org/). It offers a public service in the form of [research data repository](https://gin.g-node.org/) that can be used to share your own research data with collaborators and/or share it with the scientific community during research output publication. GIN can also be installed locally ([in-house-GIN](https://gin.g-node.org/G-Node/Info/wiki/In+House)) on a personal computer or on a local university server accessible via your institution's intranet or even made accessible publicly via an internet domain name.

The latter set up is appealing to us because it gives us:
- an extra layer of data security which is important when dealing with sensitive data
- a potential to develop our GIN-based data sharing platform in a way that is uniquely suited to our own needs
- a drive for increasing data sharing and collaboration within neuroscience research groups at the University of Bristol (UoB)
- a nudge for data standardisation.

## Benefits
There is a number of **benefits of using GIN** in addition to a traditional way of managing your research data using a file manager software:
- a more organised and disciplined way of working with the research data (relevant for PhDs and postdocs)
- a data versioning system (think of Github)
- a more secure data repository as access rights can be controlled by repository owners
- a research collaboration platform
- a project management system (relevant for PIs)
- a publication repository supporting DOIs for data (when our local GIN goes online)
- a data standardisation tool offering standard research data folder templates with automated repository sync'ing
- a resource on good data management practices (when we create documentation).

## Future directions
Currently we have GIN set up locally on one of our Linux machines (front-end) and hooked up to the university's Research Data Storage Facility (RDSF) to store the bulk data (back-end). This set up is a temporary solution useful for development and testing purposes while we are waiting for the university to allocate us a virtual machine running on a server (3-8 months queue). This is how we see our UoB Team Neuroscience Data Sharing Platform developing in the mean time and further:
- Designing UoB GIN front page
  - Front page
  - Header, footer, and navbar
  - Help, News, About, Imprint, Contact, Terms of Use, Privacy
- Creating documentation
    - [Jupyter Book](https://jupyterbook.org) documentation for the GIN web interface
    - Documentation for GIN client (command line interface)
- Creating tutorials
    - Tutorials for using UoB GIN: specific lab-tailored examples
    - Tutorials for recording metadata
    - Tutorials for converting electrophysiology data into the [Neurodata Without Borders (NWB) format](https://www.nwb.org/)
    - Tutorials on adopting standard research data folder templates (e.g., [BIDS](https://bids.neuroimaging.io/))
- Creating GIN services to automate repository creation and management (requires programming in GO; we are undecided on this)
- Launching our GIN-based data sharing platform on a local server
- Creating a Slack channel for early career researchers and PI using UoB GIN
- Pitching the platform to other labs
- Going online
- Using UoB GIN as a stepping stone towards building neuroscience research database accessible via a programming interface (Python/Matlab) and supporting fast queries.

## Practice
Now try out a few tutorials made to give you a basic introduction into using the [GIN web interface](GIN-web-interface-tutorial.md) and [GIN command line tools](GIN-client-tutorial.md).

Enjoy!
