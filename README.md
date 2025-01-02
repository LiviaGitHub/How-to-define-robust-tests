# How to define robust tests

1. Define Clear Objectives.
   
- What to test:
  - Focus on core functionalities and critical cases.
  - Risk-Based Testing - Prioritizes areas of the software that are most prone to failure or have the greatest impact.
    
- What is most important to the user?
  - Real-user testing: Collect usage metrics and feedback.
  - Which feature takes the most time to test manually?
    
- Why to test: Understand the impact of a failure in each area.
  - Example: Payment feature.
 
- How to test: Choose the appropriate type (unit, integration, functional, etc.).
  - Automation -> integration, regression.
  - Manual -> UX, Features that change a lot and exploratory testing.

2. Follow the FIRST Principle.
  * Fast: Tests should be quick to run, avoiding delays in development.
  * Independent: Tests should not depend on one another.
  * Repeatable: Tests should always produce the same results.
  * Self-validating: Tests should be binary (pass or fail).
  * Timely: Write tests at the right time (ideally before or alongside the code).

3. Automation based on testing strategies.
   
  - Test automation may include:
    * Shift-Left Testing -  To identify and correct errors earlier. Early detection of defects.
    * Continuous delivery: Allows constant feedback on code quality. Set up CI pipelines to run automated tests whenever code is integrated into the repository (Jenkins, GitHub Actions, GitLab CI/CD).
    * Scalability: Repetitive testing is handled efficiently by automation.
    * Test Automation in Development Environments.
    * Regression Testing - Ensure that code changes do not break existing functionality.
    * Integration - Checks the interaction between modules or systems.
