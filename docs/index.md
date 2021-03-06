---
hide:
  - navigation
---

# VIAME-Web-NOAA-GCP Documentation

The site details how to deploy and manage an instance of VIAME-Web on a NOAA Fisheries-hardened [virtual machine](https://cloud.google.com/compute) (VM) in a [GCP Project](https://sites.google.com/noaa.gov/fisheriescloudservices/home) within the [NOAA Fisheries Cloud](https://sites.google.com/noaa.gov/nmfs-hq-ocio-cloud-portal/home). 

These instructions were developed from [DIVE Deployment Scenario 1](https://kitware.github.io/dive/Deployment-Provision/) with the extensive help and expertise of the VIAME team, in particular Brandon Davis and Bryon Lewis, and Ed Rodgers. Note that these docs do not supersede any of the [DIVE docs](https://kitware.github.io/dive). Rather, they supplement the [DIVE deployment options](https://kitware.github.io/dive/Deployment-Overview/) by providing NOAA Fisheries Cloud-specific deployment instructions.

## Deploy your own instance

See the [Deployment Guide](deployment-general.md) for step-by-step instructions on how to deploy your own instance of VIAME-Web in GCP in the NOAA Fisheries Cloud.

## Terminology

Per Kitware's [concepts and definitions](https://kitware.github.io/dive/#concepts-and-definitions), a deployment of VIAME-Web is a deployment of DIVE Web with associated marine biology-centric [pipelines and algorithms](admin-general.md#addon-management). This repo and associated documentation were designed for users deploying the whole VIAME-Web platform, but note that they  could also be used to deploy only an instance of DIVE-Web.
