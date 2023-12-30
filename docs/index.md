# Kyle Garver
*I have lots of ideas; they just can't all be bangers*

![Image title](./assets/me.webp){ align=left width="300" }

## Hi There!

I'm Kyle and what really butters my buns finding and building solutions through automation to help others focus on things they care about. I'm passionate about empowering others and ensuing that these solutions are accessible. I like to work in small increments and get feedback early.  I'm not afraid to try something and throw it out if it isn't the right solution.  They can't all be bangers after all.

## What I believe

Mainly bouncing around a Corporate IT for the last 9 years, contributing to different projects as needed. Some of the them are listed below. 

### Developer Accessibility
For each unique project, there is a unique team of people.  Each person bringing their own experiences and skill set. I have worked with interns only 2 years into a degree and grey beards who were there at the beginning. In the following project I've implemented several different strategies and landed on a few core bits I aim for. 

#### Pit of success mindset
When design solutions or tools, aim to make doing the right thing the easiest option.  

#### Time to hitting the first breakpoint
A developers time is precious and, as a person who struggles to focus at times, tenuous. I want me and my developers to be able start digging into a problem and getting feedback as soon as possible. 

#### Empower everyone to be a developer

#### Right tool for the job

## Projects
TODO: These need to be boiled down. 
- What was the key points, things you did and how you did them. 
- What didn't go well, What did, 

### Construct Library
The problem this project aimed to solve was ever increasing complexity of requirements to run an AWS resource in a company way.  The solution that was build is what we call the construct library and was a means to cast a developer into a pit of success. Using the [AWS Cloud Developer Kit](https://docs.aws.amazon.com/cdk/v2/guide/getting_started.html), a, infrastructure as Code library, as our based,  we extended the resources definitions to include the 3M defaults. That way when you define an S3 bucket in you IAC, then you get one that prebaked with all the company defaults and the developer gets their bucket. So instead of focusing on making sure the they have the right tags, they can get back to their own work. 

I've handled this project from the prototype I created, to leading the a dev team to build it out, to driving it's adoption.  The library is primarily written in Typescript, the native language of AWS CDK and made it available as a NPM package through the internal GitHub Packages offering. 

Later, I architected and lead the team to implement solution based constructs.  Instead of a single compliant by default resource, a developer could get a suite of resources. The first solution construct we delivered was a basic full stack web application.  I loving refereed to it as the Vanilla Web App because it's as basic as it gets. 

### Falcon2
Before we talk about Falcon2 we must first understand Falcon.  Falcon is a suite of tools created to accelerate my company's DevOps journey to AWS and it succeed. It was a custom solution built that solved a lot of problems for the organization in the beginning. But with all things, cracks start to show. It was built on top of a self hosted CI/CD pipeline tool that is expensive be to maintained.  It's approach to cross account access is questionable. It was fundimentally a prototype that made it into production, but it was time for a rework. 

Falcon2 we built off a few key guiding principals. 
- Simplify the developer experience.  Get them in, get them what they need, and let them move on. 
- Apply Guardrails to the risky deployable resources.
- Securely provisions resources.
- Simplify by using Github Actions SAS offering over self hosted solution.   



### Digital Marketplace


## Tools I use