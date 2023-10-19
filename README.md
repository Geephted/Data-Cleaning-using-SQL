# Data-Cleaning-using-SQL

## Intorduction 
In the realm of data analysis, projects often take us to intriguing datasets that hold valuable insights waiting to be uncovered. In one such endeavor, I ventured into the world of the Nashville Housing Data, a comprehensive information detailing land use and property information in the Tennessee capital, Nashville. To unlock the dataset's hidden potential, I harnessed SQL through Microsoft SQL Management Server Studio, embarking on an extensive journey of exploration and data cleansing.

SQL, or Structured Query Language, is a potent tool for efficient data cleaning and transformation. With a range of functions and operations at its disposal, SQL stands as a widely recognized computer language for managing and manipulating relational databases.

In this project, we'll delve into how SQL can elevate dataset quality. We'll explore syntax and showcase SQL queries for data cleansing. To illustrate effective cleaning techniques and best practices, we'll provide SQL code samples, shedding light on the art of effective data refinement.

## Dataset 
The dataset was gotten from Kaggle. You can find the dataset [here.](url)

## Understanding the Nashville Housing Data Dataset

The dataset is composed of 19 columns and 56,477 rows.

- UniqueID — id number attributed to a buyer.
- ParcelID — code attributed to a land.
- LandUse — shows the different uses of land.
- SalesPrice — cost of land
- LegalReference — citation is the practice of crediting and referring to authoritative documents and sources.
- OwnerName_ name of land owner
- Acreage — the size of an area of land in acres
- LandValue — the worth of the land
- Building Value — worth of a building
- Total Value — landvalue + building value
- YearBuilt — year the building was built
- FullBath — a bathroom that includes a shower, a bathtub, a sink, and a toilet.
- HalfBath — a half bathroom only contains a sink and a toilet
- Sale_Date — date when the land was sold
- SaleAddress — address of land sold
- City — location of land
- Owner_Address — owners house address
- OwnerCity — city where owner lives
- OwnerState — state where owner is located

As it would be essential for the cleaning process, we would first try to comprehend and understand the dataset in order to gain a sense of it and see its shape.

```
--View of the Raw Data
Select * 
From DataCleaning;
