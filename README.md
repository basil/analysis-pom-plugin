# Analysis POM

[![Join the chat at https://gitter.im/jenkinsci/warnings-plugin](https://badges.gitter.im/jenkinsci/warnings-plugin.svg)](https://gitter.im/jenkinsci/warnings-plugin?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Jenkins Version](https://img.shields.io/badge/Jenkins-2.138.4-green.svg?label=min.%20Jenkins)](https://jenkins.io/download/)
![JDK8](https://img.shields.io/badge/jdk-8-yellow.svg?label=min.%20JDK)
[![License: MIT](https://img.shields.io/badge/license-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This static analysis POM serves as parent POM for all my Jenkins Plugins. It basically enhances the 
[Parent POM for Jenkins Plugins](https://github.com/jenkinsci/plugin-pom) 
with a predefined configuration of several static analysis tools. Additionally, it provides a fix set of test dependencies that are common
to all my plugins. This POM enforces the [Java style guide](https://github.com/uhafner/codingstyle) that I am using
in these plugins (and in my lectures at the Munich University of Applied Sciences).

[![Jenkins](https://ci.jenkins.io/job/Plugins/job/analysis-pom-plugin/job/master/badge/icon)](https://ci.jenkins.io/job/Plugins/job/analysis-pom-plugin/job/master/)
[![GitHub Actions](https://github.com/jenkinsci/analysis-pom-plugin/workflows/GitHub%20Actions/badge.svg)](https://github.com/jenkinsci/analysis-pom-plugin/actions)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/jenkinsci/analysis-pom-plugin.svg)](https://github.com/jenkinsci/analysis-pom-plugin/pulls)
