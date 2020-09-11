# Awesome Cisco DNA Center [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)


A curated list of awesome [Cisco DNA Center](https://developer.cisco.com/dnacenter/) frameworks, libraries, sdk, sample codes and resources.  
_(Inspired by [sindresorhus/awesome](https://github.com/sindresorhus/awesome))_.

See full list of Code Samples on [Cisco DevNet CodeExchange](https://developer.cisco.com/codeexchange/)


## Index


- [Awesome Cisco DNA Center](#awesome-cisco-dna-center)
  - [Getting Started](#getting-started)
  - [Platform / SDK](#platform--sdk)
  - [Plug and Play](#plug-and-play-pnp)
  - [Automation](#automation)
  - [Security](#security)
  - [Assurance](#assurance)
  - [Reports](#reports)
  - [Resources](#resources)


## Getting Started


- [Postman Collection](https://github.com/CiscoDevNet/DNAC-postman)
  - Postman collection and environment for Cisco DNA Center
- [DNAC-Top5](https://developer.cisco.com/codeexchange/github/repo/CiscoDevNet/DNAC-Top5)
  - Simple scripts to get started with Cisco DNA Center API.
- [Cisco DevNet Learning Labs: DNAv3 Sample Code](https://github.com/CiscoDevNet/dne-dna-code/tree/master/intro-dnac)
![](https://img.shields.io/badge/python-blue.svg)
  - Part of Cisco DevNet Express Track
- [usecases_sample_code](https://github.com/cisco-en-programmability/usecases_sample_code)
![](https://img.shields.io/badge/python-blue.svg)
  - This repository has examples for different use cases using Cisco DNA Center APIs. All of the examples have a functions file that uses the python requests library and some also show how to achieve the same outcome with the [Cisco DNA Center Python SDK](https://github.com/cisco-en-programmability/dnacentersdk)


## Platform / SDK


- [dnacentersdk](https://github.com/cisco-en-programmability/dnacentersdk)
<a href="https://developer.cisco.com/codeexchange/platforms/dnac#lang=Python">![](https://img.shields.io/badge/python-blue.svg)</a>
  - Cisco DNA Center Python SDK
- [DNAC-Python-Wrapper](https://developer.cisco.com/codeexchange/github/repo/rsayle/DNAC-Python-Wrapper)
![](https://img.shields.io/badge/python-blue.svg)
  - A python wrapper for easily accessing a Cisco DNA Center cluster
- [Cisco.DnaCenter.Api](https://developer.cisco.com/codeexchange/github/repo/panoramicdata/Cisco.DnaCenter.Api)
<a href="https://developer.cisco.com/codeexchange/platforms/dnac#lang=C">![](https://img.shields.io/badge/-c%23-blue.svg)</a>
  - Right-click on the project and click "Manage Nuget packages"
- [Cisco DNA Center AURA (Audit & Upgrade Readiness)](https://github.com/CiscoDevNet/DNAC-AURA)
  ![](https://img.shields.io/badge/python-blue.svg)
    - The Cisco DNA Center AURA (Audit & Upgrade Readiness) command line tool performs a variety of health, scale & upgrade readiness checks for the DNA Center and the rest of the Fabric network.
- [cisco-dnac-scrt-session](https://github.com/joshhalley/cisco-dnac-scrt-session)
  - Cisco DNAC Session Generator for SecureCRT


## Plug and Play (PNP)


- [DNAC-onboarding-tools](https://developer.cisco.com/codeexchange/github/repo/CiscoDevNet/DNAC-onboarding-tools)
<a href="https://developer.cisco.com/codeexchange/platforms/dnac#lang=Python">![](https://img.shields.io/badge/python-blue.svg)</a>
  - Cisco DNA Center PnP-BulkConfig app allows uploading of "predefined" rules to onboard network devices.
- [DNAC-ClaimAP-Mobile-App](https://developer.cisco.com/codeexchange/github/repo/CiscoDevNet/DNAC-ClaimAP-Mobile-App)
![](https://img.shields.io/badge/javascript-blue.svg)
  - DNACenter ClaimDevices mobile app to claim Day-0 or DNA-C supported Plug-n-Play(PnP) devices and provision it.
- [DNAC_AP_PnP](https://github.com/zapodeanu/DNAC_AP_PnP)
![](https://img.shields.io/badge/python-blue.svg)
  - Workflow automation for Access Points PnP Provisioning using DNA Center and ServiceNow


## Automation


- Ansible
  - [ansible-dnac-modules](https://developer.cisco.com/codeexchange/github/repo/jandiorio/ansible-dnac-modules)
  ![](https://img.shields.io/badge/python-blue.svg)
    - These modules provide declarative and idempotent access to configure the design elements of Cisco's DNA Center....
  - [ansible-dnac-inventory-plugin](https://developer.cisco.com/codeexchange/github/repo/jandiorio/ansible-dnac-inventory-plugin)
  ![](https://img.shields.io/badge/python-blue.svg)
    - DNA Center Inventory Plugin allows you to utilize the network discovery...
  - [dnac_site_settings_example](https://developer.cisco.com/codeexchange/github/repo/wwt/dnac_site_settings_example)
  ![](https://img.shields.io/badge/python-blue.svg)
    - Sample use case for using the Ansible wwt.ansible_dnac collection created for Cisco Automation Exchange.


- Templates
  - [DNAC-TemplateProgrammer](https://github.com/CiscoDevNet/DNAC-TemplateProgrammer)
  ![](https://img.shields.io/badge/python-blue.svg)
    - These scripts demonstrate the template programmer API on Cisco DNA Center. The scripts assume the templates have been setup on Cisco DNA center in advance.
  - [DNAC-TemplateTool](https://developer.cisco.com/codeexchange/github/repo/CiscoDevNet/DNAC-TemplateTool)
    - A tool for backing up and restoring templates
  - [Automate-Creation-of-DNAC-template-to-enable-packet-capture-on-IOS-XE](https://developer.cisco.com/codeexchange/github/repo/Abhijith-R/Automate-Creation-of-DNAC-template-to-enable-packet-capture-on-IOS-XE)
    - A python script to automate the packet capture on IOS-XE, create a pcap file and copy it to local machine using secure copy.
  - [vtlcli-docker](https://developer.cisco.com/codeexchange/github/repo/nickrusso42518/vtlcli-docker)
    - Docker wrapper for VTL template development


- [DNAC-AppHostingAPI](https://developer.cisco.com/codeexchange/github/repo/CiscoDevNet/DNAC-AppHostingAPI)
  - This repository contains a few simple scripts to get started with Cisco DNAC Application Hosting API.
- [DNAC-Site_Automation](https://developer.cisco.com/codeexchange/github/repo/CiscoDevNet/DNAC-Site_Automation)
  - Automate Site Creation and Automation and Device assignment using Cisco DNA Center APIs
- [dna_workflows](https://developer.cisco.com/codeexchange/github/repo/cunningr/dna_workflows)
  - A framework for building automated workflows for Cisco DNA Center
- [cisco-dnac-network-devices-cfg-backup-s3](https://developer.cisco.com/codeexchange/github/repo/robertcsapo/cisco-dnac-network-devices-cfg-backup-s3)
![](https://img.shields.io/badge/python-blue.svg)
  - Backup your Cisco Network Devices Configuration on S3 Storage
- [dnacenter_ip_address_conflict_prevention](https://github.com/cisco-en-programmability/dnacenter_ip_address_conflict_prevention)
![](https://img.shields.io/badge/python-blue.svg)
  - This repo includes sample code to prevent the configuration of new IP addresses that may create IP address conflicts. It will use Cisco DNA Center REST APIs.


## Security


- [Cisco-DNA-Center-with-Cisco-PSIRT-API-integration](https://developer.cisco.com/codeexchange/github/repo/CiscoDevNet/Cisco-DNA-Center-with-Cisco-PSIRT-API-integration)
  - The purpose of this application is to generate a CSV file containing all the vulnerabilities that affect the devices that are part of a Cisco DNA Center managed network.
- [vault](https://developer.cisco.com/codeexchange/github/repo/CiscoDevNet/vault)
![](https://img.shields.io/badge/python-blue.svg)
  - Securing your API authentication keys with Vault


## Assurance


- [DNAC-NOC](https://developer.cisco.com/codeexchange/github/repo/CiscoDevNet/DNAC-NOC)
  - NOC dashboard based on TIG (telegraf/influx/grafana)
- [webhook_receiver](https://github.com/zapodeanu/webhook_receiver)
![](https://img.shields.io/badge/python-blue.svg)
  - Webhook receiver for Cisco DNA Center, SD-WAN. It will send Notifications to Cisco Webex Teams
- [cisco-dnac-platform-webex-notifications](https://github.com/robertcsapo/cisco-dnac-platform-webex-notifications)
![](https://img.shields.io/badge/python-blue.svg)
  - Receive Events from Cisco DNA Center and push the information to Cisco Webex Teams
- [dnacenter_splunk_add_on_app](https://github.com/cisco-en-programmability/dnacenter_splunk_add_on_app)
  - This repo includes a simple Splunk Add-On app that will collect device inventory and overall network health data from Cisco DNA Center.


## Reports


- [dnac-InterfacePortSpeedReport](https://developer.cisco.com/codeexchange/github/repo/CiscoDevNet/dnac-InterfacePortSpeedReport)
  - Cisco DNA Center - Interfaces Speed (custom) Report
- [DNAC-Monitoring-App](https://developer.cisco.com/codeexchange/github/repo/oborys/DNAC-Monitoring-App)
  - DNAC Monitoring App extends the basic features of DNA-C. This App help collect information about devices and manage network issues.


## Resources


- [Cisco DNA Center](https://www.cisco.com/c/en/us/products/cloud-systems-management/dna-center/index.html)
  - [Developer Docs](https://developer.cisco.com/docs/dna-center/)
- [Cisco DevNet](https://developer.cisco.com/)
  - [Learning Labs](https://developer.cisco.com/learning/labs/tags/Cisco+DNA+Center,Networking/page/1)
  - [Sandbox](https://developer.cisco.com/docs/sandbox/#!networking/networking-overview)
  - [Code Exchange](https://developer.cisco.com/codeexchange/platforms/dnac)
  - [Automation Exchange](https://developer.cisco.com/network-automation/listing/#product=Cisco%20DNA%20Center)


# Contributing


Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/robertcsapo/awesome-cisco-dnac/blob/master/CONTRIBUTING.md) first.


# Maintainers

- Robert Csapo ([@robertcsapo](https://twitter.com/robertcsapo))
