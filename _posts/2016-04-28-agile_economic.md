---
layout: post
title: Agile Software Management Economic Aspects
---

Overview
-------------
In order to further develop the content for the Software Management (SM) course, we are iteratively creating in CSS 566 a part of the course, known as the Product. Each of the three teams is creating a Unit for Sprint 1 that is focused on a Physical aspect of SM, a Social aspect of SM, or an Economic aspect of SM. Team It’s a Secret is focusing on the Economic aspect for its Unit, as defined in this document. 


Much of the economically-focused angle of this Unit is derived from the Manifesto for Agile Software Management:


>“We are uncovering better ways of developing software by doing it and helping others do it. Through this work we have come to value:

>*Individuals and interactions* over processes and tools

>*Working software* over comprehensive documentation

>*Customer collaboration* over contract negotiation

>*Responding to change* over following a plan

>That is, while there is value in the items on the right, we value the items on the left more.” [2]

This Unit focuses on the economics aspects of Agile Software Management vs. Waterfall Software Management, as the general topic of Economics in Software Engineering is broad enough for its own course. In particular, since Agile SM is the focus of the Product and it is assumed that “Waterfall is dead” [class discussion with Professor Socha, CSS 566, Spring 2016], many of the points will be presenting advantages of Agile development over Waterfall.

Principles
-------------

- Working software as a minimum shippable product
  - Working software that is continuously delivered creates visibility into the process and helps eliminate wasted time and resources (i.e. money) [1]
- Responding to Change
  - “If we built the wrong thing, we can stop wasting money on that path.” [3]
  - Risk is reduced because business is more able to rapidly respond to change and adapt to changing competitive and technological landscape [1]
- Customer collaboration [2]
  - Customers and business gets better product in the end with Agile because their needs are addressed continually. Happier customers = healthier business finances
  - Customer collaboration creates transparency and trust with them, resulting in evangelists for the business/software and more demand for your software [3]
- People and interactions over processes and tools
  - Agile prefers small, cross-org teams over monolithic large teams, leading to faster decisions and mitigation of risks of bad decisions. [3]
    - This has an indirect financial impact that ties in with less wasted resources
    - Focus on people, both internal and external (employees and customers), results in many social benefits such as sense of ownership, flexibility in approach, dynamic adaptability, and trust with customers. Happier people = better product = happier customers = better business value

Practices
-------------

- Build continual planning and customer feedback into the process
   - Value is maximized throughout the development process [1]
   - “As a result of this iterative planning and feedback loop, teams are able to continuously align the delivered software with desired business needs, easily adapting to changing requirements throughout the process.” [1]
- Early and frequent delivery of value to customers
   - Agile development “accelerates the delivery of initial business value” [1]
     - This can be empirically measured, such as the in-class penny exercise that proved that iterative small batches results in faster delivery of value to the customer
  -  Customers will reduce the value they place on something if they have to wait too long, so early delivery is better [4]
  -  Early delivery means early money to use for other business needs and investments [3]
  -  Continual cash flow is healthier for the business than waiting for money at the end of a project [3]
