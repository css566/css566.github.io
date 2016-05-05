---
layout: post
title: Software Measurement and Metrics
---

## Overview
At the heart of software process standards are clear estimation processes and a well-defined metrics program.  Even more important than being able to meet the standards, managing your software by the numbers, rather than by the seat of your pants, enables you to have repeatable results and continuous improvement. Yes, there will be less excitement and less unpaid overtime, since you will not end up as often with the “shortest schedule I can’t absolutely prove I won’t make.” [1].

Software engineers need to be skilled in estimation and measurement, which means:

- Understanding the activities and risks involved in software development
- Predicting and controlling the activities
- Managing the risks
- Delivering reliably
- Managing proactively to avoid crises

Bottom line: You must be able to satisfy your customer and know what you will spend doing it.

To predict and control effectively you must be able to measure. To understand development progress, you must be able to measure. To understand and evaluate quality, you must be able to measure. Unfortunately, measurement, particularly in software, is not always easy. How do you predict how long it will take to build a system using tools and techniques you’ve never used before? Just envisioning the software that will be developed to meet a set of requirements may be difficult, let alone trying to determine the building blocks and how they will be mortared together. Many characteristics of the software seem difficult to measure. How do you measure quality or robustness? How do you measure the level of complexity? [1]

## What to Measure

There are many characteristics of software and software projects that can be measured, such as size, complexity, reliability, quality, adherence to process, and profitability. For any particular software project or organization, the specific software measurements program to be used will need to be defined.  
Fundamentally, to define an appropriate measurements program you need to answer the following questions:

- Who is the customer for the metrics?
- What are their goals with respect to the product, process, or resource under measurement?
- What metrics, when collected, will demonstrate whether or not the goal has been or is being met?

To define an aligned metrics program, it is critical to engage your “customer” as well as project/organizational staff who are knowledgeable in the object to be measured. Thus, identifying your customer and getting the affected stakeholders involved will be a common element no matter which approach is used. [1]

