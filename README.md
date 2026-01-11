# qa-automation-quality-gates
Production-ready QA automation framework demonstrating structured API and functional testing, CI/CD integration, risk analysis, and negative/positive test coverage. Designed to showcase professional QA practices for automation and software engineering roles.


Here’s the order you should implement them in your `tests/` folder:

1. **Smoke Test**  
   - Test that the API/service is reachable and returns 200 for health endpoints.

2. **Positive Test Cases**  
   - Valid API requests return expected responses (correct fields, data types).

3. **Negative Test Cases**  
   - Invalid inputs produce correct error codes (400, 404, etc.).
   - Missing required fields handled properly.

4. **Boundary & Edge Cases**  
   - Maximum/minimum input values.
   - Empty or null payloads.
   - Large payloads.

5. **Regression Test**  
   - Verify core functionality after new changes.
   - Re-run positive test suite with previous inputs.

6. **Performance / Response Validation**  
   - Measure response times.
   - Fail if latency exceeds threshold.

7. **CI/CD Integration Test**  
   - Automate all previous tests in a GitHub Actions workflow.
   - Fail build if any test fails or if linting errors exist.
