# The Basic Concepts of Software Testing 
## 1-Software Development Lifecycle (SDLC)
### What is a SDLC ? 
**The Software Development Lifecycle** is a methodology used for developing software. The process comprises a series of steps needed for building, maintaining, altering, replacing or enhancing the components of software.
#### The Models of Software Testing in SDLC 
Software teams can choose any of many software development lifecycle models during their projects. Each model contains a series of unique steps that the team has to follow to complete the project.
#### Sequential Models

<img src="https://github.com/ELMehdiNaor/The-Complete-2022-Software-Testing-Bootcamp/blob/main/1-Basic%20Concepts%20of%20Software%20Testing/Images/waterfallModel.png" width="600" height="400"> 

- **The Waterfall development model** follows a linearly sequential flow. In this methodolgy, the requirement analysis, designing, development, integration, testing and deployment phases are clearly defined in separate phases and none of these phases overlap each other. The project workflow only proceeds forward and teams cannot begin one phase before the previous phase ends.

<img src="https://github.com/ELMehdiNaor/The-Complete-2022-Software-Testing-Bootcamp/blob/main/1-Basic%20Concepts%20of%20Software%20Testing/Images/vModel.png" width="600" height="400">

- **The V-shaped model** is similar to the waterfall model in many ways. However, one significant change in how the testing of software components is planned. Furthermore, the project does not follow a downward trend toward completion. Instead, the process turns upwards after the development phase and testers use the test plans created earlier to evaluate specific components of the product. The shift starting from the development phase allows forming a typical V-shape.

#### Iterative and Incremental Models

<img src="https://github.com/ELMehdiNaor/The-Complete-2022-Software-Testing-Bootcamp/blob/main/1-Basic%20Concepts%20of%20Software%20Testing/Images/Agile.png" width="600" height="400">

**The Agile model** is centered around the iterative and incremental approach and cross-functional teams work in collaboration to meet the requirements of their clients. These projects require constant engagement with clients and are able to handle requirements more effectively than other models. Less time is spent in requirement analysis and more emphasis is given on pratical feedback from clients after using developed software components
## 2-Software Testing 
### What is Software Testing?
**Software Testing** is the process of evaluating and veryfying that a software product or application does what it is supposed to do. The benifits of testing include preventig bugs, reducing development costs and improving performance
### Why do we need Software Testing?
**Software Testing** is important because if there are any bugs or errors in the software, they can be identified early and fixed before the software products is delivered. A properly tested software product ensures dependability, security and high performance, which leads to time saving, cost effectiveness and customer satisfaction.
### What are the objectives of Software Testing?
Some of the **significant objectives** of sofware testing are as follows: 
- To evaluate the work products such as requirements, design, user stories and code
- To verify the fulfillment of all the specified requirements 
- To validate if the test object is complete and work as per the expectation of the users and the stakeholders
- To build confidence in the quality level of he test object
- To prevent defects in the software product
- To provide sufficient information to stakeholders to allow them to make informed decisions, especially regarding the l   level of quality of the test object
- To reduce the level of risk of insufficient software quality
- To comply with contractual, legal, or regulatory requirements or standards, and to verify the test objects compliance w   with such requirements or standards
## 3-The Test Process  
<img src="https://github.com/ELMehdiNaor/The-Complete-2022-Software-Testing-Bootcamp/blob/main/1-Basic%20Concepts%20of%20Software%20Testing/Images/Testprocess.png" width="800" height="400">

There is no one universal software test process, but there are common sets of test activities without which testing will be less likely to achieve its established objectives. These sets of test activities are a test process. The proper, specific software test process in any given situation depends on many factors.

A **test process** consists of the following main groups of activities:

- **Test planing**
- **Test monitoring and control**
- **Test analysis**
- **Test design**
- **Test implementation**
- **Test execution**
- **Test completion** 

Each main group of the activities cited above is composed on constituent activities
## 4-The Test Levels
<img src="https://github.com/ELMehdiNaor/The-Complete-2022-Software-Testing-Bootcamp/blob/main/1-Basic%20Concepts%20of%20Software%20Testing/Images/levels-of-testing.jpg" width="500" height="400"> 

There are mainly four **Levels of Testing** in software testing:
- **Unit Testing**: also known as componenet testing or module testing focuses on components that are separately testable
- **Integration Testing**: focuses on interaction between components or systems
- **System Testing**: focuses on the behaviour and capabilities of a whole system or product, often considering the end-   to-end tasks the system can perform and the non-functional behaviors it exhibits while performing those tasks
- **Acceptance Testing**: like system testing, typically focuses on the behavior and capabilities of a whole system or     product
## 5-Testing Types
Based on the focused area, testing types are defined as follows:
- **Functional Testing**: is a software testing technique that tests what the system does
- **Non Functional Testing**: is a software testing technique that tests how well the system performs
- **Structural Testing**: is the type of testing carried out to test the structure of code. It is also known as **White      Box Testing**
- **Regression Testing**: is the repeated testing of an already tested program, after modificatin, to discover any d       defects introduced or uncovered as a result of the change 
