# Postman collection
**What is a Postman collection?**

It is a series of prepared requests using the different paths presented in the specification. Using this, you will be able to test the configuration of your server.
There's more details regarding each different request inside the collection, which you can explore using the Postman app.
## Usage
We encourage you to import the Postman collection to the Postman desktop app where you will find all the available functionalities. 
 1. Download the [Postman app](https://dl.pstmn.io/download/latest/win64).
 2. Install it.
 3. Import the files inside the Postman folder.
![How to use postman](https://github.com/outpaycelab/outpayce-provider-mips-api/blob/main/assets/animation-postman.gif)

## Content
Using this tool you will be able to test the different requests and scenarios while connected to your server. Once all the requests are working you can send us the report with the results.
### Environment
You must complete the environment file with information related to your server and the type of payment to be tested, this can be done using the Postman app or editing the file. There are some example values that you can change.
### Scenarios
These are the use cases that you will find inside the collection:
* Fraud Screening
  * Success Fraud Screening
    - Success 3DSv2 1pax 1leg
    - Success no3DS 1pax 1lega
    - Success 3DSv2 2pax MultiLeg
  * Error Scenarios
    - Error 400 NoBody
    - Error 401 WrongAPIKey
    - Error 404 PathNotFound
    - Error 405 WrongMethod
    - Error 422 NoCardNumber
    - Error 422 PriInBodyDifferentFromHeader
    - Error 500 InternalServer
  
You will have more information regarding the scenarios and the variables inside the collection. 
