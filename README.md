
# Steps to test collections 

1. Clone JSON file from https://github.com/Sasha-Bullet/api-pets
2. Import api-pet.postman_collection.json to the postman.
3. Run api/pet collections.

# Api collection include tests :  

### Test Cases for v2/pet/findByStatus
- Verify that the status code 200 is in response.
- Verify that the response time is less than 1500ms. 
- Verify that the response items exist. 
- Verify that the Response item status should be as we search for. 
- Verify that the status code name has string 'OK'. 


### POST - v2/pet/{petId}
- Verify that the status code 200 is in response.
- Verify that the response message is equal to 'id'. 
- Verify that the response time is less than 200ms.
- Verify that we have Successful POST request.
