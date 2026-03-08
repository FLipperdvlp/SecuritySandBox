# School_66 Security Sandbox

## Overview

This repository is an experimental environment used to research and test secure browser communication features for the main project:

**Main project:**
https://github.com/FLipperdvlp/School_66

The goal of this repository is to safely prototype and analyze different approaches for secure messaging and communication between users in a web browser before integrating them into the main system.

## Purpose

This project is used for:

* Testing browser-based communication mechanisms
* Studying security vulnerabilities in web messaging systems
* Implementing experimental authentication and authorization approaches
* Testing protection mechanisms against common web attacks
* Prototyping secure communication logic before production deployment

## Technologies

The project is built using:

* **C#**
* **ASP.NET Core**
* **Web API**
* **Browser-based communication (HTTP / WebSocket / SignalR experiments)**
* **Security testing tools and logging**

## What is being tested

Possible security aspects that may be explored in this repository:

* Secure message transmission
* Authentication validation
* Session/token protection
* Protection against:

  * XSS (Cross-Site Scripting)
  * CSRF (Cross-Site Request Forgery)
  * Message interception
* Encryption approaches for browser communication

## Why this repository exists

Security-related experiments should not be performed directly in the production repository.
This sandbox allows safe testing, debugging, and analysis without affecting the stability of the main system.

Once a solution is validated, it can be integrated into the main project.

## Project Status

Experimental / Research

The code in this repository may change frequently and is not intended for production use.

## Author

Developer of the main project:
https://github.com/FLipperdvlp
