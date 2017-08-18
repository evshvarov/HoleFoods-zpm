# HoleFoods-zpm
ZPM compatible version of InterSystems DeepSee sample solution which illustrates the use of DeepSee Architect, Analyser, DeepSee dashboards, widgets and MDX queries.
# Installation
* Make sure you have git installed.

1. Install ZPM from : https://github.com/intersystems-community/PackageManager
2. Enter the following commands in Cache Terminal to install HoleFoods module from github:
> zpm

> zpm: USER> repo -type git -name GitRepo -url http://github.com/intersystems-community -DRepo=Holefoods-zpm -path C:\gitrepos

> zpm: USER> install isc.samples.deepsee.holefoods

