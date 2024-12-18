---
key: ops
title: Mobile app for credit card of a Hongkong's bank
projectDate: 2022 - 2024
company: psa
category: Dev, Design

carousel:
  list:
    - url: assets/img/portfolios/ops_1.png
      desc:
      alt:
      type: image
    - url: assets/img/portfolios/ops_2.png
      desc:
      alt:
      type: image
    - url: assets/img/portfolios/ops_3.png
      desc:
      alt:
      type: image
    - url: assets/img/portfolios/ops_4.png
      desc:
      alt:
      type: image
skills:
  languages:
    csharp:
    typescript:
    javascript:
    sql:
    html:
    css:
  frameworks:
    dotnet:
    vuejs:
    graphql:
    bootstrap:
  devops:
    docker:
    git:
    github:
    jenkins:
  platforms:
    azure:
  databases:
    sqlserver:
    redis:
  methodologies:
    scrum:
    kanban:
---
### Internal System for Config Support

#### Overview

This internal system extends the functionality of the configuration management system, specifically supporting the daily operations of product managers and business analysts. It simplifies the process of creating and managing JSON configurations by allowing users to upload Excel files and convert them into configuration files without requiring knowledge of game logic.

#### Key Features

**Excel to JSON Conversion**  
- Users prepare Excel files with required fields such as monetization design, data analysis, and other parameters.  
- A streamlined process allows frequent updates for scenarios like holidays, DAU changes, or shifting targets.  
- Game engineers write TypeScript scripts to convert Excel files into JSON configurations, which are executed by a worker for efficiency.  
- Users can enable, disable, or schedule Excel file uploads to meet operational needs.  

**Config Deployment Scheduling**  
- Users can schedule the deployment of configurations, enabling a more flexible and efficient workflow.  

**A/B Testing and Segmentation**  
- Enables users to create product-level A/B tests and segments.  
- Supports greater variety in configuration combinations tailored to diverse user groups.  

**GraphQL Integration**  
- Leverages GraphQL to fetch data from the config management system with multiple parameters.  
- Enhances frontend capabilities by allowing selection of required fields and logical operations in queries.  

#### Usage

The system empowers non-technical users, such as product managers and business analysts, to:  
- Automate configuration updates through Excel uploads.  
- Experiment with various product setups through A/B tests and segments.  
- Schedule configuration deployments for improved workflow flexibility.  
- Collaborate effectively with game engineers for script development and data conversion.  

By reducing manual efforts and increasing operational efficiency, this system bridges the gap between data preparation and game logic implementation, streamlining workflows for game-related configurations.
