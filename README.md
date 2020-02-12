# Flexible playbooks for Fragalysis-Stack (Kubernetes)

[![Build Status](https://travis-ci.com/InformaticsMatters/dls-fragalysis-stack-kubernetes.svg?branch=master)](https://travis-ci.com/InformaticsMatters/dls-fragalysis-stack-kubernetes)
![GitHub tag (latest SemVer)](https://img.shields.io/github/v/tag/informaticsmatters/dls-fragalysis-stack-kubernetes)

Ansible Playbooks (and Roles) for the deployment of the XChem [Fragalysis Stack]
application to Kubernetes. This repository builds on the work accomplished
by our [OpenShift deployment] and yields plays that can be run from an [AWX]
server.

## Building the documentation
The documentation is written in [Sphinx] and is the source of this project's
GitHub **PAGES**. For details of how this is done refer to the documentation
[notes]  in our OKD Orchestrator project.

---

[awx]: https://github.com/ansible/awx
[fragalysis stack]: https://github.com/xchem/fragalysis-stack.git
[openshift deployment]: https://github.com/InformaticsMatters/dls-fragalysis-stack-openshift.git
[sphinx]: https://pypi.org/project/Sphinx/
[notes]: https://raw.githubusercontent.com/InformaticsMatters/okd-orchestrator/master/README-SPHINX.md
