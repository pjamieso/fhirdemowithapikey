# FHIR API Key demo

# Cloud FHIR Integration with API Key

## INTRODUCTION 

This document describes a sample FHIR application, which was developed to provide a template for building an Angular full stack application in a secure manner using an API key.  The application is open source and can be downloaded at: [https://github.com/pjamieso/fhirdemowithapikey](https://github.com/pjamieso/fhirdemowithapikey). The app uses the IRIS FHIR Accelerator Service, a cloud based FHIR service, which is easy to deploy. The FHIR Accelerator Service has many useful features including:

• An Enterprise-grade managed FHIR service easily provisioned and launched on AWS

• Support for FHIR R4

• ISO 27001:2013, supporting HIPAA and GDPR, built on the AWS HITRUST-certified platform

• A development portal for understanding and testing FHIR APIs

• Support for multiple methods of authentication including API Key Authentication, OAuth 2.0, and OpenID connect

• Bulk import of FHIR bundles via S3

• Logging of FHIR request data

Developers can try the service for free by signing up at [https://portal.live.isccloud.io/account/login](https://portal.live.isccloud.io/account/login)

The application addresses a practical problem, how to securely retrieve personal health information (PHI), stored in a FHIR server. This demo uses an API key, but a better approach is using OAuth 2.0, a modern security framework enabling distributed authentication and authorization. You can get that demo at [https://github.com/pjamieso/fhirokta]

To use the demo, first create a deployment with the IRIS FHIR Accelerator Service at [https://portal.live.isccloud.io/account/login]. For a small deployment, this is entirely free, no credit card required. 

After you have launched your deployment, go to the credentials tab and create an API key. Copy this key to your clipboard and paste it in xapikey in the environment.ts file. Go back to the overview tab under deployments and copy the Api Key Endpoint to the clipboard and paste that next to fhirbaseurl in the enviroment.ts file.

If you have any questions, please drop me a line at [patrick.jamieson@intersystems.com](mailto:patrick.jamieson@intersystems.com)

Patrick W. Jamieson, M.D.

Product Manager, IRIS for Health.

******************************************************************

FHIR INTEGRATION DEMO

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 12.1.4. To install use npm install and then npm update.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
