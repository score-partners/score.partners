# Research: challenge working groups

To find possible [solutions](/glossary/solutions.md) for shared [challenges](/glossary/challenge.md) partners come together in challenge [working groups](/glossary/working-group.md).

The working group consist of:

* problem owners from each co-developing partner
* product owners form each co-developing partner
* technical team members from the co-developing partners
* a representative from each testing partners

The working group does the following:

* __Common architecture__: Reviews survey done by Uni of Bradford (D4.1) to assess the available data and technical architecture of involved solution development partners, implementation opportunities in the Living Labs, and what would be reasonable architecture to deploy the solutions further.
* __Research__: Researches existing Open Source solutions or libraries that can be adapted and built on.
* __Commit__: Ensure internal support in each partner to continue to the solution definition phase
* __Start solution definition__: Agrees to start co-developing a particular software solution to the common problem, based on guidelines from Ghent (D3.1), input from public service providers and citizens (D3.4), and a business case (D3.6).

Working groups have their own topic on the [SCORE Community](https://score.community/c/working-groups) in the Working Groups category. In that category there is also a pinned post with the details and committed members of each working group. Anyone is free to join a Working Group.

## IoT Registry solution example story:

> The ‘IoT registry working group’ is made up out of the cities of Aarhus and Amsterdam who want to co-develop a register for sensor data. Göteborg and Ghent join, as they want to implement and test the solution. Aarhus and Ghent already have some rich data sources for outdoor sensors, while Amsterdam and Göteborg lack these. Amsterdam requires functionality around the compulsory registration of the devices.
> 
> In the architecture survey (from D4.1) it is identified both Aarhus, Gent and Amsterdam share a common Docker based ‘microservice’ infrastructure for deploying these kind of applications, but Göteborg has PHP server architecture. The solution thus has to work on these cities own systems as well as commercially available hosting. 
> 
> In the Open Source research phase it is found that building a new application on top of the existing Open Source application ‘Sentilo’, an IoT data platform developed originally by the City of Barcelona. However both the front-end and the backend do not fit the requirements with Amsterdam’s registration system and its very strict privacy policies. A solution is proposed to build a new front-end for Sentilo in addition to changing and creating new modules for the backend to solve the challenge for all the cities and Living Labs.
