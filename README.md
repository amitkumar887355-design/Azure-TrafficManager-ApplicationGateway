# Azure Multi-Region Web Application

## Project Overview

This project demonstrates a highly available multi-region web application architecture on Microsoft Azure.

## Architecture

![Architecture](Architecture-Diagram.png)

## Services Used

- Azure Traffic Manager
- Azure Application Gateway
- Azure Linux Virtual Machines
- Azure Virtual Network
- Network Security Group


## Architecture Design

- US Region (East US)
  - 2 Linux Web Servers
  - Application Gateway

- India Region (Central India)
  - 2 Linux Web Servers
  - Application Gateway

- Traffic Manager configured with Performance Routing

## Key Features

- Low Latency User Experience
- Regional Traffic Routing
- High Availability
- Load Balancing
- Multi-Region Deployment

## Screenshots

See screenshots folder.

## Skills Demonstrated

- Azure Networking
- Traffic Manager
- Application Gateway
- NSG Configuration
- Linux VM Administration
- High Availability Design
