## 3b practical

## Catfact Ninja API Automation Suite

This repository contains an automated test suite for the Catfact Ninja API, developed as part of a technical assessment

## 📌 Project Overview

The objective of this project is to validate the reliability, data integrity, and performance of the Catfact Ninja public API. The suite covers functional "happy path" scenarios, negative input validation, and non-functional performance benchmarks.

## 🛠️ Tech Stack

Testing Tool: Postman (v10+)

Scripting Language: JavaScript

## 🧪 Test Coverage

The collection includes the following key test cases:

*1. Status & Schema Validation: Verifies 200 OK responses and ensures the JSON structure matches the expected contract.

2. Negative Validation (Type Safety): Ensures the API gracefully handles invalid data types (e.g., strings in integer fields) with 400 error codes.
 
3. Pagination: Dynamic testing of the limit parameter to ensure data returned does not exceed requested boundaries.
 
4. Performance Benchmarking: Asserts that response latency remains under 500ms to ensure a "Flash" service experience.*

## 🚀 How to Run Locally

**Import to Postman** 

1. Download the Catfact_Ninja.postman_collection.json from this repo.
2. Open Postman and click Import.
3. Drag and drop both file.
4. Set Base_url varibale to :  [https://catfact.ninja](https://catfact.ninja/)
5. Click Run Collection.
