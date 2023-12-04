# HOW TO SIMULATE A TRANSFER FROM ONE TTK BASED DFSP TO ANOTHER THROUGH A MOJALOOP BASED SWITCH.

#### By: Elijah Okello . DevOps Engineer Intern. ThitsaWorks Pte.Ltd


## Introduction

The mojaloop testing toolkit(TTK) is a functional / testing tool kit that FSPs and Hubs can use for self-testing, FSP onboarding and FSP feature development. In this guide, I show how we can simulate a transfer between two TTK instances, one acting as a payer and the other as a payee. This will be facilitated through a helm based deployment of mojaloop as per the current deployment documentation for Mojaloop Acacia v15.1.0 at the time of writing this documentation.

## Pre-requisites

You must have access or know the following to be able to successfully complete this tutorial

- A computer with 16+GB Ram, 4+ CPUS and 40+GB Disk space and ability to execute privileged commands (32GB RAM recommended)
- Preferred OS Ubuntu 22.0 but any other OS where you can run kubernetes in minikube or k3s should be fine.
- Working knowledge of kubernetes and helm (Not expert)
- Familiarity with Mojaloop concepts 