![enter image description here](https://github.com/css566/css566.github.io/blob/master/images/Software_Measurement_Non-Sequitur.jpg?raw=true)

> Example of Measurement Gone Awry [1]


----------


### The Goal Question Metric (GQM) Approach

The Goal Question Metric (GQM) approach, defined by Basili et al. [2], is a valuable, structured, and widely accepted method for answering the question of what to measure. GQM drives the definition of a metrics program from the top down:

 1. Identify the Goal for the product/process/resource. This is the goal that your metrics “customer” is trying to achieve.
 2. Determine the Question(s) that will characterize the way achievement of the goal is going to be assessed.
 3. Define the Metric(s) that will provide a quantitative answer to each question. Metrics can be objective (based solely on the object being measured) or subjective (based on the viewpoint taken as well as the object measured).

For example, let’s look at a software product delivery. The product/project manager may have the following goal for the product:

- Goal: Deliver a software product that meets the customer’s expectation for functionality.
One question that could help characterize the achievement of this goal would be:

- Question: How much does the software, as delivered to the customer, deviate from the customer requirements?
One metric that could be used to answer this question would be:

- Metric: Number of field software defects encountered. Typically, there will be a contractual agreement on what constitutes a defect, often based on software performance that deviates from mutually agreed upon requirements. The more specific the requirements, the more objective this metric becomes.

Another metric that could be used to address this question is:

- Metric: Customer satisfaction level as indicated on some form of survey. This is a subjective metric, based solely on the viewpoint of the customer.

This approach can be taken for any and all goals and stakeholders to define an aligned metrics program [1] (for entire sub-section).

### Decision Maker Model

Another method for selecting metrics is to focus on project decision making. The decision maker is the customer for the metric, with metrics produced to facilitate informed decision making. In this method, you need to determine what the needs of the decision maker are, recognizing that these will change over time [3]. This method is entirely consistent with the GQM method, with a focus on decisions that must be made. This concept is illustrated in the Figure below.

![enter image description here](https://github.com/css566/css566.github.io/blob/master/images/Software_Measurement-Decisions-Measures.jpg?raw=true)

> Decision maker model [1]


----------


Understanding the decisions that must be made will naturally lead to the project measures that must be put in place to support this decision making. 

- For example, a software project manager will need to make resource allocation decisions based on current status versus planned progress. To be able to make these decisions, he/she will need measures of both time and effort during the development life cycle. 
- A test manager will need to determine if the quality of the software is at a level acceptable for shipment to the customer. To be able to make this decision, he/she will need to have a measure of current quality of the software and perhaps a view of how that has changed over time.

With this method, look to the needs of the decision makers to define the metrics to be used. [1] (Entire section)

### Standards Driven Metrics

Both generic and industry-specific software engineering standards for collection and use of metrics are available. Some organizations use these to drive their metrics programs. For example, the Software Engineering Institute (SEI) software maturity model requires the measurement of system size, project time, level of effort, and software defects. SEI integrates these measures with the required processes in support of Project Management and Continuous Improvement. Laird and Brennan [cite] consider the SEI set, along with productivity, to be the minimal set for any organization. They define the minimal set to include:

- System size
- Project duration
- Effort
- Defects
- Productivity

Different industries may have their own standards for metrics, reliability, and safety. For example, in the telecommunications industry, the TL9000 standard defines a lengthy set of metrics that software suppliers must produce and make available to their customers and, in anonymous form, to the telecommunications industry. In the nuclear power industry, EIC 60880:1986-09 defines standards and metrics for “Software for Computers in Safety Systems in Nuclear Power Stations.” 

Under a standards-driven metrics approach, software managers should look for both industry and generic standards that are aligned with applicable business goals for an indication of metrics to be used [1] (Entire section).

### GQM + Mechanism (GQM2)

There is an important addition to all of the above approaches that must be considered. The mechanism for collecting the metrics data must be well understood and agreed to before implementing the program.  The GQM2 approach adds this mechanism to GQM.  The Mechanism This includes identifying who will be responsible for ensuring the collection and reporting of valid data, how frequently the data will be collected, how frequently the data will be reported, and what infrastructure (e.g., tools, staff resources) will be needed to collect and report the data. [1]

Failing to understand and gain agreement on this last “M” can lead to numerous failures of the metrics program [1]:

- Data is incomplete or invalid because no one has ensured that it is entered in a timely and correct manner.
- Data is “stale” and not useful for current decision making.
- Data is unavailable when needed.
- Project budgets are overrun due to the cost of the metrics program infrastructure.
- Project schedules are overrun due to unplanned staff time for data entry and validation.

###What to Measure is a Function of Time

One characteristic of any metrics program is that it is a function of time in three ways [1] (entire section): 

- First, what to measure certainly varies based on the current position in the software development and software product lifecycles. For example, code inspection metrics are collected and monitored during the code development time in the lifecycle. During the testing phase, development time to deliver a fix may be what that same decision maker needs to know. Reliability of the software may need to be measured in the early stages of product delivery and deployment, while cost to maintain might be the area of interest when a product is near the end of its life.

- Second, business needs change over time and the metrics program must change to remain in alignment. For example, if customer surveys show dissatisfaction with product reliability, a system availability metric may need to be created and monitored. If competitors are beating a company’s products to market with similar functionality, the company may need to establish development process measures that will allow it to focus on the most time consuming areas in order to drive improvement.

- Third, metrics, especially when used as a factor in recognition and/or compensation, can lose their efficacy over time. Focus can become fixated on the metric itself and how to “manage the metric” rather than on the ultimate goal the project is trying to achieve. This may necessitate selecting a different metric that supports the goal or changing the way the existing metric is calculated.

## Measurement Fundamentals

In software, the issue is that so many things that we want to measure seem so “unmeasurable.” How do you measure the complexity of a program? What does complexity even mean? How do you measure productivity? If someone can write 100 lines of code in two hours to program a function, but the software has five bugs in it, is it reasonable productivity? And what is that productivity? Better yet, if someone else can program the same function in one line of code, in one hour, what is their productivity? Whose productivity is better? [1]

### Measurement Models

The key to “making the unmeasurable measurable” is models. A model is an abstraction, which strips away unnecessary details and views an entity or concept from a particular perspective. Models allow us to focus on the important parts, ignore those that are irrelevant, and hypothesize and reason about an entity. Models make measurement possible.

We must have models of whatever we want to measure. For example, say we want to know how much of the total system development effort is testing. To determine that, we need a model of both the overall development process and the testing process, which specifies when testing starts and when it ends, what is included, and the number of people involved. If our model starts with unit test by the programmer, it is a different model and will give different results than one that includes only system test.
There are three types of models you can use—text, diagrammatic, and algorithmic—that is, words, pictures, and numbers. [1]

#### Text Models

Text models tend to be the least effective, but the most common. It is difficult to adequately describe complex situations and dynamics using just words.

Here is a text model for software development [4]:

- Effort: The time required to develop a product, expressed as increments of staff development time (e.g., staff months/hours). In general, effort is a function of size and results in cost.
- Features: The requirements of the product to be developed.
- Size: The magnitude of the product to be developed. In general, size is a function of features.
- Defects: The incompleteness of the product. In general, defects are a function of size and schedule.
- Schedule: The total development time; completion times for principal milestones. In general, schedule is a function of effort and resources.
- Resources: The number of developers applied to the product development.

This text model has advantages and disadvantages. Each item is clearly defined and easy to understand, but the relationships between items may be difficult to visualize. But notice that this text model describes software development in such a way that we can discuss it, measure it, and predict it: if the size changes, the number of defects will change. This text model gives structure to the abstract concept of “software development.”
We frequently use metaphors and heuristics to provide insight into the software development environment dynamics. These tend to work well, due to the breadth of meaning we associate with metaphors. The downside is that these models can limit, as all models, our creative thinking as they structure it [4]. Some examples of text model metaphors for software development are:

- The Wild, Wild West
- Agile Development (both a metaphor and a name)
- Death March
- Software Factory

Notice how each metaphor evokes a different mental image and response. You probably can envision the environment, the types of people, and processes from just the few words.
Some examples of heuristics models are:

- “Adding additional staff to late projects makes them later” F.P. Brooks [5]
- “Prototyping cuts the work to produce a system by 40%” L. Bernstein

#### Diagrammatic Models

Diagrammatic models can be extremely powerful. There are many techniques for diagrammatic modeling, two of which are Weinberg’s [6] and Senge’s [7]. They allow you to model the entities, the relationships between them, and their dynamics. Use one of the formal diagram modeling techniques if you will be doing extensive modeling. Otherwise, simplistic flow diagrams (annotated circles and arrows) should suffice. The Figure below is a simple diagrammatic model of software development, which matches the text model above.

![enter image description here](https://github.com/css566/css566.github.io/blob/master/images/Software_Measurement-Diagrammatic-model.jpg?raw=true)

> Diagrammatic model of software development.


----------


#### Algorithmic Models

Algorithmic models are also called parametric models. In the right situations, they can be extremely powerful, as they can clearly describe the relationship between entities. Some examples of algorithmic models for software development are:

- Effort = Schedule * Resource.
- % Defects Found During One Test Cycle = 30% of defects remaining in product.
- Effort = A * (Size-of-ProgramB) + C, where A, B, and C are all empirically derived constants.

#### The Pantometric Paradigm: How to Measure Anything

You may be concerned about how to create a model. The Pantometric Paradigm [8] is a simple method to produce a purely visual and quantitative model of anything within the material world. You can use it to create an initial model that can evolve to meet your needs. The simple process is:

 1. Reduce what you are trying to model to the minimum required by its definition. Strip away all extraneous information.
 2. Visualize it on a piece of paper or in your head.
 3. Divide it in fact or in your imagination into equal parts.
 4. Then measure it (e.g., count the parts).

Now you have a quantitative representation (model) of your subject which matches your definition. You can now manipulate it, reason about it, experiment with it, and evolve it.

### Meta-Model for Metrics

Another method for creating models that takes abstract concepts to empirical measurements is from Kan [9], and is depicted below. You begin with an abstract concept, define it, create an operational definition, and then specify a real-world measurement. 

![enter image description here](https://github.com/css566/css566.github.io/blob/master/images/Software_measurement_meta-model_1.jpg?raw=true) 

> Meta-model for metrics [1]


----------


An example of this methodology, using the same response time example, is shown below.

![enter image description here](https://github.com/css566/css566.github.io/blob/master/images/Software_measurement_meta-model_2.jpg?raw=true)

> Example using meta-model for response time [1].


----------


There are attributes of software that we can define and measure directly, such as the number of modules in a system or the number of people assigned to a project. These are called “direct measures.” However, many of the attributes we want to measure are calculated, such as number of defects per thousand lines of code (KLOC) or average number of lines of code (LOC) produced per week. These are called “indirect measures.”

### References:

[1] L. Laird and C. Brennan, Software Measurement and Estimation: A Practical Approach, IEEE Press 2006 Citation

[2] V.R. Basili, G. Caldiera, H.D. Rombach, and R. van Solingen, “Goal Question Metric (GQM) approach,” Encyclopedia of Software Engineering, John Wiley & Sons, Hoboken, New Jersey, 2002.

[3] J. McGary, D. Card, C. Jones, B. Layman, W. Clark, J. Dean, and F. Hall. Practical Software Measurement, Objective Information for Decision Makers, Addison-Wesley, Boston, 2002.

[4] D. Pitts, Why is software measurement hard? 1999.  http://www.ifpug.org/Conference%20Proceedings/IFPUG-1999/IFPUG1999-12-Pitts-Why_Is_Measurement_Hard.pdf Accessed May 5, 2016.

[5] F.P. Brooks, The *Mythical Man Mont*h, Addison-Wesley, Reading, Mass., 1974.

[6] G. Weinberg, Quality Software Management, Volume 2 First –Order Measurement, Dorset House Publishing, New York 1993

[7] P. Senge, The Fifth Discipline, Doubleday, New York, 1990

[8] A.W. Crosby, The Measure of Reality, Cambridge University Press, Cambridge, United Kingdom, 1997.

[9] S. Kan, Metrics and Models in Software Quality Engineering, 2nd ed., Addison-Wesley, Boston, 2003.

[10] R.S. Kaplan and D.P. Norton, “The balanced scorecard—measures that drive performance,” The Harvard Business Review, 1992.
