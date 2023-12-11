## What is Environment
  - An Environment is a system where a software application can be deployed and executed , i.e. It is needed to host any kind of application
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

  ![image](https://github.com/SurajKande/AutomationTesting/assets/37841586/38332166-e0bf-4cbd-975d-9344c88af6e1)
  - each blue box represents a server or a machine
  - we can have multipe physical servers / machines based on the number of products or seperating the servers for different testing teams for example like Automation testing team , Performance testing team, Manual teasting to team, so that they can work on their own environments for better testing results.
  - other environments can have multiple servers as well
  - Currently companies are using AWS to spin up and spin down the servers as they use
  - Each server comes with its seperate application like
    - Application server ( ex : tomcat ) [ web services are deployed on this application services ] 
    - seperate Database [ bascially host and contain all the data ]
    - seperate Configuration file [ set of text files which contain details related to the server and application ]

## Common Environmental Issues
  - Configuration File Issues
      - file not up to date or wrong Configuration info
  - Database related Issues
      - missing / bad data
      - missing / failed deployed scripts
  - Server related Issues
      - Server data being full , low spec's server used to run
      - firewall / proxy issues
      - wrong software / not upto date software versions are being used in the server
