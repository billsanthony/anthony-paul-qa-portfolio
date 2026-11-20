# API Testing Practice Plan

## Goal
Practice checking API behavior using a public test API and an API client. This document is a learning plan; tests and outcomes will be added after execution.


## Suggested practice API
JSONPlaceholder: https://jsonplaceholder.typicode.com/

## Planned checks
- GET resource returns an appropriate successful status code.
- Response body is valid JSON and includes expected fields.
- A request for a known resource ID returns the correct shape.
- A request for an unknown ID is handled consistently.
- Query parameters return the intended subset/filter behavior where supported.
- POST request behavior is documented as simulated/demo behavior (not assumed to persist).

## Example endpoint to practice
`GET https://jsonplaceholder.typicode.com/posts/1`

Record:
- Request method and URL
- Status code
- Response time as shown by the tool
- Response headers of interest
- Response body fields and data types
- Expected vs. actual result
- Screenshot or exported evidence

## API test report template
| Test ID | Method | Endpoint | Expected | Actual | Status | Evidence |
|---|---|---|---|---|---|
| API-001 | GET | `/posts/1` | Successful response with post object | Not recorded | Not Run | |
| API-002 | GET | `/posts/999999` | Confirm behavior for unknown ID | Not recorded | Not Run | |


## Learning notes
Add notes here after hands-on API testing. Avoid claiming API test experience until the exercises have been performed and documented.
