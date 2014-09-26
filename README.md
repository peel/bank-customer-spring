# Bank Demo
## Customer

## Description
The service exposes Customer-related data as a REST service.

## Submit customer
curl -i -X POST -H "Content-Type:application/json" -d '{  "account" : "123456", "phone": "+48123456789", "address": "test@test.com",  "name" : "John Doe" }' http://localhost:8080/customers