# Project 20 - AWS Application Load Balancer

## Project Overview
This project demonstrates load balancing using an AWS Application Load Balancer (ALB).

## AWS Services Used
- Amazon EC2
- Application Load Balancer
- Target Groups
- Security Groups
- HTTP Listener

## AWS Region
Asia Pacific (Singapore) - ap-southeast-1

## Architecture

Internet
   |
Application Load Balancer
   |
Target Group
   |
EC2 Server 1 and EC2 Server 2

## Project Features
- Distributes incoming HTTP traffic between two EC2 instances.
- Performs health checks on backend servers.
- Uses an HTTP listener on port 80.
- Demonstrates load balancing through SERVER 1 and SERVER 2 responses.

## Terraform
Terraform data sources document and read the existing AWS infrastructure.

## Testing
Successfully tested the ALB DNS endpoint and verified responses from both backend servers.
