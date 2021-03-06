Jenkins JIRA Plugin
===================

[![Build Status](https://jenkins.ci.cloudbees.com/buildStatus/icon?job=plugins/jira-plugin)](https://jenkins.ci.cloudbees.com/job/plugins/job/jira-plugin/)
[![Build Status](https://travis-ci.org/jenkinsci/jira-plugin.svg?branch=master)](https://travis-ci.org/jenkinsci/jira-plugin)
[![Coverage Status](https://coveralls.io/repos/jenkinsci/jira-plugin/badge.svg?branch=master&service=github)](https://coveralls.io/github/jenkinsci/jira-plugin?branch=master)
[![Issue Stats](http://issuestats.com/github/jenkinsci/jira-plugin/badge/pr?style=flat)](http://issuestats.com/github/jenkinsci/jira-plugin)


See [Wiki page](https://wiki.jenkins-ci.org/display/JENKINS/JIRA+Plugin) for more information.

Reported Issues: [by Votes](https://issues.jenkins-ci.org/browse/JENKINS-6110?jql=project%20%3D%20JENKINS%20AND%20resolution%20%3D%20Unresolved%20AND%20component%20%3D%20jira-plugin%20ORDER%20BY%20votes%20DESC%2C%20updated%20ASC%2C%20priority%20DESC%2C%20created%20ASC), [by Priority](https://issues.jenkins-ci.org/browse/JENKINS-26962?jql=project%20%3D%20JENKINS%20AND%20resolution%20%3D%20Unresolved%20AND%20component%20%3D%20jira-plugin%20ORDER%20BY%20priority%20DESC%2C%20votes%20ASC%2C%20updated%20ASC%2C%20created%20ASC)

Contributing to the Plugin
==========================

Plugin source code is hosted on [GitHub](https://github.com/jenkinsci/jira-plugin).
New feature proposals and bug fix proposals should be submitted as
[GitHub pull requests](https://help.github.com/articles/creating-a-pull-request).
Fork the repository on GitHub, prepare your change on your forked
copy, and submit a pull request (see [here](https://github.com/jenkinsci/jira-plugin/pulls) for open pull requests). Your pull request will be evaluated
by the [Cloudbees Jenkins job](https://jenkins.ci.cloudbees.com/job/plugins/job/jira-plugin/)
and you should receive e-mail with the results of the evaluation.

Before submitting your change, please assure that you've added a test
which verifies your change.  There have been many developers involved
in the git plugin and there are many, many users who depend on the
git-plugin.  Tests help us assure that we're delivering a reliable
plugin, and that we've communicated our intent to other developers in
a way that they can detect when they run tests.

Code coverage reporting is available as a maven target and is actively
monitored.  Please try your best to improve code coverage with tests
when you submit.

Before submitting your change, please review the findbugs output to
assure that you haven't introduced new findbugs warnings.
