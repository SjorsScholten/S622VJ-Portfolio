# Distributed Data

[Portfolio](../../README.md) | Distributed Data

[Uitleg leeruitkomst]: #

## Scale

| ID | Description | Type | Level |
|---|---|---|---|
| 8.1 | Database orientation | IP | orienting |
| 8.2 | MongoDB implementation | IP | beginning |
| 8.3 | Data scaling with MongoDB | IP | beginning |
| 8.4 | GDPR analysis of data | IP | proficient |

## Argumentation

### 8.1: Database Orientation

Made the choice to use MongoDB as a database for my system. From previous use I know that MongoDB is a scalable NoSQL database which can run in the cloud. Next step is to figure out how to implement it.

### 8.2 MonogDB Implementation

Set up a docker container running an image of MongoDB when starting the backend in local environment. The application can read and write to this database. The next step is to apply it to the development environment by connecting it to the cloud endpoint.

### 8.3 Data scaling with MongoDB

Looked at how I could scale my databases in MongoDB. With the free tier you get 3 preconfigured shards. With higher paid tiers you can configure both horizontal and vertical.

### 8.4 GDPR analysis of data

Did research on what is GDPR (see case), and made a small analysis of my data in the security view.