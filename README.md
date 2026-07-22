# Open Test Reporting Maven Plugin

[Maven report plugin](https://maven.apache.org/guides/plugin/guide-java-report-plugin-development.html) for [open-test-reporting](https://github.com/ota4j-team/open-test-reporting).

## Context

Currently, open-test-reporting has no official maven plugin that can be configured to automatically generate test report.  
This means that using it in Maven projects requires additional workarounds, see [#734](https://github.com/ota4j-team/open-test-reporting/issues/734).

This project aims at implementing a reporting plugin to attach opent-test-reporting to Maven lifecycles hooks.

The code is heavily inspired by the Maven surefire reporting implementation, available [here](https://github.com/apache/maven-surefire/tree/master/maven-surefire-report-plugin).

## Design



