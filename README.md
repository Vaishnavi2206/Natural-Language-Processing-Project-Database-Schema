# Natural-Language-Processing-Project-Database-Schema

Tables:

company_info: Consists information about companies.
event_info: Consists information about events.
people_info: Consists information about people working in companies.

Relationships:

Relationship 1: Events and company data can be merged using ‘event_url’ column.
Relationship 2: Company and people data can be merged using ‘homepage_base_url’ colum.

Attributes:

This repository contains the CREATE TABLE definitions for all three tables (company_info, event_info, people_info) in the database schema, along with corresponding CSV files for data insertion.

Challenges Faced:

During the development and management of this database, several challenges were encountered:

Ensuring Data Integrity: Maintaining data consistency and integrity across multiple tables and transactions was a significant challenge

Handling Large Datasets: Efficiently managing and querying large volumes of data posed challenges in terms of performance optimization, indexing strategies, and resource allocation.

Managing Queries for Different Data Types: Adapting queries and schema changes when transitioning data types, such as converting from VARCHAR to TIMESTAMP for date columns

Improvements for Database Design
Given more time to work on the database design, several improvements could be implemented:

Normalization Refinement: Further normalize the schema to eliminate redundancy and improve data consistency.

Indexing Strategy: Implement a comprehensive indexing strategy based on query patterns and performance benchmarks to enhance query speed.

Schema Flexibility: Design the schema to be more flexible to accommodate future changes and new requirements more seamlessly.

Documentation: Enhance schema documentation to improve understanding and ease of maintenance for future developers.
