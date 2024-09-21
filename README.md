
# Shipment Management System with JsonPowerDB

## Description

The **Shipment Management System** is a web application built to manage shipment data such as shipment number, description, source, destination, shipping date, and expected delivery date. This project utilizes **JsonPowerDB (JPDB)** as the backend database for storing and managing shipment records. JsonPowerDB is a fast, efficient, and secure NoSQL database that simplifies the handling of complex database operations.

## Benefits of Using JsonPowerDB

1. **Easy Integration**: JPDB is simple to integrate with web applications and provides a rich set of APIs.
2. **Minimal Setup**: No complex database setups or configurations. Just create a database, set your API keys, and start.
3. **Fast and Lightweight**: Highly efficient with quick data retrieval and storage.
4. **Low Latency**: Delivers data instantly due to optimized RESTful API access.
5. **Versatile**: Supports multi-mode database functionalities such as key-value, document, and relational database models.
6. **In-Built Security**: JPDB provides an access control layer and secure token-based API requests.

## Release History

- **Version 1.0** (Sep 2024): Initial release with basic CRUD functionality using JPDB. Supports insertion, retrieval, and updating of shipment data.

## Table of Contents

- [Description](#description)
- [Benefits of Using JsonPowerDB](#benefits-of-using-jsonpowerdb)
- [Release History](#release-history)
- [Scope of Functionalities](#scope-of-functionalities)
- [Examples of Use](#examples-of-use)
- [Project Status](#project-status)
- [Sources](#sources)
- [Other Information](#other-information)

## Scope of Functionalities

This project enables the following functionalities:
- **Create Shipment**: Users can create a new shipment record with unique shipment numbers.
- **Update Shipment**: Allows users to update existing shipment details.
- **View Shipment**: Fetch existing shipment records by shipment number.
- **Form Reset**: Reset the form fields for a fresh start.
  
Data is validated before submission, ensuring that no fields are left empty.

## Examples of Use

- **Creating a new shipment**: Enter shipment number and other details, then click **Save** to store the record in the database.
- **Updating an existing shipment**: Enter an existing shipment number, and once the record is loaded, update the fields and click **Update**.
- **Resetting the form**: Click **Reset** to clear the form fields and start a fresh entry.

## Project Status

- **Version 1.0**: Complete, functional, and stable.
- Future features will include better error handling, enhanced UI, and further integration with JPDB's advanced features.

## Sources

- **JsonPowerDB Official Documentation**: [JsonPowerDB Documentation](https://login2explore.com/jpdb/docs.html)
- **jQuery Documentation**: [jQuery Documentation](https://jquery.com/)

## Other Information

- This project uses **HTML**, **CSS**, and **JavaScript** for the front end and **JsonPowerDB** as the database.
- Contributions, bug reports, and feature requests are welcome.
