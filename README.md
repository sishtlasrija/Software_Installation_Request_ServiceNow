# Software_Installation_Request_ServiceNow

A ServiceNow-based solution that automates licensed software installation requests through Service Catalog, approval workflows, fulfillment tasks, and request tracking.

## Project Overview

This project provides a structured and automated process for employees to request licensed software through the ServiceNow Service Catalog. The employee submits the required software details, which are processed through an approval workflow. Once approved, a fulfillment task is automatically created and assigned to the Software Support Team.

## Key Features

- Service Catalog item for software installation requests
- Software name, version, license justification, and urgency fields
- Automated approval workflow
- Automatic creation of fulfillment tasks
- Request tracking through REQ, RITM, and SCTASK
- Email notification for submitted requests
- Business Rules and workflow automation
- Update Set for capturing and deploying configurations

## Workflow

Employee  
↓  
Service Catalog  
↓  
Software Installation Request  
↓  
REQ / RITM Creation  
↓  
Approval  
↓  
Email Notification  
↓  
Catalog Task (SCTASK)  
↓  
Software Support Team  
↓  
Request Completion

## Technologies Used

- ServiceNow
- Service Catalog
- Flow Designer / Workflow
- Business Rules
- Update Sets
- IT Service Management (ITSM)

## Project Documentation

The repository contains documentation for:

- Ideation Phase
- Requirement Analysis
- Project Design Phase
- Project Planning Phase
- Project Development Phase
- Project Documentation
- Project Demonstration

## Project Outcome

The solution provides a standardized way to manage licensed software installation requests, improves request visibility, reduces manual coordination, and provides a structured approval and fulfillment process.
