# Code Complete
### Chapter 22 Testing
* Unit testing is the execution of a complete class, routine, or small program that has been written by a single programmer or team of programmers, which is
tested in isolation from the more complete system.
* Component testing is the execution of a class, package, small program, or other program element that involves the work of multiple programmers or
programming teams, which is tested in isolation from the more complete system.
* Integration testing is the combined execution of two or more classes, packages, components, or subsystems that have been created by multiple programmers or
programming teams. This kind of testing typically starts as soon as there are two classes to test and continues until the entire system is complete.
* Regression testing is the repetition of previously executed test cases for the purpose of finding defects in software that previously passed the same set of
tests.
* System testing is the execution of the software in its final configuration, including integration with other software and hardware systems. It tests for
security, performance, resource loss, timing problems, and other issues that can't be tested at lower levels of integration.

### Recommended Approach to Developer Testing
* Test for each relevant requirement to make sure that the requirements have been implemented. Plan the test cases for this step at the requirements stage or as early as possible—preferably before you begin writing the unit to be tested. Consider testing for common omissions in requirements. The level of security, storage, the installation procedure, and system reliability are all fair game for testing and are often overlooked at requirements time.
* Test for each relevant design concern to make sure that the design has been implemented. Plan the test cases for this step at the design stage or as early as possible— before you begin the detailed coding of the routine or class to be tested.
* Use "basis testing" to add detailed test cases to those that test the requirements and the design. Add data-flow tests, and then add the remaining test cases needed to thoroughly exercise the code. At a minimum, you should test every line of code. Basis testing and data-flow testing are described later in this chapter.
* Use a checklist of the kinds of errors you've made on the project to date or have made on previous projects.
