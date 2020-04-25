# Postmannewman
package.json
{
  "name": "postman-newman-jenkins",
  "version": "1.0.0",
  "description": "project for storing postman test",
  "directories": {
    "test": "tests"
  }
} "scripts": {
  "test1": "newman run Billing Order API Tests.postman_collection.json -e BO1.postman_environment.json -d data.csv",
  "report": "newman run Billing Order API Tests.postman_collection.json -e BO1.postman_environment.json -d data.csv -r html",
} "author"="Lavanya", "dependencies": {
  "newman": "5.0.0"
} 
}
