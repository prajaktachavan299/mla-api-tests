# mla-api-tests
MLA Contract Testing using Postman
# MLA Contract Testing – Postman

This repository contains Postman collection and environment files
for MLA contract testing using a public API.

## Base URL
https://jsonplaceholder.typicode.com

## Files
- MLA-Contract-Tests.postman_collection.json
- MLA-Test-Env.postman_environment.json

## APIs Covered
- GET /posts
- GET /users
- GET /todos/1
- POST /posts

## How to Run
1. Open Postman
2. Click Import
3. Import both JSON files
4. Select environment: MLA-Test-Env
5. Open collection: MLA Contract Tests
6. Click Run (Collection Runner)

## Contract Tests Included
- Status code validation
- Response structure (keys) validation
- POST response ID validation
