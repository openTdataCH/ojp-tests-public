# OJP tests for Switzerland (OJP 1.0 and 2.0)

This repository contains tests for OJP instances in Europe, with a primary focus on the Swiss server (see https://opentransportdata.swiss).

## OJP 2.0 — Bruno

Some tests for Bruno:
- https://github.com/openTdataCH/ojp-tests-public/tree/main/OJP-Regression-Tests

To use the Bruno collections, set the following environment variables:
- `BearerToken`
- `server` (the base URL)

You can set these as global or local environment variables in Bruno. Our OJP provider also supplies a Postman collection with the same tests, which you can use as well. SoapUI tests are no longer supported.


## Real-time data

### How to use

There are test collections for Postman and Bruno. For real-time use cases, we provide sample data that you can use to test your own environment and to see how it handles exceptional cases.

To obtain an OJP 2.0 INT API key, contact us at the email below. The real-time collection works only against the OJP 2.0 INT instance.

Link: https://github.com/openTdataCH/ojp-tests-public/tree/main/Realtime%20tests

## OJP 2.0 request/response examples and automated tests

We have test cases for OJP 2.0. In the `ojp2-req-res-examples` folder, there is a Python program that:
- downloads the `develop` branch of the repository,
- generates responses from the provided requests, and
- validates the responses (including known validation errors).

Folder link: https://github.com/openTdataCH/ojp-tests-public/tree/main/ojp2-req-res-examples

See also our API Explorer: https://opentdatach.github.io/api-explorer/

# Contact
If you have questions contact opendata@sbb.ch.

# License
The programs here are made available as AGPL. The tests are made available as CC-BY-SA.
