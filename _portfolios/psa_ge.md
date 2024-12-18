---
key: ge
title: Mobile game's config management system for game engineer
projectDate: 2020 - 2024
company: psa
category: Dev, Design

carousel:
  list:
    - url: assets/img/portfolios/ge_1.png
      desc:
      alt:
      type: image
    - url: assets/img/portfolios/ge_2.png
      desc:
      alt:
      type: image
    - url: assets/img/portfolios/ge_3.png
      desc:
      alt:
      type: image
    - url: assets/img/portfolios/ge_4.png
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
### Config Management and Manifest System

#### Overview

This high-performance SaaS platform is specifically designed for mobile games, streamlining the creation and management of JSON configurations and generating manifests critical for game functionality. It provides robust tools for game engineers to design and customize settings, ensuring seamless and personalized gameplay experiences tailored to user needs.

#### Key Features

**Config Management**  
Game engineers can create, merge, and manipulate JSON configs with tools for advanced operations such as concatenation and replacement. The system simplifies managing complex configurations across different game scenarios.

**Config Manifest Generation**  
The system generates manifests that are essential for mobile games to function. These manifests dynamically adapt to user data, enabling personalized experiences and ensuring games have the necessary configurations to operate seamlessly.

#### Usage

The system supports multiple games and environments, including QA and development. It generates manifests containing critical user-specific configurations essential for game functionality. These features make it an indispensable part of daily operations.

#### Performance and Scalability

The platform is built for high performance:

- Handles over 2,000 requests per second with an average manifest size of ~800KB.
- Leverages CDN for efficient content delivery and Redis cache to minimize latency and enhance throughput.

#### Integration

The system integrates with other company platforms to retrieve crucial user data, such as account balance and status. It employs Cosmos DB for secure data storage and Redis for caching user-specific configurations, ensuring quick and reliable data access.

By delivering high performance and adaptability, this system empowers personalized mobile gaming experiences while maintaining reliability and scalability at scale.
