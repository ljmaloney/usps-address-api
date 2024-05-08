Java library to call USPS address valitation API. 

This library is based around the USPS address APIs as of 2023. 

Firstly, to use the API, create a developer account with USPS at https://www.usps.com/business/web-tools-apis/welcome.htm

Once the registration is complete, USPS sends an email containing the USPS username and password. 

Usage:

1. Create an instance of UspsAddressClient with the username and password recieved from USPS
2. Call the UspsAddressClient.validateAddress method with the address to be validated
3. The method returns an instance of AddressResponse or throws an exception 
