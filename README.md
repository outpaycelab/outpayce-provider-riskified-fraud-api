# Connect API Acceptance
## Non-Disclosure Agreement Reminder
As Outpayce S.A.U. is part from Amadeus IT Group S.A. all the agreements signed between Amadeus IT Group S.A. and your company are still applicable to all the content available in this [repository](https://github.com/outpaycelab/outpayce-provider-mips-api)..
## Introduction
The Fraud Connect API is a modern REST API for any Fraud Screening Partner needing to connect to Outpayce Xchange Payment Platform. 
In this repository, you will find:
* **Swagger specification**: API definition, its paths and components.
* **Test cases**:  a group of requests to test your configuration using the Postman app.
* **Provider questionnaire**: an excel file containing general and functional questions to better understand the capabilities you support. This file also includes a Network and technical section which will allow us to setup the connectivity between you and Amadeus. 

You will find more information about each of them in their specific folder.
## Context
### Prerequisites
* Connectivity with Amadeus
* Security rights to perform the operations
### Scope
This API covers fraud screening operations for Credit Card payments:
  * **Fraud Screening**: This operation will trigger a fraud screening request on a credit card – you may also receive extra information as external 3DS data or flight data.

 
  
## Integration steps
#### Please follow the differents steps in the table and update their status accordingly. 

TO BE COMPLETED

## API Authentication & Security

### Transport Layer Security (TLS):
To ensure communication security, the TLS protocol is designed to provide the following three essential services to all applications running above it:

Encryption: A mechanism to obfuscate what is sent from one host to another. <br>
Authentication: A mechanism to verify the validity of provided identification material.<br>
Integrity: A mechanism to detect message tampering and forgery.<br>
<br>Today Outpayce supports TLS 1.2 and TLS 1.3 versions.<br>


**NB:** For stronger security, **MTLS** (mutual TLS) can be implemented which is the usecase where both communicators have TLS certificate. We also provide IP whitelisting to restrict unauthorized access to the Outpayce system for inbound flow..

### API Authentication:
The authentications method supported by Fraud Connect API Acceptance today are:

#### - API KEY:
When using API key, the request header Authorization is populated with the key previously obtained through the provider system.
````
Host: <your_host>
Content-Type: application/vnd.amadeus+json 
Authorization: <API_KEY>
````

### Timeout Handling

The proposed request timeout is ````30 seconds````.

## Questions
For discussions related to any topic, the usual channels should be used.
