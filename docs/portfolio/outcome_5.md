# Development and Operations

[Portfolio](../../README.md) | Development and...

You set up environments and tools which support your chosen software development process. You provide governance for all stakeholders’ goals. Furthermore, you aim for as much automation as possible, to enable short release times and high software quality.

## Scale

| ID | Description | Type | Level |
|---|---|---|---|
| 5.1 | GitHub Environment | GP | Beginning |
| 5.2 | Local environment | IP | Beginning |
| 5.3 | SDLC activities | IP | Beginning |
| 5.4 | GitHub actions | IP/GP | Proficient |

## Argumentation

### 5.1: GitHub environment

Worked on setting up the organization for our team in GitHub. 

- Created the team and added everyone to that team.
- Set up branches for the team with branch protection.
- Added a template repository for setting up future services.
- Created a master repository.
    - All the repositories and documentation are now available in a central place.
    - Issues can be gathered in one place.
    - All services can be pulled with one recursive clone.
- Started on documentation on how the organization works and how to set up for future teams.

[FIPost GitHub link](https://github.com/FIPost)

### 5.2 Local environment

Made it easier to run the local environment to a bat script. With executing a single script the developer can set up his local environment in docker.

[FFT GitHub link](https://github.com/SjorsScholten/FoodForThoughts)

### 5.3 SDLC activities

Described for every SDLC phase what a programmer can do to improve development.

[Scenario view](https://github.com/SjorsScholten/FoodForThoughts/blob/master/docs/architecture/scenarios.md)

### 5.4 GitHub actions CI/CD

Configured a CI/CD pipeline for my application using GitHub actions. On push the services are build and tested. A SonarCloud build is also made to check for bugs, code smells, and vulnerabilities

[FFT GitHub actions](https://github.com/SjorsScholten/FoodForThoughts/actions)