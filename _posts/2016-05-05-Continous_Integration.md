---
layout: post
title: Continuous Improvement
---

![CI](https://t1.ftcdn.net/jpg/00/86/02/76/500_F_86027652_ap6Gqn0D7yqUlqxsxqxK0mxtEngAWa2x.jpg)

> Continous Improvement

> [Source](https://t1.ftcdn.net/jpg/00/86/02/76/500_F_86027652_ap6Gqn0D7yqUlqxsxqxK0mxtEngAWa2x.jpg)

## Kaizen
Kaizen (Continuous Improvement) is a strategy where employees at all levels of a company work together proactively to achieve regular, incremental improvements to the manufacturing process. In a sense, it combines the collective talents within a company to create a powerful engine for improvement.

![kaizen](https://www.vocoli.com/media/18328/kaizen-teian.png)

> Kaizen

[Source](https://www.vocoli.com/media/18328/kaizen-teian.png)

## Practices
- Maintain a single source repository
- Automate the build
- Make your build self-testing
- Every commit should build on an integration machine
- Keep the build fast
- Fix Broken Builds Immediately
- Test in a clone of the production environment
- Make it easy for anyone to get the latest executable
- Everyone can see what’s happening
- Automate deployment

![CI cycle](https://pbs.twimg.com/media/CcGRYS6UsAAccyU.jpg)

> Continous Integration Cycle

[source](https://pbs.twimg.com/media/CcGRYS6UsAAccyU.jpg)

## Benefits
- Say goodbye to long and tense integrations
- Increase visibility which enables greater communication
- Catch issues fast and nip them in the bud
- Spend less time debugging and more time adding features
- Proceed in the confidence you’re building on a solid foundation
- Stop waiting to find out if your code’s going to work
- Reduce integration problems allowing you to deliver software more rapidly

## How to do it
- Developers check out code into their private workspaces.
- When done, commit the changes to the repository.
The CI server monitors the repository and checks out changes when they occur.
- The CI server builds the system and runs unit and integration tests.
- The CI server releases deployable artefacts for testing.
- The CI server assigns a build label to the version of the code it just built.
- The CI server informs the team of the successful build.
- If the build or tests fail, the CI server alerts the team.
- The team fix the issue at the earliest opportunity.
- Continue to continually integrate and test throughout the project.

## Books
[Continuous Integration: Improving Software Quality and Reducing Risk 1st Edition](http://www.amazon.com/gp/product/0321336380)

> For any software developer who has spent days in “integration hell,” cobbling together myriad software components, Continuous Integration: Improving Software Quality and Reducing Risk illustrates how to transform integration from a necessary evil into an everyday part of the development process. The key, as the authors show, is to integrate regularly and often using continuous integration (CI) practices and techniques.


[Continuous Delivery: Reliable Software Releases through Build, Test, and Deployment Automation (Addison-Wesley Signature Series (Fowler)) 1st Edition](http://www.amazon.com/gp/product/0321601912)

> Getting software released to users is often a painful, risky, and time-consuming process.
This groundbreaking new book sets out the principles and technical practices that enable
rapid, incremental delivery of high quality, valuable new functionality to users. Through
automation of the build, deployment, and testing process, and improved collaboration between
developers, testers, and operations, delivery teams can get changes released in a matter of hours—
sometimes even minutes–no matter what the size of a project or the complexity of its code base.

## Videos
[Continous Delivery](https://yow.eventer.com/events/1004/talks/1062)

> Businesses rely on getting valuable new software into the hands of usersas fast as possible, while making sure that they keep their production environments stable. Continuous Delivery is a revolutionary and scalableagile methodology that enables any team, including teams within enterprise IT organizations, to achieve rapid, reliable releases throughbetter collaboration between developers, testers, DBAs and operations, and automation of the build, deploy, test and release process. We'll start by discussing the value of CD to the business, inspired by the lean startup movement. We'll then present the principles and practices involved in continuous delivery, including value stream mapping, the deployment pipeline, acceptance test driven development, zero-downtime releases, and incremental development. We'll cover how CD is enabled by an ecosystem including Devops, cloud computing, agile testing, and continuous deployment. Finally we'll talk about how continuous delivery can co-exist with ITIL and compliance in an enterprise environment.

[PCI-DSS and continuous deployment at Etsy](https://www.thoughtworks.com/insights/blog/pci-dss-and-continuous-deployment-etsy)

>  Michael Rembetsy is the Director of Engineering and Operations at Etsy, which manages to be PCI-DSS compliant while practicing continuous deployment. In this short interview, he describes how they do it.