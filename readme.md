# FYP Jenkins Jobs

This repository contains the definitions of Jenkins Jobs for my final year project. The jobs are defined as *yaml* files which are used by [Jenkins Job builder](https://docs.openstack.org/infra/jenkins-job-builder/) to create the jobs on a Jenkins server.

## Config File

A *config.ini* is required to. This is where details (url, credentials) are provided for a remote Jenkins server.

See [here](https://docs.openstack.org/infra/jenkins-job-builder/quick-start.html#use-case-2-updating-jenkins-jobs) for more details about configuration files.

## Usage

    jenkins-jobs --conf ./config.ini update jobs

