# POSTMAN COLLECTION FOR PET STORE PROJECT

### This project has couple of API's 

1. Find pet by ID

2. Update pet name

3. Delete a pet



### Command to run the postman collection

-> Clone this repo

-> Make sure to have Node.JS and newman installed globally followed by HTML Extra reporter
   (npm install -g newman-reporter-htmlextra)

### navigate to the path of this cloned repository folder and then run this command below from command line

-> newman run PetStoreCollection.json -r htmlextra