As a Application Developer
I need a Continuous Integration pipeline
So that my code is automatically built and tested every time I push changes.

###Details and Assumptions
Uses GitHub Actions for automation.
The project uses Python/Flask (based on the template).
Pipeline should run on every push to the main branch.

###Acceptance Criteria
Gherkin
Given a code change is pushed to the repository
When the GitHub Actions workflow is triggered
Then the build should succeed and all unit tests must pass
