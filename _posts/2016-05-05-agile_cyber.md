---
layout: post
title: Agile Software Management Economic Aspects
---


#Agile Software Management Cyber Aspects
##CSS 566: Sprint #2
###Overview

In order to further develop the content for the Software Management (SM) course, we are iteratively creating in CSS 566 a part of the course, known as the Product. Each of the three teams is creating a Unit for Sprint 1 & 2 that is focused on a Physical aspect of SM, a Social aspect of SM, an Economic aspect of SM, or a Cyber aspect of SM. Team “It’s a Secret” is focusing on the Cyber aspect for its Unit, as defined in this document. 

###Topic

This Unit focuses on the cyber aspects of Agile Software Management, as the general topic of Economics in Software Engineering is broad enough for its own course. Moving beyond Agile and into DevOps requires testers and project managers to take on constant collaboration, continuous testing and more. This Unit focuses on the cyber aspects of Software process in Agile Software Management. 

###Principles

 - DevOps - blending of tasks performed by a company's application development and systems operations teams [6]
	 - Continual testing is the norm
	 - Testers are part of development and part of operations
	 - Analytics to assess status of code after each build
 - Software project collaboration [7]
	 - Tools to facilitate task-oriented collaboration by allowing users to pull relevant information from multiple applications into a dashboard
 - Continuous Integration - for scaling agile development [5]
	 - Continuous Integration always keeps a working and stable system
	 - Stable system by working in small batches and short cycles
	 - Test automation of all tests and manual tests when needed
 - Architecture and Design - modeling related to their upcoming goals or to the overall system architecture or both [5]
	 - Low-fidelity UI modeling with sticky notes or in prototyping tools
	 - Algorithm modeling with UML activity diagrams - CASE tools
	 - Object-oriented software design modeling usually sketched in UML-ish notation, and database modeling 


###Theories and Practices

Although one of the core principles of Agile software management is to emphasize individuals and interactions over processes and tools,  managing a complex project efficiently relies on using a robust set of tools for management, tracking and collaboration.
Project management tools can help in the following steps in Agile Software Management:

 - Backlog Management  
	 - Tools can be used to define, prioritize and decompose work for the project.
 - Scrum Tools  
	 - Can be used for capacity planning and to assign work 
	 - Monitor progress throughout the sprint with real-time burndown charts
 - Kanban tools 
	 - Many Agile SM tools have a virtual Kanban board that can be used to monitor workflow 
	 - And set work-in-progress limits by dragging and dropping cards.
 - Dashboards 
	 - Dashboards in SM tools can be used to provide visibility to all the stakeholders
 - Advancing DevOps through Release Management [3]  
	 - For example, Visual Studio online provides Release Management features to orchestrate deployment from development to production. 
	 - If a build causes a serious regression, it is easy to roll back the deployment to a previous build.
 - Mitigating Risk with Automated Builds [3]  
	 - Build automation and gated check-ins prevent breaking changes from being checked in. 
	 - Test suites can also be run automatically and check-ins can be gated on that to reduce risk of regressions.
	 - Open source unit test frameworks such as JUnit for Java and CppUTest for C/C++ [5]
 - Use of Virtualization in automated testing [5]
	 - Speeds up the tests and keep the investment in hardware low
	 - Use of virtual machines such as VirtualBox or VMWare
	 - Use of linux virtual containers such as Docker
 - Gaining Insights from Production Applications [3] - 
	 - Tools like Visual Studio Online Application insights can monitor performance and usage of applications and services hosted in the cloud. 
	 - This can give insight into how users are interacting with the applications and this can be used for focusing resources on experiences that delight users.


###Case Study:

**Content Marketing Company Streamlines Development ALM tools [4].**

**Business Problem** 
PaperShare is a company that develops software services for digital content marketing and lead generation. The company earlier used traditional defect management systems to track bugs and work items and lacked a holistic solution to break down stories into tasks, communicate tasks across team members, and give stakeholders views into the status of the tasks. The tools were not built for agile software development, and backlog management became a hard problem. Eventually, it became a challenge to prioritize tasks and accurately schedule work for each sprint. This uncertainty in the schedule made it difficult to communicate feature dates to customers. Papershare wanted to bring more discipline and traceability to its development processes with an ALM (Application Lifecycle Management) solution suited for agile software development.

**Solution**
Papershare upgraded to Microsoft Visual Studio Online for ALM. Moving to a cloud-based ALM solution has made sprint planning much easier for the distributed development team. The entire team uses the toolset as they break down a story into tasks and estimate the cost of each task. Using burndown charts, they can see their progress during the sprint and this process helped improve planning over time.

Quality assurance process improved as well. Code reviews were managed by the ALM solution and could be accessed securely thru the web. Once code is ready for check-in, a gated check-in process runs unit and scenario tests and submits the code only after a successful test pass. This helped prevent regressions and the simplicity of the toolset helped improve code velocity. The solution also ensures the builds are staged for pre-production environment periodically for internal testing. The ALM suite also tracks bugs and work items and helps map code changes to defects and vice-versa, improving traceability. Virtual Kanban boards made daily Scrum meetings a breeze.

**Benefits**
*Disciplined Sprints* - The company is deploying new production code every two weeks. The ALM tools helped them manage development rhythm and made it easier to prioritize tasks and manage backlog.

*Traceability* - The solution enabled the teams to track the progress for each task corresponding to every story, along with integrated code reviews and check-ins. If a bug is found in production, it was easy to to trace it back to the code and see what was changed and why, along with who made the change and when.

*Productivity* - With this solution, the development team no longer had to use standalone applications and co-ordinate between them. Developers and product managers were able to do everything they need without leaving the solution. The ALM solution also made productivity measurable. By looking at historic performance,  teams were able to better forecast future stories sprints and releases, resulting in better estimation and planning.

As a result of the Agile ALM solution, PaperShare was able to pivot its Software Management practices to get more features into the product faster and with better quality.

###References:

1. http://searchsoftwarequality.techtarget.com/tip/Tips-for-effective-software-project-collaboration
2. http://searchcontentmanagement.techtarget.com/news/4500251063/Microsoft-unveils-Project-GigJam-collaboration-tool
3. https://customers.microsoft.com/Pages/CustomerStory.aspx?recid=1029
4. https://customers.microsoft.com/Pages/CustomerStory.aspx?recid=1613
5. https://less.works/less/technical-excellence/
6. http://searchcloudcomputing.techtarget.com/definition/DevOps
7. http://searchcontentmanagement.techtarget.com/news/4500251063/Microsoft-unveils-Project-GigJam-collaboration-tool

