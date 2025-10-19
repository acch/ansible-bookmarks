# Ansible Bookmarks [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![CI](https://github.com/acch/ansible-bookmarks/actions/workflows/awesome-lint.yml/badge.svg)](https://github.com/acch/ansible-bookmarks/actions/workflows/awesome-lint.yml)

This repository collects resources for learning how to write good [Ansible](https://www.ansible.com/) playbooks. [Please bring yours!](CONTRIBUTING.md) :blush:

<div align="center">
  <br>
  <img width="203" height="250" src="ansible.png" alt="Ansible logo">
  <br>
  <br>
</div>

## Contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Getting Started](#getting-started)
  - [YAML Syntax](#yaml-syntax)
- [Articles and Books](#articles-and-books)
  - [Event-Driven](#event-driven)
- [Talks](#talks)
  - [2022](#2022)
  - [2018](#2018)
  - [2017](#2017)
  - [2016](#2016)
- [Selected Roles](#selected-roles)
- [Cheatsheets](#cheatsheets)
- [Reference Documentation](#reference-documentation)
  - [Automation Platform](#automation-platform)
  - [Jinja2](#jinja2)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Getting Started

- [User Guide » Getting Started](https://docs.ansible.com/ansible/latest/user_guide/intro_getting_started.html) - Documentation section about how to initially get Ansible running.

- [Ansible-Boilerplate](https://github.com/acch/ansible-boilerplate) - Basic template for new Ansible projects.

- [How Ansible Works](https://www.ansible.com/overview/how-ansible-works)

- [How to automate your system administration tasks with Ansible](https://opensource.com/article/17/7/automate-sysadmin-ansible)

- [Getting Started: Writing Your First Playbook](https://www.ansible.com/blog/getting-started-writing-your-first-playbook)

- [Install Ansible on Windows Using Cygwin](http://www.dcaulfield.com/install-ansible-on-windows-using-cygwin)

- [Quick start guide to Ansible for Linux sysadmins](https://www.redhat.com/sysadmin/ansible-quick-start)

- [Ansible Resources » Videos](https://www.ansible.com/resources/videos)

### YAML Syntax

- [User Guide » YAML Syntax](https://docs.ansible.com/ansible/latest/reference_appendices/YAMLSyntax.html) - Basic overview of correct YAML syntax.

- [YAML](https://en.wikipedia.org/wiki/YAML) - Wikipedia, the free encyclopedia.

- [YAML for beginners](https://www.redhat.com/sysadmin/yaml-beginners)

- [Understanding YAML for Ansible](https://www.redhat.com/sysadmin/understanding-yaml-ansible)

- [In YAML, how do I break a string over multiple lines?](https://stackoverflow.com/questions/3790454/in-yaml-how-do-i-break-a-string-over-multiple-lines/21699210#21699210)

- [YAML Specification](https://yaml.org/spec/1.2/spec.html)

## Articles and Books

- [Ansible Best Practices: The Essentials](https://www.ansible.com/blog/ansible-best-practices-essentials)

- [User Guide » Tips and tricks](https://docs.ansible.com/ansible/latest/user_guide/playbooks_best_practices.html)

- [Use Ansible's YAML callback plugin for a better CLI experience](https://www.jeffgeerling.com/blog/2018/use-ansibles-yaml-callback-plugin-better-cli-experience)

- [Reboot Plugin for Linux in Ansible 2.7](https://www.ansible.com/blog/reboot-plugin-for-linux-in-ansible-2-7)

- [Dealing with Unreliable Connections and Services](https://www.ansible.com/blog/ansible-tips-and-tricks-dealing-with-unreliable-connections-and-services)

- [Ansible Configuration Management Database](https://github.com/fboender/ansible-cmdb) - Generate host overview from ansible fact gathering output.

- [Ansible recipes and gotchas](https://github.com/andiveloper/ansible-recipes-and-gotchas)

- [Hands on with Ansible collections](https://www.ansible.com/blog/hands-on-with-ansible-collections)

- [Ansible Linting with GitHub Actions](https://www.ansible.com/blog/ansible-linting-with-github-actions)

- [Tolerable Ansible](https://www.ansible.com/blog/tolerable-ansible)

- [Deploying a static website with Ansible](https://www.redhat.com/sysadmin/deploying-static-website-ansible)

- [How to encrypt a single Linux filesystem](https://www.redhat.com/sysadmin/encrypt-single-filesystem)

- [Handling secrets in your Ansible playbooks](https://www.redhat.com/sysadmin/ansible-playbooks-secrets)

- [8 steps to developing an Ansible role in Linux](https://www.redhat.com/sysadmin/developing-ansible-role)

- [6 troubleshooting skills for Ansible playbooks](https://www.redhat.com/sysadmin/troubleshoot-ansible-playbooks)

- [Writing Ansible Modules in Bash](https://github.com/pmarkham/writing-ansible-modules-in-bash/blob/master/ansible_bash_modules.md)

- [Tuning Ansible For Maximum Performance](https://gryzli.info/2019/02/21/tuning-ansible-for-maximum-performance/)

- [How to customize your Ansible logs](https://www.redhat.com/sysadmin/ansible-logs-customize)

- [Automate container management on Fedora Linux with the Podman Linux System Role](https://fedoramagazine.org/automate-container-management-on-fedora-linux-with-the-podman-linux-system-role/)

- [How to cache Ansible facts with Redis](https://www.redhat.com/sysadmin/ansible-fact-cache-redis)

- [Good Practices for Ansible - GPA](https://redhat-cop.github.io/automation-good-practices/)

- [How to work with a list of dictionaries in Ansible](https://www.redhat.com/sysadmin/ansible-jinja-lists-dictionaries)

- [Ansible for DevOps - by Jeff Geerling](https://www.ansiblefordevops.com/)

- [Ansible for Kubernetes - by Jeff Geerling](https://www.ansibleforkubernetes.com/)

- [Ansible data manipulation with a Filter](https://www.ansible.com/blog/ansible-data-manipulation-with-a-filter)

- [Using Ansible for Automation in IBM Power Environments](https://www.redbooks.ibm.com/abstracts/sg248551.html)

- [Peeling back the layers and understanding automation mesh](https://www.ansible.com/blog/peeling-back-the-layers-and-understanding-automation-mesh)

- [Pushing Kickstarts with Ansible](https://medium.com/@jackprice/pushing-kickstarts-with-ansible-122b2cd9c1e)

- [Create an efficient Ansible development environment in VS Code IDE](https://developers.redhat.com/articles/2024/03/05/create-efficient-ansible-development-environment-vs-code-ide)

- [ansible-content-actions](https://github.com/ansible/ansible-content-actions) - Combine GitHub Actions to create a streamlined workflow for testing Ansible collection repositories on GitHub.

- [Making the double hop on Windows with Red Hat Ansible Automation Platform](https://www.redhat.com/en/blog/making-double-hop-windows-ansible)

- [Azure Automation with Ansible](https://mycloudrevolution.com/2023/12/19/azure-automation-with-ansible/)

- [Ansible Forms](https://ansibleforms.com/) - Lightweight Node.js webapplication to generate userfriendly and pretty forms to kickoff Ansible playbooks or AWX/Tower templates.

- [Ansible Best Practices](https://timgrt.github.io/Ansible-Best-Practices/) - Good and best practices from Ansible practitioners and experience from multiple Ansible projects.

- [Strategies for eliminating Ansible hardcoded credentials](https://developers.redhat.com/articles/2025/01/23/strategies-eliminating-ansible-hardcoded-credentials)

- [How to manage Python dependencies in Ansible execution environments](https://developers.redhat.com/articles/2025/01/27/how-manage-python-dependencies-ansible-execution-environments)

- [How to Troubleshoot and Debug Ansible Playbooks](https://spacelift.io/blog/ansible-debug)

- [The Tao of Ansible](https://github.com/stiliajohny/Book-The-Tao-of-Ansible) - Mastering Automation with Simplicity and Grace by John Stilia (Ioannis Stylianakos).

- [Automate Your Network](https://github.com/automateyournetwork/automate_your_network) - Introducing the Modern Approach to Enterprise Network management (John Capobianco).

- [How to start configuration as code for an Ansible instance](https://developers.redhat.com/articles/2025/05/27/how-start-configuration-code-ansible-instance)

- [New Red Hat Ansible Certified Content Collections for HashiCorp Terraform and HashiCorp Vault](https://www.redhat.com/en/blog/new-ansible-certified-content-hashicorp-terraformvault)

- [Ansible: pure (only in its) pragmatism](https://andrejradovic.com/blog/ansible/)

### Event-Driven

- [Introducing the Event-Driven Ansible developer preview](https://www.ansible.com/blog/introducing-event-driven-ansible)

- [Ansible Rulebook documentation](https://ansible.readthedocs.io/projects/rulebook/)

- [Event-driven remediation with systemd and Red Hat Ansible Automation Platform](https://www.ansible.com/blog/event-driven-remediation-with-systemd-and-red-hat-ansible-automation-platform)

- [OpenShift application monitoring with Event-Driven Ansible & Alertmanager](https://developers.redhat.com/articles/2024/01/08/openshift-application-monitoring-event-driven-ansible-alertmanager)

## Talks

- [Red Hat Ansible Automation Platform Workshops](https://ansible.github.io/workshops/)

- [1. Ansible Anwendertreffen](https://www.ansible-anwender.de/post/2020/11/rueckblick/)

- [2. Ansible Anwendertreffen](https://www.ansible-anwender.de/post/2021/05/rueckblick/)

- [3. Ansible Anwendertreffen](https://www.ansible-anwender.de/post/2022/02/rueckblick/)

- [4. Ansible Anwendertreffen](https://www.ansible-anwender.de/post/2023/05/rueckblick/)

- [5. Ansible Anwendertreffen](https://www.ansible-anwender.de/post/2024/03/rueckblick/)

- [6. Ansible Anwendertreffen](https://www.ansible-anwender.de/post/2024/11/rueckblick/)

- [7. Ansible Anwendertreffen](https://www.ansible-anwender.de/post/2025/03/rueckblick/)

### 2022

- [Validierung und Integration Testing für Ansible Roles und Playbooks](https://www.youtube.com/watch?v=Cj_d1N8MIEM) - by [Daniel Schier](https://github.com/dschier-wtd)

### 2018

- [Ansible 202: Best Practices from the field](https://www.youtube.com/watch?v=xGkrSaoSo6M) - by [Juan Manuel Parrilla](https://github.com/jparrill) - DevConf Brno.

- [Ansible best current practices](https://www.youtube.com/watch?v=4RpqD9GhSOs) - by [Lee Garrett](https://github.com/leegarrett) - MiniDebConf Hamburg.

### 2017

- [Best Practices for Ansible Roles Development](https://www.youtube.com/watch?v=sFuKuHmRuzQ) - by [Jiri Tyr](https://github.com/jtyr) - Ansible London.

### 2016

- [Ansible From Zero to Best Practices](https://willthames.github.io/devops-singapore-2016/01-intro.html) - by [Will Thames](https://github.com/willthames) - DevOpsDays Singapore.

## Selected Roles

- [IBM Spectrum Scale](https://galaxy.ansible.com/acch/spectrum_scale) - Highly-customizable role for installing and configuring IBM Spectrum Scale (GPFS).

- [Ansible Role: mmmodules](https://github.com/idiv-biodiversity/ansible-role-mmmodules) - Ansible modules for IBM Spectrum Scale (formerly GPFS) file systems.

- [NetApp ONTAP volume-nfs-share](https://galaxy.ansible.com/chrifey/ontap_volume_nfs_share) - Role to configure NFS exports (volume, qtree, policy).

- [IBM Spectrum Virtualize IP-Quorum](https://galaxy.ansible.com/olemyk/ansible_ipquorum) - Role that installs and configures IP-Quorum service for IBM Spectrum Virtualize.

- [IBM Power Systems AIX Collection](https://galaxy.ansible.com/ibm/power_aix) - Ansible Content for IBM Power Systems - AIX provides a collection of modules used to manage and deploy Power Systems AIX.

- [IBM Cloud Ansible Collections](https://github.com/IBM-Cloud/ansible-collection-ibm) - Ansible modules collection for IBM cloud.

- [Linux System Roles](https://linux-system-roles.github.io/)

- [Red Hat Enterprise Linux (RHEL) System Roles](https://access.redhat.com/articles/3050101)

- [Regex Test](https://galaxy.ansible.com/acch/regex_test) - Role for comparing command output with reference file.

- [IBM Storage Scale](https://github.com/IBM/ibm-spectrum-scale-install-infra) - Spectrum Scale Installation and Configuration.

- [IBM Storage Protect](https://github.com/IBM/ansible-storage-protect) - Ansible collection for IBM Storage Protect.

## Cheatsheets

- [Awesome Ansible](https://github.com/jdauphant/awesome-ansible) (archived!)

- [Awesome Ansible](https://github.com/KeyboardInterrupt/awesome-ansible)

- [Ansible Cheat Sheet from Jon Warbrick](https://gist.github.com/andreicristianpetcu/b892338de279af9dac067891579cad7d)

- [Devhints.io cheatcheets](https://devhints.io/ansible)

## Reference Documentation

- [User Guide](https://docs.ansible.com/ansible/latest/user_guide/index.html)

- [Index of all Modules](https://docs.ansible.com/ansible/latest/collections/index_module.html)

  - [Ansible.Builtin](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/index.html)
  - [Community.General](https://docs.ansible.com/ansible/latest/collections/community/general/index.html)

- [Developer Guide](https://docs.ansible.com/ansible/latest/dev_guide/index.html)

- [Ansible Roadmap](https://docs.ansible.com/ansible/devel/roadmap/ansible_roadmap_index.html)

- [Porting Guides](https://docs.ansible.com/ansible/devel/porting_guides/porting_guides.html)

- [Community Guide](https://docs.ansible.com/ansible/latest/community/index.html)

- [The Ansible Community forum](https://forum.ansible.com/)

- [Ansible Collections Checklist](https://github.com/ansible-collections/overview/blob/main/collection_requirements.rst)

- [Ansible Automation Platform Certified Content](https://access.redhat.com/articles/3642632)

- [`ansible-core` support matrix](https://docs.ansible.com/ansible/latest/reference_appendices/release_and_maintenance.html#ansible-core-support-matrix)

### Automation Platform

- [Automation with Ansible AWX](https://spacelift.io/blog/ansible-awx)

- [Introducing Red Hat Ansible Automation Platform](https://www.ansible.com/blog/introducing-red-hat-ansible-automation-platform)

- [Ansible Automation Platform - A video tour](https://www.ansible.com/blog/ansible-automation-platform-a-video-tour)

- [Introducing Ansible Automation Platform 2](https://www.ansible.com/blog/introducing-ansible-automation-platform-2)

- [Ansible Automation Platform 2.0](https://red.ht/AAP-20)

- [Introducing Red Hat Ansible Automation Platform 2.1](https://www.ansible.com/blog/introducing-red-hat-ansible-automation-platform-2.1)

- [What's new in Ansible Automation Platform 2.2](https://www.ansible.com/blog/whats-new-in-ansible-automation-platform-2.2)

- [What's new in Ansible Automation Platform 2.3](https://www.ansible.com/blog/whats-new-in-red-hat-ansible-automation-platform-2.3)

- [What's new in Ansible Automation Platform 2.4](https://www.ansible.com/blog/whats-new-in-ansible-automation-platform-2.4)

- [What's new in Red Hat Ansible Automation Platform 2.5](https://developers.redhat.com/blog/2024/10/01/whats-new-red-hat-ansible-automation-platform-25)

- [What’s new in Red Hat Ansible Automation Platform 2.6](https://www.redhat.com/en/blog/whats-new-in-ansible-automation-platform-2.6)

### Jinja2

- [Template Designer Documentation](http://jinja.pocoo.org/docs/2.10/templates/)

- [User Guide » Templating Jinja2](https://docs.ansible.com/ansible/latest/user_guide/playbooks_templating.html)
