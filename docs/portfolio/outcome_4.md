# Scalable Architecture

[Portfolio](../info_portfolio.md) | Scalable Architecture

[Uitleg leeruitkomst]: #

## Scale

| ID | Description | Type | Level |
|---|---|---|---|
| 4.1 | Architecture Documentation | IP | Beginning |
| 4.2 | Ocelot API Gateway| IP/GP | Beginning |

## Argumentation

### 4.1: Architecture Documentation

Created first iteration of the architecture document. I have written my documentation in Markdown, so it's easier to link sections. I used C4 models to create different views of my systems. There is currently a container model showing the whole system and its connected cloud services, a deployment diagram to show how it would run in its production environment, and use case diagrams to show the functionality of the system.

### 4.2 Ocelot API Gateway

Implemented an Ocelot API Gateway for both the IP and GP. In the GP it will replace the existing Gateway as it was a bad implementation (using logic to retrieve information from multiple services in a single call). I use the same architecture in my IP so here ocelot was also viable.