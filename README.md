# E-commerce-Back-End

## Description

This project is a back-end for an e-commerce website, designed to enable a retail company to compete effectively in the internet retail space. Built with the latest technologies, this back-end leverages Express.js and Sequelize to manage database interactions with a PostgreSQL database.

## User Story

As a manager at an internet retail company,  
I want a back end for my e-commerce website that uses the latest technologies  
So that my company can compete with other e-commerce companies.

## Acceptance Criteria

- **GIVEN** a functional Express.js API  
  - **WHEN** I add my database name, PostgreSQL username, and PostgreSQL password to an environment variable file  
  - **THEN** I am able to connect to a database using Sequelize.

- **WHEN** I enter schema and seed commands  
  - **THEN** a development database is created and seeded with test data.

- **WHEN** I enter the command to invoke the application  
  - **THEN** my server is started and the Sequelize models are synced to the PostgreSQL database.

- **WHEN** I open API GET routes in Insomnia for categories, products, or tags  
  - **THEN** the data for each of these routes is displayed in a formatted JSON.

- **WHEN** I test API POST, PUT, and DELETE routes in Insomnia  
  - **THEN** I am able to successfully create, update, and delete data in my database.


