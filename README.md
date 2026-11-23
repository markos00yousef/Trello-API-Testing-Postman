# Trello API Testing – Postman

## Project Overview
This project focuses on testing the Trello REST API using Postman. It covers different API operations to validate the functionality of boards, lists, cards, labels, and checklists.

The collection includes automated test scripts to validate API responses, status codes, response data, and resource creation.

## Tools & Technologies
- Postman
- Trello REST API
- JavaScript (Postman Test Scripts)
- JSON

## Project Structure

```text
Trello-API-Testing-Postman/
│
├── Trello-API-Testing.postman_collection.json
├── Trello-Environment.postman_environment.json
└── README.md
```

## API Testing Coverage

The collection contains 20 requests organized into 5 folders:

| Folder | Requests | Coverage |
|---|---:|---|
| Authentication | 1 | Retrieve authenticated member information |
| Boards | 6 | Get, create, retrieve, update, and delete boards |
| Lists | 2 | Create lists |
| Cards | 8 | Create, retrieve, move cards, manage checklists and attachments |
| Labels | 3 | Create and retrieve labels |

## Testing Features
- Validate HTTP response status codes.
- Verify response content and JSON structure.
- Validate returned resource IDs and names.
- Use environment variables to manage dynamic resource IDs.
- Store generated IDs for reuse in subsequent requests.
- Organize API requests into logical folders.

## Environment Configuration

To run this collection, you need a Trello API Key and Token.

1. Import the Postman Collection into Postman.
2. Import the Environment Template.
3. Add your own Trello API Key and Token to the environment variables:
   - `key`
   - `token`
4. Select the imported environment before running requests.
5. Save the environment.

**Note:** Never share or upload your actual API Key or Token.

## How to Run
1. Open Postman.
2. Import the collection JSON file.
3. Import and configure the environment.
4. Select the Trello Environment.
5. Open the required request and click **Send**.
6. To execute the collection, open the Collection Runner and run the requests in the appropriate order.

**Important:** Some requests create, update, or delete Trello resources. Review the requests before running the entire collection.

## Project Objective
The objective of this project is to practice REST API testing, understand HTTP methods, validate API responses, manage dynamic test data, and write automated assertions using Postman.
## Screenshots

### Collection Overview & API Response
![Collection Overview](Screenshots/01-Collection-Overview.png)

### Postman Test Results
![Test Results](Screenshots/02-Test-Results.png)

### Test Scripts & Assertions
![Test Scripts](Screenshots/03-Test-Scripts.png)


## Author

**Markos Youssef**

Software Tester | ISTQB® Certified Tester (CTFL v4.0)
