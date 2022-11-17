# Payment_Gateway_SystemDesign
The main agenda of this repository is to showcase the merchant payment system working arcitecture design with a systematic diagram .

## Basic terminologies

### Payment Gateway :
A service which allows us to make payments online while making purchase from e-commerce website. It supports paying through card , internet banking , e-wallet etc.

### Payment Processor:
It is the main part of the payment gateway which starts the processing of the request by verifying the authorization passed by the issuer bank and saves the information in the database .

### Payment service provider (PSP):
It is the service which makes such that money is transferred from buyers account to merchants account .

### Issuer Bank:
This is the bank which buyer is related to .

### Card Association :
This is the entity which links a card number to its relavent issuing bank like visa,mastercard etc .

### Payment Card Industry Data Security Standards (PCIDSS):
It is a security standard , if a seller is complaiant with this standard then payment page can be generated on sellers page else they need to re-direct the request to payment gateways's payment page which is complaint with this standards.

### Acquiring Bank:
Bank associated with seller's payment processor

### ISO-8583:
EFT switch message format for card payment processing .


