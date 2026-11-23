# Trello API Testing – Test Scenarios

## 1. Authentication

| ID | Test Scenario | Expected Result |
|---|---|---|
| TS-01 | Verify retrieving authenticated member information using valid API credentials. | API returns HTTP 200 with authenticated member details. |

## 2. Boards

| ID | Test Scenario | Expected Result |
|---|---|---|
| TS-02 | Verify retrieving all boards associated with the authenticated account. | API returns HTTP 200 with the boards list. |
| TS-03 | Verify creating a new board with valid data. | Board is created successfully and its ID is stored. |
| TS-04 | Verify retrieving a specific board using its ID. | API returns the correct board details. |
| TS-05 | Verify retrieving lists associated with a specific board. | API returns the board's lists. |
| TS-06 | Verify updating an existing board's name. | Board name is updated successfully. |
| TS-07 | Verify deleting an existing board. | Board is deleted successfully. |

## 3. Lists

| ID | Test Scenario | Expected Result |
|---|---|---|
| TS-08 | Verify creating a new list on an existing board. | List is created and its ID is stored. |
| TS-09 | Verify creating another list on the same board. | Second list is created successfully. |

## 4. Cards

| ID | Test Scenario | Expected Result |
|---|---|---|
| TS-10 | Verify creating a card in the first list. | Card is created and its ID is stored. |
| TS-11 | Verify creating a second card. | Card is created successfully. |
| TS-12 | Verify creating a third card. | Card is created successfully. |
| TS-13 | Verify retrieving cards from a list. | API returns the cards associated with the list. |
| TS-14 | Verify creating a checklist on a card. | Checklist is created successfully. |
| TS-15 | Verify adding a checklist item. | Checklist item is added successfully. |
| TS-16 | Verify attaching a file or URL to a card. | Attachment is added successfully. |
| TS-17 | Verify moving cards between lists. | Cards are moved to the target list successfully. |

## 5. Labels

| ID | Test Scenario | Expected Result |
|---|---|---|
| TS-18 | Verify creating a label on a board. | Label is created successfully. |
| TS-19 | Verify creating another label. | Second label is created successfully. |
| TS-20 | Verify retrieving labels associated with a board. | API returns the board's labels. |

## Test Execution Notes

- API requests were executed using Postman.
- Environment variables were used to manage API credentials and dynamic resource IDs.
- Postman test scripts were used to validate responses and returned data.
- Actual execution results are available in the Postman screenshots.

## Author

**Markos Youssef**

Software Tester | ISTQB® Certified Tester (CTFL v4.0)