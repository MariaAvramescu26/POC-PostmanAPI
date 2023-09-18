Sure, here's a simple README for your Postman collection on GitHub:

# API Tests POC

This repository contains a Postman collection for testing APIs as a Proof of Concept (POC). The collection includes API requests and associated test scripts to verify their functionality.

## Collection Details

- **Collection Name**: API tests POC
- **Postman Collection ID**: 35d989e1-9ac0-41c1-a61f-7d361c704c1e
- **Postman Collection Schema**: [Collection Schema](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

## Included API Requests

### CoinDesk

- **Description**: This request retrieves data from the CoinDesk API.
- **HTTP Method**: GET
- **Endpoint**: [https://api.coindesk.com/v1/bpi/currentprice.json](https://api.coindesk.com/v1/bpi/currentprice.json)

#### Tests

- Status code is 200.
- Response time is less than 200ms.

### PostAPI

- **Description**: This request sends a POST request to a sample API endpoint.
- **HTTP Method**: POST
- **Endpoint**: [https://jsonplaceholder.typicode.com/posts](https://jsonplaceholder.typicode.com/posts)

#### Tests

- Status code is 201 (Created).
- Response time is less than 200ms.

## How to Use

1. Clone or fork this repository to your local machine.
2. Import the Postman collection JSON file into your Postman application.
3. Run the collection to execute the included API requests and tests.
4. View the results and make any necessary modifications to suit your testing needs.

Feel free to explore and modify this collection for your API testing requirements.

Please note that this repository is for educational and testing purposes only. Ensure you have the necessary permissions before using it for production purposes.
