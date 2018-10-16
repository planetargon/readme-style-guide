# Planet Argons README Style Guide

This file is to outline what a quality README file should contain. Here we are talking specifically for a Rails application.
A good README file should contain all information required for a new team memeber to get up to speed. It should be a snapshot
of the application as a whole. A reminder to keep sensitive data secure and out of source control as you modify your project's
README.

## Table of Contents

  * [Application Description](#application-description)
  * [Third Party Dependencies](#third-party-dependencies)
  * [Local Setup](#local-setup)
  * [Testing](#testing)
  * [Deployment](#deployment)




## Application Description

This first section should provide a good description of what the purpose of the application is. It needs to cover all
the different functions of the application has. This is also where we want to see all domains that the application is
responsible for in production and their responsibilities. After a new team member reads this section they should have a
high level idea of the application's function and it's overall purpose.

## Third Party Dependencies

In this section we expect to see all third party APIs being used. Examples being New Relic, Akamai, Zendesk. A brief description
of their responsiblity in the application is also recommended.


## Local Setup

We want to see a list of steps required to start the application in a local environment. After the developer has completed
these steps the application should be accessible locally, and the test suite should be prepared to run

## Testing

A section in regards to how to run the test suite is a must since different applications use different commands to kick off
the test suite.

## Deployment

Document a brief description of the hosting environment as well as any steps the developer needs to complete before they
are able to deploy. We also want to see the steps needed to deploy the application.
