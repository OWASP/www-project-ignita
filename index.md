---
layout: col-sidebar
title: OWASP iGNITA
tags: ignita
level: 0


---
## OWASP iGNITA
To overcome the above mentioned problems, It is a fine game plan to build an own standalone analyser to detect vulnerabilities where the OWASP iGNITA Scanner will be independent from tools such as OWASP SonarQube, which will make the Framework more light and easy to set up, and users won’t be restricted to the API provided by the sonarqube or other scanners of such. Also creating a plugin for IDE’s which will be a faster way to detect vulnerabilities. And dockerize the Framework so the set up time will be minimal and less hectic. This plugin will also be proposed to be integrated into DevSecOps toolchain; github/jenkins/owasp appsec pipelines. Additionally a developer guide will be written with guidelines, templates and other titles for future collaborators.

## Requirement which satisfy the Important Selection Criteria,

Vulnerabilities it can detect (out of the OWASP Top Ten?) - Focused on top Ten
Can it be integrated into the developer's IDE? - Plugin is proposed to be developed
How hard is it to set up/use? - Dockerizing for easy setup
Can it be run continuously and automatically? - Will be tested and added to pipeline in github

### Features of the Analyzer
- The analyzer will initially focus on JAVA language
- Analyzer will be built to detect owasp top 10 vulnerabilities such as,
    - Injection
    - Broken Authentication
    - Sensitive Data Exposure
    - XEE
    - Broken Access Control
    - Security Misconfig
    - Cross site Scripting 
    - Insecure deserialization