- Iterative development
   - Ideas, concepts, and software features depreciate over time and have a “freshness window” before people place no value in them, so Agile development works within that 1-4 week timeframe to stay on top of customer needs and market demands [4
   - Iterative software product produces less value more frequently and is able to achieve higher overall value before depreciating revenue-wise [4]
   - Risk is “reset” every iteration due to iterative reevaluation of product [4]
   - Bug cost is reduced because they are continually tested and squashed instead of looked at far after the code is written [4]

<img src="https://raw.githubusercontent.com/css566/css566.github.io/master/images/agile_development_value_proposition.jpg" alt="Agile Development Value Proposition" width="400" height="400" /> 

Figure 1. Charts showing value proposition of Agile Development (red) vs. Traditional Development (gray). Source: VersionOne Enterprise Agile Solutions [1]

Theories
-------------
- Theory of constraints - “The chain is no stronger than its weakest link” [5]
   - Limiting amount of work that causes constraint or bottleneck
   - Diverting work away from the bottleneck
   - Increasing limitation of bottleneck by buying systems or hiring people
- Use of agile methodology to reduce cost of failure [5]
   - Faster feedback from stakeholders
   - Increasing flow of information within participating entities in a scrum
   - Decreasing the risk of one person failing by reducing number of dependencies on that person and distributing work equally amongst everyone
   - Focusing more on simplicity and reducing complication
- Importance of refactoring in agile [6]
   - More cost is incurred for adding features than the business benefits of adding these features if software system becomes dysfunctional and complicated
   - Refactoring is safest and cheapest when done in many small chunks
   - Use of business requests as catalysts for refactoring rather than call from technical teams
   - Team cohesion in terms of communication and collaboration in regards to which tools, techniques, and practices to use in refactoring
   - Team’s openness and honesty with all stakeholders about the cost of refactoring


<img src="https://raw.githubusercontent.com/css566/css566.github.io/master/images/SM_Unit_Economic_CaseStudy_1.jpg" alt="Reducing complexity and cost by refactoring" width="400" height="400" />

Figure 2. Diagram illustrating how refactoring reduces complexity and costs in agile software development. Source: Richard Fridrich [5]

 - Shorter feedback loops [7]
   - In agile, risks are cut down because of short releases in contrary to multi-year waterfall projects. Hence, feedback reduced to a smaller period
   - Comparison of the opportunity cost of agile and waterfall results in identifying waste of money and missing opportunity of working on more profitable projects in waterfall
   - User satisfaction has value too and not just return on investment in the form of mone

Case Studies
-------------
1) **"Mugshot.com" Website**

Case-study that shows how agile outperforms traditional techniques - by Chad Albrecht of Centare [4]
In this video (cited in references [4]), Chad has demonstrated a side-by-side cost model of an Agile vs. Traditional project. This case study is about creating a simple website, “Mugshot.com”. This social network site allows users to connect with family and friends. The major requirement is the website must be up and running ASAP. 

Some principles that they are going to use are:

- Bugs cost more the longer we wait
- Requirements change
- Some requirements are wrong
- Software depreciates
- We can choose when to stop developing

<img src="https://raw.githubusercontent.com/css566/css566.github.io/master/images/SM_Unit_Economic_CaseStudy_2.jpg" alt="Team structure and budget planning for Mugshot website" width="600" />

Figure 3. Team structure and budget planning for Mugshot website. Source: [4]


Figure 3 describes the structure of the team that is going to work on developing the website.

They have taken a team of 6 developers who will be working on developing the website. And they are going to include everybody on that team. They have four software engineers, a DBA and a QA. Each of them cost 2000/week. Total comes out to be $12000/week. There are 120 requirements to start with, given a requirement stack. Almost 20% of requirements are invalid. And they are getting approximately two changes a week. Each developer is putting four bugs per day in the code.  The longer the bug sticks around, the more it costs to fix. For the first 7 days, it takes 15 minutes. For first 30 days, it takes 30 minutes. Thereafter, they are gonna take 90 minutes to fix. The purpose of this is to model some of the things that we see in industry and try to compare short-cycle vs long-cycle that is, agile practices  vs more traditional long cycle practices. 

