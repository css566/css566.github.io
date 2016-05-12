---
layout: post
title: Cyber Aspects of LeSS
---
 <a name="content"></a>
 
## Trends, Concepts, Patterns, Issues

---



### [LEAN THINKING](#leanthinking)
  * Concepts
  * Patterns

### [TECHNICAL EXCELLENCE](#technicalexcellence)

* [**Architecture & Design**](#architecture-design)
  * Concepts
  * Patterns
  * Issues

* [**Test Driven Development**](#tdd)
  * Patterns
  * Concepts
  * Issues
  
* [**Specification by Example or Acceptance test-driven development (A-TDD)**](#byexample)
  * Patterns

* [**Test Automation**](#testautomation)
  * Concepts
  * Patterns

* [**Continuous Integration**](#continuous-integration)
  * Patterns
  * Concepts
  * Issues

* [**Acceptance Testing**](#acceptancetesting)
  * Concepts  

* [**Unit Testing**](#unittesting)
  * Concepts
  * Patterns

*  [**Product Backlog**](#productbacklog)
  * Concepts
  * Patterns

* [**Product Backlog Refinement**](#pbrefinement)
  * Patterns

* [**Coordination & Integration**](#coordination-integration)
  * Patterns

## <a name="leanthinking">LEAN THINKING</a>

### Concepts

- % Utilization of Resources

- Value-to-waste ratio

- Cycle times

- Value of information - also, create useful knowledge

- Data Driven - experiment, collect data, adapt based on data

### Patterns

- Focus on early testing and feedback

- Focus on large-scale test automation

- Focus on continuous integration

[Back to top](#content)

## <a name="technicalexcellence">TECHNICAL EXCELLENCE</a>

## <a name="architecture-design">Architecture & Design</a>

### Concepts

- Source code is the real design

- Risk-driven development

- Agility through low coupling 

### Patterns

- Very early, develop a walking skeleton with tracer code

- Incrementally build ‘vertical’ architectural slices of customer-centric features

- Do customer-centric features with major architectural impact first

- HTML-ize and hyperlink your entire source code, daily

- Use lots of stubs, plus dependency injection

- Use architectural and design patterns

- Wrap calls to remote components with proxies or adapters


### Issues

- Intended architecture (speculated, wished for) versus actual architecture

- Architecture is performed once near the start, often in documents

- Architecture overlaps with requirements analysis

- Start with indirect interaction between major components, then replace as needed

- Message-oriented middleware (MOM) can be slow, may need to change to SOAP or Java RMI for remote clients.

[Back to top](#content)

## <a name="tdd">Test Driven Development (TDD)</a>

### Patterns

Short cycles of:
 1. Write one test.
 2. Implement just enough code to make it pass.
 3. Refactor the code so it is clean.


### Concepts

- Short

- Rhythmic

- Incremental

- Design-focused

- Disciplined

- Encourages lower coupling and simple, flexible configuration

### Issues

When a developer creates a new component (such as a class) with TDD, or refactors a legacy component to be unit-testable, they must break the dependencies of that component so that it is testable in isolation

[Back to top](#content)

## <a name="byexample"> Specification by Example or Acceptance test-driven development (A-TDD) </a>

### Patterns

- Condense workflow in business rules

- Expressing business rules in tables makes them more comprehensible

- Use an A-TDD Tool

[Back to top](#content)

## <a name="testautomation"> Test Automation </a>

### Concepts

- Scripted testing - automated

- Exploratory testing - not automated

### Patterns

- Create maintainable tests
	- remove duplication in and between tests
	- delete tests when not adding value
	- do not test through the UI
	- run tests frequently

- Treat non-functionals the same as functionals

- Continuously run long-running tests

- Use virtualization or containers

- Avoid using commercial test tools

[Back to top](#content)

## <a name="continuous-integration">Continuous Integration</a>

### Concepts

- Shared Code

- Working in small batches--iteratively.

### Patterns

- Integrating at least daily

- supported by a CI system

- with lots of automated tests

- build and test need to be fully automated

- Multi-stage CI:

	- a developer build
	- component or feature focus
	- automatic or manual promotion
	- event or time triggers
	- the number of stages

### Issues

Many large products have legacy code without automated tests. Developers need to add automated tests–which is a lot of work.

Probability of breaking the build increases with more people checking in code. Address by:

- build incrementally
- deploy incrementally
- manage dependencies
- refactor tests

Increase in code size leads to a slower build and thus a slower CI feedback loop. Upgrading tools to the latest version or replacing a slow tool with a fast one speeds up the build a lot.

[Back to top](#content)

## <a name="acceptancetesting">Acceptance Testing</a>

### Concepts

- UAT is a subset of acceptance tests

[Back to top](#content)

## <a name="unittesting">Unit Testing</a>

### Concepts

- Unit testing Facilitates changes

- Unit testing Simplifies integration

- Unit testing Provides documentation

- Unit testing Serves as design tool

- Total cost of ownership is low

- Tests Internal Quality vs. External Quality

- Feedback is precise and actionable

### Patterns

- unit test should be small and test only limited piece of code functionality

- AAA: Arrange, Act and Assert

- Behaviour Driven Development (BDD)

[Back to top](#content)

## <a name="productbacklog">Product Backlog</a>

### Concepts

- Multiple teams building a single product work from a single Product Backlog.

- Avoid unnecessary and costly complication by using the simplest tools possible for managing the Product Backlog.

### Patterns

A good Product Backlog must:

- have estimates for all items,
- have finer grained items at the top and coarser grained items further down, and
- be prioritized.

[Back to top](#content)

## <a name="pbrefinement">Product Backlog Refinement</a>

### Patterns

- split big items

- do very lightweight item analysis for basic understanding

- estimate items

- identify strongly-related items that suggest shared work, common work, or coordination

[Back to top](#content)

## <a name="coordination-integration">Coordination & Integration</a>

### Patterns

Communicate in Code - use continuous integration to keep track of what others are doing. When you synchronize, look at the changes others have made.
