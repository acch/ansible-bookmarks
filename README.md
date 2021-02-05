<div align="center">
  <br>
  <img width="203" height="250" src="ansible.png" alt="Ansible logo">
  <br>
  <br>
</div>

This repository collects resources for learning how to write good [Ansible](https://www.ansible.com/) playbooks. [Please bring yours!](CONTRIBUTING.md) :blush:

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Getting Started](#getting-started)
  - [YAML Syntax](#yaml-syntax)
- [Articles and Books](#articles-and-books)
- [Talks](#talks)
  - [2017](#2017)
  - [2016](#2016)
- [Selected Roles](#selected-roles)
- [Cheatsheets](#cheatsheets)
- [Reference Documentation](#reference-documentation)
  - [Jinja2](#jinja2)
- [License](#license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->


## Getting Started

- [User Guide &raquo; Getting Started](https://docs.ansible.com/ansible/latest/user_guide/intro_getting_started.html) &mdash; Documentation section about how to initially get Ansible running

- [Ansible-Boilerplate](https://github.com/acch/ansible-boilerplate) &mdash; Basic template for new Ansible projects

- [How Ansible Works](https://www.ansible.com/overview/how-ansible-works)

- [How to automate your system administration tasks with Ansible](https://opensource.com/article/17/7/automate-sysadmin-ansible)

- [Getting Started: Writing Your First Playbook](https://www.ansible.com/blog/getting-started-writing-your-first-playbook)

- [Install Ansible on Windows Using Cygwin](http://www.dcaulfield.com/install-ansible-on-windows-using-cygwin)

- [Ansible Tutorial](https://www.javatpoint.com/ansible)

- [Quick start guide to Ansible for Linux sysadmins](https://www.redhat.com/sysadmin/ansible-quick-start)

### YAML Syntax

- [User Guide &raquo; YAML Syntax](https://docs.ansible.com/ansible/latest/reference_appendices/YAMLSyntax.html) &mdash; Basic overview of correct YAML syntax

- [YAML](https://en.wikipedia.org/wiki/YAML) &mdash; Wikipedia, the free encyclopedia

- [YAML for beginners](https://www.redhat.com/sysadmin/yaml-beginners)

- [Understanding YAML for Ansible](https://www.redhat.com/sysadmin/understanding-yaml-ansible)

- [In YAML, how do I break a string over multiple lines?](https://stackoverflow.com/questions/3790454/in-yaml-how-do-i-break-a-string-over-multiple-lines/21699210#21699210)

- [YAML Specification](https://yaml.org/spec/1.2/spec.html)


## Articles and Books

- [Ansible Best Practices: The Essentials](https://www.ansible.com/blog/ansible-best-practices-essentials)

- [Use Ansible's YAML callback plugin for a better CLI experience](https://www.jeffgeerling.com/blog/2018/use-ansibles-yaml-callback-plugin-better-cli-experience)

- [Reboot Plugin for Linux in Ansible 2.7](https://www.ansible.com/blog/reboot-plugin-for-linux-in-ansible-2-7)

- [Dealing with Unreliable Connections and Services](https://www.ansible.com/blog/ansible-tips-and-tricks-dealing-with-unreliable-connections-and-services)

- [Ansible Configuration Management Database](https://github.com/fboender/ansible-cmdb) &mdash; Generate host overview from ansible fact gathering output

- [Ansible recipes and gotchas](https://github.com/andiveloper/ansible-recipes-and-gotchas)

- [Ansible Linting with GitHub Actions](https://www.ansible.com/blog/ansible-linting-with-github-actions)

- [Tolerable Ansible](https://www.ansible.com/blog/tolerable-ansible)

- [Deploying a static website with Ansible](https://www.redhat.com/sysadmin/deploying-static-website-ansible)

- [How to encrypt a single Linux filesystem](https://www.redhat.com/sysadmin/encrypt-single-filesystem)


## Talks

- [Training Course for Ansible Automation](https://github.com/ansible/workshops)

### 2017

- [Best Practices for Ansible Roles Development](https://www.youtube.com/watch?v=sFuKuHmRuzQ) by [Jiri Tyr](https://github.com/jtyr) &mdash; Ansible London

### 2016

- [Ansible From Zero to Best Practices](https://willthames.github.io/devops-singapore-2016/01-intro.html) by [Will Thames](https://github.com/willthames) &mdash; DevOpsDays Singapore


## Selected Roles

- [IBM Spectrum Scale](https://galaxy.ansible.com/acch/spectrum_scale) &mdash; Highly-customizable role for installing and configuring IBM Spectrum Scale (GPFS)

- [NetApp ONTAP volume-nfs-share](https://galaxy.ansible.com/chrifey/ontap_volume_nfs_share) &mdash; Role to configure NFS exports (volume, qtree, policy)

- [IBM Spectrum Virtualize IP-Quorum](https://galaxy.ansible.com/olemyk/ansible_ipquorum) &mdash; Role that installs and configures IP-Quorum service for IBM Spectrum Virtualize

- [IBM Power Systems AIX Collection](https://galaxy.ansible.com/ibm/power_aix) &mdash; Ansible Content for IBM Power Systems - AIX provides a collection of modules used to manage and deploy Power Systems AIX

- [Regex Test](https://galaxy.ansible.com/acch/regex_test) &mdash; Role for comparing command output with reference file


## Cheatsheets

- [Awesome Ansible](https://github.com/jdauphant/awesome-ansible) (archived!)

- [Ansible Cheat Sheet from Jon Warbrick](https://gist.github.com/andreicristianpetcu/b892338de279af9dac067891579cad7d)

- [Devhints.io cheatcheets](https://devhints.io/ansible)


## Reference Documentation

- [User Guide](https://docs.ansible.com/ansible/latest/user_guide/index.html)

- [Index of all Modules](https://docs.ansible.com/ansible/latest/collections/index_module.html)
  - [Ansible.Builtin](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/index.html)
  - [Community.General](https://docs.ansible.com/ansible/latest/collections/community/general/index.html)

- [Developer Guide](https://docs.ansible.com/ansible/latest/dev_guide/index.html)

- [Porting Guides](https://docs.ansible.com/ansible/devel/porting_guides/porting_guides.html)

- [Community Guide](https://docs.ansible.com/ansible/latest/community/index.html)

- [Linux System Roles](https://linux-system-roles.github.io/)

- [Ansible Automation Platform Certified Content](https://access.redhat.com/articles/3642632)

### Jinja2

- [Template Designer Documentation](http://jinja.pocoo.org/docs/2.10/templates/)

- [User Guide &raquo; Templating Jinja2](https://docs.ansible.com/ansible/latest/user_guide/playbooks_templating.html)


## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
