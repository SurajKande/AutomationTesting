# Automation Testing
All About Automation Testing


## What is Test Automation
  - Test Automation is the use of software to execute tests without Human intervention
 
## Why Test Automation ?
  - Manual Validation of application functionality is inefficent in certain cases
  - expanding application feature sets are making comprehensive manual testing more tedious and difficult

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

## Agile
  - <b>Agile Methodology</b> : It is a practice that encourges continuous development and testing throughout the project software development cycle.
    
  - <b>Agile FrameWorks<b/> : An Agile framework is a specific approach to planning, managing, and executing work
    * Agile frameworks typically fall into two categories
        1. Frameworks designed for teams, and
        2. frameworks designed to help organizations practice Agile at scale, across many teams.
    * There is no single “best” Agile framework. The best approach for your team or organization will depend on a variety of factors, including your industry, Agile maturity, number of Agile teams, and goals for Agile within your organization.
    * Scrum is one of the most used Agile FrameWork, there are other frameworks like Kanaban , XP, Etc.
       
  - <b>Agile Testing<b> : It simply means following the Agile Principles in Testing the software.
  - <b>Agile Testing Methodology</b> : The goal of the Agile Automation Testing is to improve the effectiveness and efficiency of the software development process while maintaining quality, time and resource consumption.
  
      ![image](https://github.com/SurajKande/AutomationTesting/assets/37841586/35448c89-3c8b-4fbe-bc4f-65bdc186f40b)                   ![image](https://github.com/SurajKande/AutomationTesting/assets/37841586/faf48f11-2c02-49ee-8b21-bb4adc7f4af4)

  - Agile is an approach for software development where it goes through the phases as Waterfall model , but the phases are divided into iterations.
  - implied the whole project is divided into seperate sets , with each set having features ( new or modified ) that can be developed and delivered independently, only few product features will be worked on each iteration.
  - Hence each feature developed in respesctive iterations go through all the phases of SDLC, hence not impacting the complete development , reducing the risks and also allowing the customer to see the subsets of product constantly.

  - These Iterations are called as <b>Sprints</b> in the Agile Model. Each Sprints span about 2 to 4 weeks and No of Sprints depends on the size of the project.
  - A lot of collaboration is needed in between teams from QA , DevOPS, developers , etc as each Sprint is a complete implementation of features, any bugs, issues regarding those features must be dealt within the sprint.  Hence all the teams must collaborate and work with each other for effective and efficient Development.

  - Scrum : It is One of a type of FrameWork which helps in executing Agile Methodology, i.e. it provides a framework within which multiple processes and techniques can be used.
  - Scrum Roles
    1. Scrum Master : The Scrum Master ensures that the team maintains scrum values and has the following responsibilities.
         - Get rid of roadblocks for efficiency and Productivity.
         - Organize Sprint planning sessions.
         - Conduct retrospective reviews.
         - Conduct daily scrum meetings.
         - Communicate with stakeholders.

    2. Product Owner : The Product Owner ensures that the teams contributions are aligned with the broader product goals. They are aware of product business requirements, such as client expectations and market trends. The following are the responsibilities of the Product owner
         -   Increasing the value of the work done
         -   Setting the Team's Product vision
         -   Ensuring that the team is focused on meeting product requirements by communicating and assessing the progress

    3. Scrum Team : The team is cross-functional, i.e. the team inclodes analysis, designers, developers, testers and others as needed and appropriate for the project development. The Following are the responsibilities of the Scrum Team
         - Support Sprint Planning and target setting
         - Contribute knowledge to the programming , design and improvement of product
         - Determine the best development strategies
         - Include testing products and prototypes, as well as other methods
         - they have all the skills needed to complete the tasks without relying on anyone outside the team, it is designed to enhance flexibility, innovation and productivity hence saving time and effort.
