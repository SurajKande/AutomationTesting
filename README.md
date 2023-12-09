# Automation Testing
All About Automation Testing


## What is Test Automation
  - Test Automation is the use of software to execute tests without Human intervention
 
## Why Test Automation ?
  - Manual Validation of application functionality is inefficent in certain cases
  - expanding application feature sets are making comprehensive manual testing more tedious and difficult

## What is Environment
  - An Environment is a system where a software application can be deployed and executeD , i.e. It is needed to host any kind of application
  - Typically 4-tier deployment enivornment can be seen across most companies
  - There are several types of environments in the context of software development:
### 1. Development Environment ( Dev )
  - It is mostly used by the developers, It is where developers write code, debug code perform unit testing as well as integration testing
  - Once thr development is done and unit tested , it will be pushed to Testing Environments
### 2. Testing Environment
  - Used to test software for bugs and performance issues before deploying it
  - generally it is seperated into 2 seperate environments <b>QA & Regression</b>
  - the newly developed code / features will be manually tested by the testers in QA Environment, also know as feature testing or system testing
  - sometimes regression testing is done in parallel or most of the times it is done after the QA testing is finished
  - Regresison is mostly automated and it runs test scripts to make sure the existing or previous features are not broken because of the new change or feature.
  - Once the QA enginner's who perform the tests approve the change, the code then will be pushed to Staging Environment
### 3. Staging Environment ( UAT : User Acceptance Testing )
  - Similar to the production environment, it mirrors the production setup and is used for final testing before deploying new features or updates.
  - accessed by internal businessteams to verify if it satisfies the Clients and then inform the client to perform the UAT
  - once the Client confirms they're satisfied with the UAT, the code can then be pulished to the <b>Production ( or Live ) Environment</b>
### 4. Production Environment ( Live Environment )
  - Live Environment is where the software is finally deployed and accessed by end users for their uses