![enter image description here](https://raw.githubusercontent.com/css566/css566.github.io/master/images/SM_Unit_Economic_CaseStudy_3.jpg)

Figure 4. Traditional Approach - Cost Summary. Source of image: [4]


What this comes down when you plug all these numbers in is, its gonna cost them about almost half a million dollars to develop in a traditional sense (Refer figure 2), with discovery and estimation, implementation, fixing bugs. It is interesting to see that, the bug fixing phase cost them the most. Almost $330000 just to fix the bugs and stabilize for a total cost of half a million dollars.

![enter image description here](https://raw.githubusercontent.com/css566/css566.github.io/master/images/SM_Unit_Economic_CaseStudy_4.jpg)
Figure 5: Agile Approach - Cost Summary. Source: [4]


Figure 3 shows cost summary of agile approach. In agile approach, they ran 20 weeks, that is half the time as traditional approach. And it only cost them $240,000 from a cost standpoint. Moreover, they were keeping up with utility, they were matching utility, they were keeping features fresh, they were releasing more often, and they were adjusting to the two requirements that were changing every week on an on-going basis. 

![enter image description here](https://raw.githubusercontent.com/css566/css566.github.io/master/images/SM_Unit_Economic_CaseStudy_5.jpg)
Figure 6. Revenue Comparison of Agile vs. Traditioanl development for Mugshot website case study. Source: [4]


From figure 4,  by looking at gross revenue from forecasting standpoint, it looked like they are going to make a lot of money in a traditional sense. But as we get through, all the waste generated costed a lot in traditional approach. And it turns out that our revenue less depreciation is significant on the agile approach.   

![enter image description here](https://raw.githubusercontent.com/css566/css566.github.io/master/images/SM_Unit_Economic_CaseStudy_6.jpg)
Figure 7. Overall Comparison. Source: [4]


Overall comparison is shown in figure 5. They generated $87000 in waste in traditional sense and the net income if compared shows what economic impact agile is capable of producing. Conclusion is it can range anywhere from 2:1 to 10:1 improvement in agile.

2) **SAFe [8]**

This case study is about how SAFe applies lean-agile principles to give a broader economic view and to highlight key role economics plays in successful solution development. It talks about decentralizing decision making enabled by team’s knowledge on fundamental economic drivers for the solution. In particular, decision-making can happen in agreed-to financial context within the team. 

![enter image description here](https://raw.githubusercontent.com/css566/css566.github.io/master/images/SM_Unit_Economic_CaseStudy_7.jpg)
Figure 8. SAFe constructs for economic decision-making. Source: [8]


Figure 8 illustrates how economic framework decision rules are embedded in SAFe. The components are as following:

- Lean agile budgeting: This is the very first decision and kind of an important one, as lean-agile enterprise moves from project-based cost-center accounting to a more streamlined budget process. In particular, cost for each program increment is largely fixed and scope is varied as necessary to stay within the PI budget.
- Epic funding and governance: Allocating funds to the value streams is all well and good, but what happens when there are substantial concerns such as significant local investment concerns? The empowerment of funding requires responsibility to communicate any investments that are beyond routine. 
- Decentralize economic decision-making: With these elements of the framework in place, enterprise empowers people relevant context and knowledge to make content decisions at each level of the framework.
- Job sequencing based on cost of delay: Every significant program has a host of new backlog features and capabilities just waiting to be implemented in order to increase efficacy of the solution. But SAFe is a flow-based system and flow-based system economics are optimized by job-sequencing rather than by theoretical job ROI. Picking the right next job is where the greatest benefit lies.

References

1. The Benefits of Agile Software Development: https://www.versionone.com/agile-101/agile-software-development-benefits/
2. Agile Manifesto: http://www.agilemanifesto.org/
3. Agile Economics: Supply and Demand http://www.gilzilberfeld.com/2016/04/agile-economics-supply-and-demand.html
4. Agile Economics: https://channel9.msdn.com/Events/ALM-Summit/ALM-Summit-3/Agile-Economics
5. http://agileprague.com/the-economics-of-agile-software-development.htm
6. http://www.agileadvice.com/category/theoryofagile/
7. http://www.gilzilberfeld.com/2016/04/agile-economics-early-and-often.html
8. http://www.scaledagileframework.com/economic-framework/

Related Links

1. http://agility.iqbusiness.net/thought-leadership
2. https://www.youtube.com/watch?v=pLeSvduRPrQ
