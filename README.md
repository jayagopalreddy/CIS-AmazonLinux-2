<<<<<<< HEAD
# CIS-AmazonLinux-2 - v1.0.0 - Latest

## Amazon Linux 2 - CIS Benchmark Hardening Script

This Ansible script is under development and is considered a work in progress.

This Ansible script can be used to harden a Amazon Linux 2 machine to be CIS compliant to meet level 1 or level 2 requirements.

This role will make significant changes to systems and could break the running operations of machines. Considering using this script on a test machine before using the script against other production level systems for remediation. Use this script at your own risk and no warranty is attached for the usage of this script as dictated by the license.

## System Requirements
```
Ansible 2.7+
Amazon Linux 2
```
## Role
```
role: CIS-AmazonLinux-2
```
## Role/Playbook Tags
```
tags: 
level1
level2
always
prelim_tasks
post_tasks
```
## Section Vars
```
section1
section2
section3
section4
section5
section6
```
## Vars
```
Refer to defaults/main.yml for other vars
```
## Sample Playbook.ymls
```
Refer to AmazonLinux-2-CIS_Benchmark_(level1, level1_and_level2, or level2).ymls for sample playbook.ymls. Change the role to match role folder name.
```
