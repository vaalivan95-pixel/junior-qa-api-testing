 API Test Execution Report



Project: DummyJSON REST API Testing  

Test Date: October 15, 2026  

Test Environment: DummyJSON Public API  

Tools: Postman, JavaScript, Chai Assertions  

Execution Method: Postman Collection Runner



 1. Test Objective



Validate the functionality of the DummyJSON Products API, including successful requests, error handling, pagination, search functionality and response data validation.



\## 2. Test Execution Summary



| Metric | Result |

|---|---|

| Total API requests | 6 |

| Total automated tests | 49 |

| Passed | 49 |

| Failed | 0 |

| Skipped | 0 |

| Execution errors | 0 |

| Iterations | 1 |

| Total execution time | 1.759 seconds |

| Average response time | 215 ms |



\*\*Execution Status: PASSED\*\*



\## 3. Test Scenarios



| Scenario | Tests | Status |

|---|---:|---|

| POST — Create Product | 8 | PASS |

| GET — Non-existent Product | 5 | PASS |

| GET — Product Pagination | 9 | PASS |

| GET — Search Products | 8 | PASS |

| GET — Product by ID | 9 | PASS |

| GET — All Products | 10 | PASS |

| \*\*Total\*\* | \*\*49\*\* | \*\*PASS\*\* |



\## 4. Validation Coverage



The executed tests cover HTTP status codes, JSON response structure, field presence, data types, positive numeric values, unique identifiers, search relevance and pagination parameters.



Both positive and negative request scenarios were tested.



\## 5. Defect Summary



No product defects were confirmed during the documented execution.



The negative test returning HTTP 404 passed because the status was expected for a non-existent product.



\## 6. Test Limitations



Testing was performed against a public demonstration API using one Collection Runner iteration.



DummyJSON simulates product creation without permanent data persistence. The test results reflect the tested scenarios and do not guarantee full API reliability or complete functionality coverage.



\## 7. Conclusion



All 49 automated tests passed successfully, with no failed tests or execution errors.



The tested API scenarios met their defined assertions at the time of execution.



\*\*Final Result: PASS\*\*



\## 8. Evidence



Execution screenshots are available in the `screenshots/` directory of this repository.

