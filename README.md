# Postman API Testing — ReqRes

This repository contains a Postman collection to practice and demonstrate API testing skills using the ReqRes public REST API.

## What’s included
- REST requests (GET/POST/PUT/DELETE) to common endpoints
- Positive and negative test cases
- Environment variables (base URL, credentials, token)
- Basic automated checks in Postman (status codes and JSON fields)
- Token handling via login request (stored in environment)

## Tech
- Postman
- ReqRes REST API

## How to use
1. Import the files from `/postman/` into Postman:
   - `ReqRes.postman_collection.json`
   - `ReqRes.postman_environment.json`
2. Select the `ReqRes` environment.
3. Run the collection (or individual folders) and review the test results.

## Notes
- ReqRes is a public API intended for testing and prototyping.
- Credentials used in the environment are the official sample values from ReqRes.

## Structure

/postman
ReqRes.postman_collection.json
ReqRes.postman_environment.json
