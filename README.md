# Rice Mill CRM Application

### Category: Salesforce

## Project Overview
The Rice Mill CRM Application is a comprehensive solution designed to streamline and simplify operations in a wholesale rice mill factory. It automates reporting on daily rice production, sales, and stock tracking, while providing detailed analytics and insights to the business owners. This project is built on Salesforce, leveraging its customer relationship management (CRM) capabilities to enhance operational efficiency, customer experience, and business performance.

## Features and Functionality

1. **Reporting and Dashboards**:  
   The application generates daily reports on rice sold, total income, and the most popular types of rice, presenting this data in a way that is easy to understand. This helps in improving resource allocation and planning future production.

2. **Rollup Summary Fields**:  
   Rollup summary fields are used to aggregate data from child objects (e.g., rice details) to parent objects (e.g., supplier). This allows you to display the total amount of rice supplied from the related supplier.

3. **Cross-Object Formula Fields**:  
   Formula fields that reference fields from another object in Salesforce are used to calculate the total cost (rice taken * price/kg) that needs to be paid by the supplier.

4. **Validation Rules**:  
   Validation rules are used to ensure data integrity. For example, the `IsBlank` formula is used to display an error message if a required field is left empty.

5. **Permission Sets**:  
   Organization-Wide Defaults (OWD) are used to restrict access. Roles are assigned so that the owner can see all records, the employer can see worker records, and workers have limited access.

## Prerequisites

- Salesforce Developer account
- Knowledge of Salesforce admin concepts
- Installed with 2 web browsers on the machine
- Good internet connectivity

## What I've Learned

- Real-time Salesforce Project Development
- Object & Relationship Management in Salesforce
- Formula Fields and Validation Rules
- Cross-Object Formula Fields
- Page Layouts
- Rollup Summary Fields
- Reports and Dashboards

## Done by
**Akashdip Saha**

---

## Documentation and Video Links

- **Documentation**: [[Project Documentation](https://docs.google.com/document/d/1ZYUgGFjW66nSG-M7Aywi-JlUGixwifGR/edit?usp=sharing&ouid=110948134362735888233&rtpof=true&sd=true)](#)
- **YouTube Demo**: [[Watch the Demo on YouTube](https://youtu.be/fJv4Uj_9pcY)](#)
