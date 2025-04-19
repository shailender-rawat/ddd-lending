# ddd-lending

have been working in SME Lending for 7 years and 

Define problem statement(s) 
> how software maintenance is getting difficult
> big ball of mud (BBoM)
> external API dependency is major change
> isolation 

what is domain driven design and how can it help in addressing the issues assoicated with 

Does your project need DDD / refer to DDD Scorecard (referred in Vaughan Book)
As a concept was Eric Evans, Refer to the 2 books that can be considered for developing a greater understanding 

Diagram of the DDD

Explaination of the key terms of the DDD 

What is the objective of the blog / Appyling the principles and patterns of DDD in Lending / Covers STRATEGIC design

Lending
> Loan Initiation
> Loan Eligibility (Data Collection, Fraud Check, System Checks, others)
> Loan Decisioning
> Loan Disbursement
> Loan Servicing

What is the difference between Strategic Design and Tactical Design 

why strategic design is important 


Part 1: Domain discovery
(reviewing a pre-prepared event storm)
Part 2: Designing domain boundaries
(chopping the event storm up into domains/subdomains)
Part 3: Choosing core domains
(modelling the strategy)
Part 4: Designing domain collaboration
(designing end-to-end processes to identify coupling and validate responsibilities)

1st step - Domain Event 
How - using Event Storming technique

How event storming works

<<Create the diagram >>

Using the above diagram create the Commands, Events, Entities, Ubiquitous Language for each Bounded Context 


Strategic Design
Which Strategic Patterns are you familiar with? (Multiple choices)

 Bounded Contexts
 Ubiquitous Language
 Core Domain and Subdomains
 Context Mapping
 Other... (Open text)
How do I identify a Bounded Context? (Open text)

How do I know a Bounded Context is Core Domain? (Open text)

How do I know a Bounded Context is Supportive Subdomain? (Open text)

How do I know a Bounded Context is a Generic Subdomain? (Open text)

How do I differentiate between them? (Open text)

What's Context Mapping used for? (Open text)

Which kind of Context Mappings do you know? (Open text)

TL;DR [Rewrite]
The building block of domain-driven design is the ubiquitous language. The ubiquitous language connects people in the project, so everyone can understand each other. We have to keep using the language that comes from the domain and never invent our own.

So simple, yet so powerful.

Next time we’ll take a look at Tactical Design.

Reference 
1. 
https://github.com/SAP/curated-resources-for-domain-driven-design/blob/main/ddd-kata.md

Books:
Domain-Driven Design: Tackling Complexity in the Heart of Software by Eric Evans
Implementing Domain-Driven Design by Vaughn Vernon
Patterns, Principles, and Practices of Domain-Driven Design by Scott Millett and Nick Tune

Blogs:
Strategic Domain Driven Design with Context Mapping / 
https://martinfowler.com/tags/domain%20driven%20design.html
https://martinfowler.com/bliki/DomainDrivenDesign.html

Context Mapping - Chapter 4 - Learning Domain-Driven Design / https://www.oreilly.com/library/view/what-is-domain-driven/9781492057802/ch04.html
Bounded Context - Martin Fowler

YouTube:
DDD Bounded Contexts & Subdomains
Bounded Contexts - Eric Evans - DDD Europe 2020
Introduction to Context Mapping - Michael Plöd - DDD Europe 2022

