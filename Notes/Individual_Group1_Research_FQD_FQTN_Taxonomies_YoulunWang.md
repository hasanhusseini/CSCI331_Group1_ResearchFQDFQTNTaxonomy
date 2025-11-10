Youlun Wang

Notes on Research

Fully Qualified Domains

https://www.lightsondata.com/what-is-a-data-domain-examples-included/

A collection of values that a data element may contain, 

it sets the standards for organizations across different departments speak the same language.

allowing reusability 

### Fully Qualified Domain (FQD)

- In SQL theory (ANSI standard), a domain is a user-defined data type — a reusable data element that defines not just the type (VARCHAR) but also constraints and meaning.
- T-SQL implements similar behavior through `CREATE TYPE`.

### Fully Qualified Table Name (FQTN)

- This is the complete reference to a table, identifying it by database, schema, and table name.
- used in select queries but also maintains clarity to which exact database, schema being referenced

### Taxonomy

- A taxonomy is the organizational classification of data assets — a business-level hierarchy describing how datasets, tables, and domains relate to business entities.
- Consistent Organizations
- Better Data Access
- Improved Data quality
- Efficient data analysis and reporting
- Data governance and compliance

https://amplitude.com/explore/data/what-data-taxonomy

## Data taxonomy example

To help understand how data taxonomy works, let’s consider an example for an ecommerce company.

Top-level categories may contain:

- Products
- Customers
- Orders
- Marketing
- Inventory

You then have the option for several subcategories from these main categories. For example, subcategories under ‘Products’ could include:

- Electronics
- Clothing
- Home and kitchen
- Beauty and personal care

Subcategories under each product category would help classify the information further. For example, under ‘Electronics’:

- Computers and laptops
- Smartphones and tablets
- TVs and home entertainment
- Audio and headphones