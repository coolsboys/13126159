##How to ensure the quality of a software system


####Test early and often
Delib have a strong belief that where possible quality should be built in throughout the development life cycle rather than tested in at the end of a project. This is an important part of the agile development process which we use when making our apps. We test what we do, whether it’s design, code, or documentation, early and often so that defects are found while the work is still fresh in people’s minds and before the defects can become too deeply embedded in the software.

####Minimise variation
Any customisation of the software introduces variation which needs to be tested and maintained for every version of the app. Lean manufacturing has taught us that by minimising variation and developing apps which work for people out of the box we can reduce costs and more thoroughly test what we make, increasing the value of what we do for our clients. We recommend to our clients that they avoid paying us to customise our apps when possible so that we can provide them with the most cost efficient solution.

####Build in flexibility
Where there is a common need for the same customisation from lots of clients we try to allow for this by building flexibility into the system. This limited and known variation can be accounted for when testing and does not add a huge cost overhead to our development process, while at the same time allowing our clients to change the things they need to.

####Use great tools
Tools like Selenium and Jenkins enable us to run automated tests on our apps to ensure that any changes we make don’t break the existing features which our clients rely on. We continually make use of these tools throughout our development cycle.

####Try out new ideas
We are always eager to learn about anything which might help us increase the quality and value of what we produce. Moving from the specification driven waterfall development model to the more flexible agile methodology was a big change for us, but adopting lean production methods is the thing that has given us the largest benefits.


The most intuition way of SQA is software testing. The purpose of software testing is to detect errors in the software. The tester should ideally detect all errors before the software is released to the customer. However, full test coverage of a program is impossible. Software testing is a trade-off between budget, time and quality. Here are six functional tests to ensure software quality.

####Unit Testing

Unit testing is the process of testing each unit of code in a single component. This form of testing is carried out by the developer as the component is being developed. The developer is responsible for ensuring that each detail of the implementation is logically correct.

####Functional Testing

Functional testing addresses concerns surrounding the correct implementation of functional requirements. Commonly referred to as black box testing, this type of testing requires no knowledge of the underlying implementation. Functional test suites are created from requirement use cases, with each scenario becoming a functional test. As a component is implemented, the respective functional test is applied to it after it has been unit tested.For many projects, it is unreasonable to test every functional aspect of the software. Instead, define functional testing goals that are appropriate for the project. Prioritize critical and widely used functions and include other functions as time and resources permit.

####System Testing

System testing executes end-to-end functional tests that cross software units, helping to realize the goal of ensuring that components combine to deliver the desired business result. In defining the project's system testing goals, focus on those scenarios that require critical units to integrate.

####Regression Testing

Regression testing ensures code modifications have not inadvertently introduced bugs into the system or changed existing functionality. Goals for regression testing should include plans from the original unit, as well as functional and system tests phases to demonstrate that existing functionality behaves as intended.

####System Integration Testing

System integration testing is a process that assesses the software's interoperability and cooperation with other applications. Define testing goals that will exercise required communication. This is done using process flows that encapsulate the entire system.

####Acceptance Testing

Acceptance testing aims to test how well users interact with the system, that it does what they expect and is easy to use. Although it is the final phase of testing before software deployment, the tests themselves should be defined as early as possible in the Software Development Life Cycle. Early definition ensures customer expectations are set appropriately and confirms for designers that what they are building will satisfy the end user's requirements. To that end, acceptance test cases are developed from user requirements and are validated in conjunction with actual end users of the system. The process results in acceptance or rejection of the final product.
