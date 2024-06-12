# Jamf Compliance Editor

## Establishing Compliance Baselines

Regulated industries and government agencies that handle sensitive or classified data are required by their InfoSec teams to harden and secure endpoints as much as possible.

Other organizations may not need the highest security possible, but may still want to achieve a custom level of security they can track and enforce.

Staying on top of all the changes and features in every macOS, iOS, or iPadOS release is cumbersome and time-consuming and may lead to data leaks or exfiltration.

Various government entities and organizations have provided guidance that details settings/controls that should be reviewed when developing security compliance policies. These are known as security benchmarks. A benchmark is a set of best-practice cybersecurity standards for a range of IT systems and products.

Your organization may choose to develop its own security benchmark or may be required to adopt one of the well-known security benchmarks or baselines including CIS, NIST 800-53 & 800-171, DISA STIG, CNSSI, and CMMC.

## Jamf Compliance Editor

Jamf Compliance Editor is a tool that provides macOS, iOS/iPadOS system administrators with an easy way to establish and manage compliance baselines on their fleet of Apple devices.

This tool is built on the foundations of the macOS Security Compliance Project, hosted by the United States government agency, NIST, in their Github repo.

This application features:

* Easily selectable benchmark/baselines for customization
* Support for all variations of benchmark/baselines currently offered by the macOS Security Compliance Project.
* Support for multiple major macOS, iOS/iPadOS versions
* Modificiation of organization-defined values (ODV) from the core compliance project specifications
* Local storage of your custom benchmark(s) for editing later
* An easy-to-use UI that eliminates the need for complicated scripting
* One-click guidance creation that includes:
* PDF, Excel, HTML, and Adoc for audit review with option to add branding
* (macOS only) Shell script (zsh) that can audit and remediate endpoint
* All configuration profiles needed to be uploaded to MDM server
* (macOS only) Jamf Pro Extension Attributes that will submit status of benchmark/baseline of endpoints

## Support

Jamf Compliance Editor application version 1.2.1 and higher supports macOS Sonoma.

A User's Guide is available in this repository. 

You can interact with other users in the #jamf-compliance-editor channel on MacAdmins Slack. The applicaton is based on the [macOS Security Compliance Project](https://github.com/usnistgov/macos_security) with discussions in MacAdmins Slack's #macos_security_compliance project. 