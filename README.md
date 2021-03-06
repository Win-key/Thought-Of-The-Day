# Thought-Of-The-Day
Thought Of the day is the repo to keep the valuable information that we may need today or tomorrow

S.O.L.I.D stands for:
=======================

S - Single-responsiblity principle.
	A class or function should have one and only one reason to change

O - Open-closed principle.
	Functionality must be open for extension but closed for modification

L - Liskov substitution principle.
	You should be able to replace a super class with a sub class anywhere in the program without any unexpected behaviour
	
I - Interface segregation principle.
	Create simple, focused interfaces instead of bloated big ones

D - Dependency Inversion Principle.
	A class should not depend on another concrete class, instead it should depend on an abstraction

Domain Modeling
===============
* Entities ** Relationships *** Responsbility

* Derived from an understanding of system-level requirements, identifying domain entities and their relationships provides an effective basis for understanding and helps practitioners design systems for maintainability, testability, and incremental development
* Domain modeling is a primary modeling area in Agile development at scale.

* Domain modeling simply reflects our understanding of real-world entities and their relationships and responsibilities that cover the problem domain.
* Domain modeling is typically developed and continuously refined by the System Architect in collaboration with other stakeholders

** In a large scale Agile development, domain modeling is continuously used to support: 
	* Analysis of Epics 
	* Backlog Refinement at Large Solution, Program and Team levels
	* Design workshops at different levels
	* Refining Vision and Roadmap (typically in preparation for Program Increment)


** Epic -- Typically introduces new entities, relationships and responsibilities
** Feature -- May introduce new entities, typically introduces new relationships or responsibilities
** Story Typically introduces changes to the existing relationships and responsibilities, may introduce new responsibilities, value objects or changes to the service interfaces
** Enabler Epic -- Typically affects implementation and design aspects of a whole range of entities, services, and repositories such as underlying technology or platform, a generic life cycle of the entities, API constraints etc.E 
** Enabler Feature -- Introduces changes to implementation/design aspects for a) only certain entities/services typically constrained to one product or system; b) only certain lifecycle steps (e.g.: instantiation). Enabler features may also result in a change of responsibilities or may introduce new value objects. 
** Refactor -- May extract individual value objects or “helper” objects out of an entity, may change internal interfaces between entities, protocols or APIs.


Data Structure
==============
* Efficient Data Structure :: Efficient Algorithm


Four Pillars of Object Oriented Programming (OOP)
=================================================
*  Abstraction
*  Encapsulation
*  Inheritance
*  Polymorphism

Functional programming
======================
*  Functional programming is used for performing many different operations for which the data is fixed. Object-oriented programming used for performing few operations which are having common behavior and different variants.
*  Functional programming is having a stateless programming model. Object-oriented programming is having a stateful programming model.
*  In functional programming, a state does not exist. In object-oriented programming, the state exists.
*  In functional programming, a function is the primary manipulation unit. In object-oriented, an object is the primary manipulation unit.
*  In functional programming, its functions have no side effects means does not make any impact on code that is running on multiple processors. In Object-oriented programming, its methods can have side effects and may put an impact on processors.
*  In functional programming, the main focus of programming is what are we doing. In object-oriented programming, the main focus of programming is how are we doing.
*  Functional programming mainly supports abstraction over data and abstraction over behavior. Object-oriented programming mainly supports abstraction over data only.
*  Functional programming provides high performance in processing the large data for the applications. Object-oriented programming is not good for big data processing.
*  Functional programming does not support conditional statements. In Object-oriented programming, conditional statements can be used like if-else statements and switch statement.

When you anticipate a different kind of software evolution:

Object-oriented languages are good when you have a fixed set of operations on things, and as your code evolves, you primarily add new things. This can be accomplished by adding new classes which implement existing methods, and the existing classes are left alone.

Functional languages are good when you have a fixed set of things, and as your code evolves, you primarily add new operations on existing things. This can be accomplished by adding new functions which compute with existing data types, and the existing functions are left alone.

When evolution goes the wrong way, you have problems:

Adding a new operation to an object-oriented program may require editing many class definitions to add a new method.

Adding a new kind of thing to a functional program may require editing many function definitions to add a new case.

Code refactoring
================
Code refactoring is the process of restructuring existing computer code—changing the factoring—without changing its external behavior.

"Refactoring is the process of changing a software system in such a way that it does not alter the external behavior of the code yet improves its internal structure." -- MartinFowler in

Code smell
==========
"Smells are certain structures in the code that indicate violation of fundamental design principles and negatively impact design quality"
Code smell are nothing but a pattern of code that is not well writen and there are high possibiliy for error cause of that code. 
How to find : Code review and static analysis tool like Sonar 
=============
Eg : We assign a variable to null and calling it in the next line. This cause the NullPointerException
	 When we use a loop but not increamenting the loop counter.
	 When we use a switch statement but not having a default clause.
	 Using toString() on a string
	 
Software engineering
====================
Software engineering is the systematic application of engineering approaches to the development of software.[1][2][3] Software engineering is a direct sub-field of engineering and has an overlap with computer science and management science.[4] It is also considered a part of overall systems engineering.

Software development process
============================
	Software development life cycle (SDLC).
	
	Practices
		2.1	Continuous integration
		2.2	Prototyping
		2.3	Incremental development
		2.4	Rapid application development
		
Continuous integration
======================
Continuous integration is the practice of merging all developer working copies to a shared mainline several times a day. 

Prototyping
===========
Software prototyping is about creating prototypes, i.e. incomplete versions of the software program being developed.

Incremental Model 
=================
System development is broken down into many mini development projects
Partial systems are successively built to produce a final total system
Highest priority requirement is tackled first
Once the requirement is developed, requirement for that increment are frozen

