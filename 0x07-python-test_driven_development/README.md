0x07. Python - Test-driven development

Testing is the process of evaluating a system or its component(s) with the intent to find whether it satisfies the specified requirements or not. Testing is executing a system in order to identify any gaps, errors, or missing requirements contrary to the actual requirements.

On this project we are covering a test driven development. I have touched on bases such as:
 * Bad reputation
	> “Testing is Too Expensive”: Pay less for testing during software development => pay more for maintenance or correction later. Early testing saves both time and 		cost in many aspects.
	> “Testing is Time-Consuming”: Testing is never a time-consuming process. However diagnosing and fixing the errors identified during proper testing is a time-
		consuming but productive activity.
	> “Only Fully Developed Products are Tested”: No doubt, testing depends on the source code but reviewing requirements and developing test cases is independent
		from the developed code.
	> “Complete Testing is Possible”: It becomes an issue when a client or tester thinks that complete testing is possible. It is possible that all paths have been
		tested by the team but occurrence of complete testing is never possible.
	> A Tested Software is Bug-Free”: No one can claim with absolute certainty that a software application is 100% bug-free even if a tester with superb testing
		skills has tested the application.
	> “Testers are Responsible for Quality of Product”: It is a very common misinterpretation that only testers or the testing team should be responsible for product		quality. Testers’ responsibilities include the identification of bugs to the stakeholders and then it is their decision whether they will fix the bug or
		release the software. 
	> “Test Automation should be used wherever possible to Reduce Time”: Yes, it is true that Test Automation reduces the testing time, but it is not possible to
		start test automation at any time during software development. Test automaton should be started when the software has been manually tested and is stable 		to some extent.
 * Basic
	> This standard deals with the following aspects to determine the quality of a software application:

    	Quality model
    	External metrics
    	Internal metrics
    	Quality in use metrics

	> This standard presents some set of quality attributes for any software such as:

    	Functionality
    	Reliability
    	Usability
    	Efficiency
    	Maintainability
    	Portability

 * Functional Testing
	> This is a type of black-box testing that is based on the specifications of the software that is to be tested. The application is tested by providing input and 		then the results are examined that need to conform to the functionality it was intended for. Functional testing of a software is conducted on a complete, 		integrated system to evaluate the system’s compliance with its specified requirements.

	> There are five steps that are involved while testing an application for functionality:

    		The determination of the functionality that the intended application is meant to perform.
    		The creation of test data based on the specifications of the application.
    		The output based on the test data and the specifications of the application.
    		The writing of test scenarios and the execution of test cases.
    		The comparison of actual and expected results based on the executed test cases.

	> An effective testing practice will see the above steps applied to the testing policies of every organization and hence it will make sure that the organization 		maintains the strictest of standards when it comes to software quality.

 * Unit Testing
	> This type of testing is performed by developers before the setup is handed over to the testing team to formally execute the test cases.
	> Limitations of Unit Testing:
		Testing cannot catch each and every bug in an application. It is impossible to evaluate every execution path in every software application. The same is
		the case with unit testing.
		There is a limit to the number of scenarios and test data that a developer can use to verify a source code. After having exhausted all the options, there
		is no choice but to stop unit testing and merge the code segment with other units.

 * Intergration Testing
	> Integration testing is defined as the testing of combined parts of an application to determine if they function correctly. Integration testing can be done in
	two ways:
		Bottom-up integration: This testing begins with unit testing, followed by tests of progressively higher-level combinations of units called modules or
		builds.
		Top-down integration: In this testing, the highest-level modules are tested first and progressively, lower-level modules are tested thereafter.

	>In a comprehensive software development environment, bottom-up testing is usually done first, followed by top-down testing.

 * System Testing
	> System testing tests the system as a whole.
	> System testing is important because of the following reasons:
		System testing is the first step in the Software Development Life Cycle, where the application is tested as a whole.
		The application is tested thoroughly to verify that it meets the functional and technical specifications.
		The application is tested in an environment that is very close to the production environment where the application will be deployed.
		System testing enables us to test, verify, and validate both the business requirements as well as the application architecture.

 * Regression Testing
	> Whenever a change in a software application is made, it is quite possible that other areas within the application have been affected by this change. Regression 		testing is performed to verify that a fixed bug hasn’t resulted in another functionality or business rule violation.
	> Regression testing is important because of the following reasons:
		Minimize the gaps in testing when an application with changes made has to be tested.
		Testing the new changes to verify that the changes made did not affect any other area of the application.
		Mitigates risks when regression testing is performed on the application.
		Test coverage is increased without compromising timelines.
		Increase speed to market the product.

 * Acceptance Testing
 * Alpha Testing
 * Beta Testing
 * Non-Functional Testing
 * Usability Testing
 * Security Testing
 * Portability Testin

Have also covered:
 * Test Plan
 * Test Scenario
 * Test Case
