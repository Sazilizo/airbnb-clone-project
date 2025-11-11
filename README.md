
About the Project

The Airbnb Clone Project is a comprehensive, real-world application designed to simulate the development of a robust booking platform like Airbnb. It involves a deep dive into full-stack development, focusing on backend systems, database design, API development, and application security. This project enables learners to understand complex architectures, workflows, and collaborative team dynamics while building a scalable web application.

Team Roles
    Business Analyst
    - Turns the customers needs into tangible ideas and requirements to deliver the required customer results

    Product Owner
    - They are responsible for planning and strategizing, will come up with ways to make the product a success

Technology Stack
Django, MySQL, and GraphQL in a unified ecosystem.
    Django - a high-level Python web framework designed to help developers build robust, secure, and scalable web applications quickly and efficiently.
            It follows the Model–View–Template (MVT) architectural pattern, similar to MVC (Model–View–Controller).
    
    MySQL - a relational database management system (RDBMS) based on SQL (Structured Query Language).
            It stores data in tables (rows and columns) with predefined schemas that describe how data is structured and related. 

    GraphQL - a query language and runtime for APIs, developed by Facebook. It lets clients request exactly the data they need, and nothing more, from 
    a single API endpoint

Database Design:
    Users - Users can have multiple properties, book and pay for multiple properties
    Property - can have one owner or a group of owners owning it. one-to-one, one-to-many
    Booking - can have one user or two for a specific property, but no two users can have the same property at the same time same day (double booking, one payment received in time, no cancelations -> alert the other user for the inavailability of the property if no payment already) one-to-one
    Reviews - multiple users can make multiple reviews on the properties they visited, one user to many
    Payments - One user can make a payment for a property, property is taken off the market, one-to-one