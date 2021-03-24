+++
title = "OMS IAC"
date = "2021-03-09"
description = "OMS IAC"
tags = ["OMS"]
+++
# OMS IAC

## Introduction
This terraform script implements OMS infrastructure, using modules imported from https://git.yoox.net/projects/EOB/repos/terraform_module_oms

Each environment live in its own branch, COP is our develompent environment.

## Setup
Populate TF_VAR_vra_username, TF_VAR_vra_password, ARTIFACTORY_USERNAME and ARTIFACTORY_PASSWORD.

## Usage
Invoke terraform container via make file, eg:

```bash
make terraform_plan
```
Look at Makefile for list of available commands
