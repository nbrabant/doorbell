# Doorbell

## Introduction

This project is a way to use IOT button to communicate with Alexa like as a doorbell

## Prerequisites

* An Amazon developper account (required for managing skills and login with Amazon LWA)
* An Alexa enabled device associated to your account
* An AWS account (for managing lambda)

## Installation

First, install [ASK CLI](https://developer.amazon.com/fr-FR/docs/alexa/smapi/quick-start-alexa-skills-kit-command-line-interface.html) and deploy the skill to your Alexa developper account. In the next step, link the skill to your AWS console account (LWA). And finally, in the permission menu, activate the "Send Alexa events" option to get the client Id and secret.

The next step is to attach IOT button to your AWS Lambda : go to your IOT Core interface and add your IOT button, then attach a new lambda function action.



## Usage

## Technical schema

![Sequence diagram](doorbell.png)

**Diagram.net link**

https://app.diagrams.net/#G1l5yIitg1NbGZEqSB4hyoNtQxvMHbtTqo
