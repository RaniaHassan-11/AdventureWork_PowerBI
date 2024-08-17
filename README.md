# AdventureWork_PowerBI

## About Project  :
In this report, you'll find a wide array of visuals, including bar charts, tables, and line graphs, which offer a granular view of Adventure Works' sales performance over time. I've also leveraged Power BI's advanced features such as slicers, DAX (Basics), and Tooltip, all the while establishing relationships between data tables to ensure a user-friendly experience. This allows viewers to not only dive deeper into the data but also customize their view to extract the precise information they seek.

## Steps :
1. Utilized Power Query for importing Excel files, data cleaning, grouping, aggregating, merging queries, appending queries, defining hierarchies, creating a rolling calendar table, and adding new columns.
2. Implemented data modeling by creating table relationships, a Star Schema, and updating the filter flow.
3. Leveraged DAX to create columns and new measures.
4. Created visuals using various tools like page filters, image insertion, slicers, multiple visuals (Cards & KPIs, Text Cards, Metrix, Map, etc.)

## Data Modeling :
Data Modeling is one of the features used to connect multiple data sources in BI tool using a relationship. A relationship defines how data sources are connected with each other and you can create interesting data visualizations on multiple data sources.
![DataModel](https://github.com/user-attachments/assets/2945315d-5fd6-43e7-8218-d7d9ce847d91)

### Hierarchies :
- Hierarchies are groups of nested columns that reflect multiple
levels of granularity
- For example, a “Product” hierarchy might include CategoryName ,SubcategoryName and ProductName columns.
- Each hierarchy can be treated as a single item in tables and reports, allowing users to “drill up” and “drill down” through different levels of the hierarchy in a
meaningful way.

![image](https://github.com/user-attachments/assets/0f1e2cd7-6333-4503-b4a0-b22a5059e1c6)


## DAX Measures :
- Measures are DAX formulas used to generate new calculated values
- Use measures to create numerical, calculated values that can be analyzed in the “values” field of a report visual
- Measures are evaluated based on filter context, which means they recalculate when the fields or filters around them change (like when new row or column labels are pulled into a matrix or when new filters are applied to a report)
  
![image](https://github.com/user-attachments/assets/ea6cad81-e1eb-4af6-80e4-6bad539a0ef9)



## The Power BI Dashboard :
![image](https://github.com/user-attachments/assets/e3368f8d-7e08-4bfe-b052-6a094283022b)





