---
isChild: true
anchor: vagrant
---

## Vagrant {#vagrant_title}

## 强烈推荐!!!

为了解决不同系统、不同开发环境带来的差异，Vagrant运势而生。

Vagrant配合虚拟机一起使用，使得Windows作为开发系统的用户，也可以获得与线上Linux机器一样的环境。[Vagrant][vagrant]可以通过简单命令来
手动创建和管理虚拟机，当然也允许一些自动管理工具的使用，如：[Puppet][puppet] 或 [Chef][chef]。

Vagrant 负责同步本地代码到虚拟机，这样你可以本地编写代码，通过虚拟机来执行。

### 一些指南

Vagrant的使用帮助:

- [Rove][rove]: service that allows you to pre-generate typical Vagrant builds, PHP among the options. The
  provisioning is made with Chef.
- [Puphpet][puphpet]: simple GUI to set up virtual machines for PHP development. **Heavily focused in PHP**. Besides
  local VMs, can be used to deploy to cloud services as well. The provisioning is made with Puppet.
- [Protobox][protobox]: is a layer on top of vagrant and a web GUI to setup virtual machines for web development. A single YAML document controls everything that is installed on the virtual machine.
- [Phansible][phansible]: provides an easy to use interface that helps you generate Ansible Playbooks for PHP based projects.

[vagrant]: http://vagrantup.com/
[puppet]: http://www.puppetlabs.com/
[chef]: http://www.opscode.com/
[rove]: http://rove.io/
[puphpet]: https://puphpet.com/
[protobox]: http://getprotobox.com/
[phansible]: http://phansible.com/