waterfall model 
===============
The waterfall model is a breakdown of project activities into linear sequential phases, where each phase depends on the deliverables of the previous one and corresponds to a specialisation of tasks.

Rapid application development
==============================

Step 1. Define and finalize project requirements
	Step 2: Begin building prototypes
		Step 3: Gather user feedback
			Step 4: Test, test, test
				Step 5: Present your system
				
Agile development
=================

*******************

* Agile is the set of values and priciples

* How a team become agile : They make the decision based on the agile values and priciples

* The values and Principles have enough flexibility to allow teams in a wide variety of organisations to develope software in the way that work best for their particular situation
  while providing the direction to help the team continuously move toward their full potential.

*******************

		Items on Left more Important 			Than Intems on right
		============================			====================
		
		Individuals and Interaction				Process and Tools
		
		Working software						Comprehensive Documentation
		
		Customer Colobration					Contract Negotiation
		
		Responding to Change					Folowing a Plan
		
12 Principles of Agile
======================
1.  Our highest priority is to satisfy the customer through the early and continuous delevery of valuable software
2.  Welcome changes in the delevelopment even in the late stage.
3.  Deliver the working software frequently, from a couple of weeks to couple of months
4.  Business people and developers should work together daily to develop the project
5.  Give the projects to the motivated individuals. and help the to develop the job and beleive them
6.  Face to face conversation
7.  Working software is the primary measure of progress
8.  Agile process promote sustainable development. The sponsors, devlrs, users should be maintain a constant pace
9.  Continuous attention to technical excellence and good design enhances
10. Simplicity the art of maximizing the amount of work not done is essential
11. The best architechtures , requirements, designs emerge from self-organising teams
12. At regular intervels, the team reflects on how to become more effective, then turns and adjusts its behavior accordingly.

* Making decision based on the values and priciples that team has to follow

User Story

	Who
		What
			Want
			
TEST DRIVEN DEVELOPMENT (TDD) 
==============================

TEST DRIVEN DEVELOPMENT (TDD) approach first, the test is developed which specifies and validates what the code will do. In simple terms, test cases are created before code is written. The purpose of TDD is to make the code clearer, simple and bug-free.

step 1 : Add a test.
step 2 : Run all tests and see if any new test fails.
step 3 : Write some code.
step 4 : Run tests and Refactor code.
step 5 : Repeat.

Write a test for the next bit of functionality you want to add.
Write the functional code until the test passes.
Refactor both new and old code to make it well structured.

Three laws of TDD
=================
You are not allowed to write any production code unless it is to make a failing unit test pass.
You are not allowed to write any more of a unit test than is sufficient to fail; and compilation failures are failures.
You are not allowed to write any more production code than is sufficient to pass the one failing unit test.

XP - Extreme Programming
========================

XP is a light weight methodology for small to medium sited teams developing software in the face of vague or rapidly changing requirements.

Light Weight
============
Doesnt burdent to the developers. The process kept minimum.

Humanistic
==========
Centered around peaople - Developers and Customers are at the center of the Process

Discipline
==========
Its contains processes that we need to follow

Software Development
====================

* Developing like driving
* Mentality of sufficiency

Extreme Programming consist of 
	* Pair Programming
	* Code Review
	* Unit testing
	* Integration testing
	* Planning game
	* Courge
	* Respect
	
Planning
==========
User stories are written.
Release planning creates the release schedule.
Make frequent small releases.
The project is divided into iterations.
Iteration planning starts each iteration.

Managing
==========
Give the team a dedicated open work space.
Set a sustainable pace.
A stand up meeting starts each day.
The Project Velocity is measured.
Move people around.
Fix Extreme Programming when it breaks.

Designing
==========
Simplicity.
Choose a system metaphor.
Use CRC cards for design sessions.
Create spike solutions to reduce risk.
No functionality is added early.
Refactor whenever and wherever possible.

Coding
=======
The customer is always available.
Code must be written to agreed standards.
Code the unit test first.
All production code is pair programmed.
Only one pair integrates code at a time.
Integrate often.
Set up a dedicated integration computer.
Use collective ownership.

Testing
=======
All code must have unit tests.
All code must pass all unit tests before it can be released.
When a bug is found tests are created.
Acceptance tests are run often and the score is published.


RED, GREEN, REFACTOR
=====================
The red, green, refactor approach helps developers compartmentalize their focus into three phases:

Red — think about what you want to develop
Green — think about how to make your tests pass
Refactor — think about how to improve your existing implementation


Design Patterns
================
Creational Design Patterns:
===========================
	Singleton Pattern
	=================
	Singleton - Ensure that only one instance of a class is created and Provide a global access point to the object.
	When to Use , Common Usage , Example: Lazy Singleton in Java, Example: Early Singleton in Java

	Factory Pattern
	===============
	Factory(Simplified version of Factory Method) - Creates objects without exposing the instantiation logic to the client and Refers to the newly created object through a common interface.

	Factory Method 
	==============
	- Defines an interface for creating objects, but let subclasses to decide which class to instantiate and Refers to the newly created object through a common interface.

	Abstract Factory - 
	=================
	Offers the interface for creating a family of related objects, without explicitly specifying their classes.
	Example: Gui Look & Feel in Java
	Builder 
	=======
	- Defines an instance for creating an object but letting subclasses decide which class to instantiate and Allows a finer control over the construction process.
	Example: Text Converter in Java
	Prototype - 
	===========
	Specify the kinds of objects to create using a prototypical instance, and create new objects by copying this prototype.
	Object Pool
	============
	Object Pool - reuses and shares objects that are expensive to create..
	Sourcecode: Database Connection Pool in Java
