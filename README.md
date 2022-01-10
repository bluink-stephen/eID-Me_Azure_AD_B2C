# A Custom Policy Template and Sample ASP.NET Core Web app for integrating eID-Me with Azure AD B2C

This repo contains sample code to integrate **Azure AD B2C** authentication with [eID-Me](https://bluink.ca). **eID-Me** is an identity verification and decentralized digital identity solution for Canadians. With **eID-Me**, **Azure AD B2C** tenants can strongly verify the identity of their users, obtain verified identity claims during Sign-up and Sign-in, and support multi-factor authentication (MFA) and password-free login using a secure digital identity. It enables organizations to meet Identity Assurance Level (IAL) 2 and Know Your Customer (KYC) requirements. Users will enjoy a simple and secure Sign-up and Sign-in experience while reducing fraud.

Detailed documentation on configuring a Custom Profile and the Web Application sample for integrating **eID-Me** with **Azure AD B2C** is available [here](https://bluink.ca/eid-me/azure-b2c-integration-guide).

## Custom Policy

The template XML files contained in the eIDMe\_Custom\_Policy\_Template directory enables applications to control the account sign-up process based on identity claims retrieved from a user's **eID-Me** digital identity.  It also enables a secure, simple sign-in process with Multi-Factor Authentication (MFA) without passwords, also using the same **eID-Me** digital identity.


## Sample ASP.NET Code

This sample ASP.NET code is a web application for **Azure AD B2C**, that illustrates how to invoke the Sign-up and Sign-in user journeys defined in the Custom Policy.  It also shows how to view the identity claims returned to the application in the ID Token and to determine whether an account was or was not created in **Azure AD B2C** during Sign-up.

