# Ansible

## Recommended resources

+ Ansible online reference guide : https://docs.ansible.com/
+ Source code of Packt ansible course : https://github.com/spurin/masteringansible

The Packt source code comes with a video course : https://subscription.packtpub.com/video/virtualization-and-cloud/9781788629515

## Course track

+ Introduction
+ Installation
+ Quick start
+ Configuration
+ Inventory
+ Modules
+ Playbook
+ Managing playbooks
+ Advanced topics

## Introduction

Watch the ansible introduction video : https://www.ansible.com/resources/videos/quick-start-video

## Prerequisites

VM images in a virtualization environment (virtual box, vmware) :

+ Ubuntu
+ Centos

## Installation

Many options :

+ Package included in distributions (centos, ubuntu) : apt, yum
+ Adding the official ansible repository to your apt source list
+ Installing from source (github)
+ Installing in a default python environment using pip
+ Installing in a python virtual environment (pyenv, miniconda, ...) using pip

### Procedure

1. Install Ubuntu (VM)
2. Stop Ubuntu instance
3. Take a snapshot
4. Install ansible using apt

We install following Ansible official installation guide for Ubuntu : https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#installing-the-control-node. The complete reference documentation is here : https://docs.ansible.com/ansible/latest/installation_guide/index.html

### Authentification par clé dans SSH

Voir le doc suivant : https://www.digitalocean.com/community/tutorials/how-to-configure-ssh-key-based-authentication-on-a-linux-server


## Getting started

Tutorial : https://docs.ansible.com/ansible/latest/user_guide/intro_getting_started.html

## Inventories

+ Tutorial : https://github.com/spurin/masteringansible/tree/master/02%20-%20Ansible%20Architecture%20and%20Design/01%20-%20Ansible%20Inventories
+ Documentation : https://docs.ansible.com/ansible/latest/user_guide/intro_inventory.html

## Modules

+ Tutorial : https://github.com/spurin/masteringansible/tree/master/02%20-%20Ansible%20Architecture%20and%20Design/02%20-%20Ansible%20Modules
+ Documentation : https://docs.ansible.com/ansible/latest/user_guide/modules.html

## YAML

Tutorial : https://github.com/spurin/masteringansible/tree/master/02%20-%20Ansible%20Architecture%20and%20Design/03%20-%20YAML

## Playbooks

Tutorial : [Introduction to playbooks]("https://github.com/spurin/masteringansible/tree/master/02%20-%20Ansible%20Architecture%20and%20Design/04%20-%20Ansible%20Playbooks%2C%20Breakdown%20of%20sections")

## Variables

+ Tutorial : [playbook variables]("https://github.com/PacktPublishing/Mastering-Ansible/tree/master/02%20-%20Ansible%20Architecture%20and%20Design/05%20-%20Ansible%20Playbooks%2C%20Variables")
+ Documentation : https://docs.ansible.com/ansible/latest/user_guide/playbooks_variables.html

## Facts

+ Tutorial : [playbook facts]("https://github.com/PacktPublishing/Mastering-Ansible/tree/master/02%20-%20Ansible%20Architecture%20and%20Design/06%20-%20Ansible%20Playbooks%2C%20Facts")
+ Documentation : https://docs.ansible.com/ansible/latest/user_guide/playbooks_variables.html#variables-discovered-from-systems-facts

## Jinja2

+ Tutorial : [jinja2]("https://github.com/PacktPublishing/Mastering-Ansible/tree/master/02%20-%20Ansible%20Architecture%20and%20Design/07%20-%20Templating%20with%20Jinja2")
+ Documentation : https://docs.ansible.com/ansible/latest/user_guide/playbooks_templating.html

## Wrap up

+ Tutorial : [Wrap up of day1](https://github.com/PacktPublishing/Mastering-Ansible/tree/master/02%20-%20Ansible%20Architecture%20and%20Design/08%20-%20Ansible%20Playbooks%2C%20Creating%20and%20Executing)

## END OF DAY 1
