# WP3 - Working Groups (Months 0 to 3)

Based on an the initial clustering, the working group consisting of problem owners from each co-developing city, and at least a product owner and technical team member and a representative from the testing cities.

1. Plan: Sets up common 2 year working group timeline, key milestones and collaboration structures to ensure a coherent working method for the working group, that also integrates with the overall project plan.
2. Common architecture: Reviews survey done by Uni of Bradford (D4.1) to assess the available data and technical architecture of both partners, implementation opportunities in the Living Labs, and what would be reasonable architecture to deploy the projects further.
3. Agree solution: Agrees to start co-developing a particular software solution to the common problem, based on guidelines from Ghent (D3.1), input from public service providers and citizens (D3.4), and a business case (D3.6).
4. Research: Researches existing Open Source solutions or libraries that can be adapted and built on.
5. Commit: Ensure internal support in each city to continue to the project definition phase

This phase is followed by [Project Definition (Months 3 to 5)](project-definition.md).

## IoT Registry Project example story of operationalising working groups:

The ‘IoT registry working group’ is made up out of the cities of Aarhus and Amsterdam who want to co-develop a register for sensor data. Göteborg and Ghent join, as they want to implement and test the solution. Aarhus and Ghent already have some rich data sources for outdoor sensors, while Amsterdam and Göteborg lack these. Amsterdam requires functionality around the compulsory registration of the devices.

In the architecture survey (from D4.1) it is identified both Aarhus, Gent and Amsterdam share a common Docker based ‘microservice’ infrastructure for deploying these kind of applications, but Göteborg has PHP server architecture. The project thus has to work on these cities own systems as well as commercially available hosting. 

In the Open Source research phase it is found that building a new application on top of the existing Open Source application ‘Sentilo’, an IoT data platform developed originally by the City of Barcelona. However both the front-end and the backend do not fit the requirements with Amsterdam’s registration system and its very strict privacy policies. A project is proposed to build a new front-end for Sentilo in addition to changing and creating new modules for the backend to solve the challenge for all the cities and Living Labs.
