# REST API Testing with Postman

## Project overview
Original starter QA portfolio project using the public Restful Booker demo API.
Base URL: https://restful-booker.herokuapp.com

## Scope
Health check, authentication, booking IDs, create/read/update/partial update/delete booking, and invalid-ID handling.

## Setup
1. Import `Restful_Booker_Postman_Collection.json` into Postman.
2. Create an environment with `baseUrl` = `https://restful-booker.herokuapp.com`, `token` blank, and `bookingId` blank.
3. Run requests in order. The collection saves the token and created booking ID into environment variables.
4. Record real outcomes in `API_Test_Cases.xlsx`; add only reproducible defects to the bug template.
5. Capture your own request/response screenshots.

The demo API commonly documents `admin` / `password123` as sample credentials. If authentication fails, consult https://restful-booker.herokuapp.com/apidoc/index.html. Never use real credentials or personal data.

IMPORTANT: This is a prepared starter project, not evidence that tests have already been executed. Run the requests yourself and update the results. The public demo may change, reset, or be unavailable.
