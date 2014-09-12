Project Name
==============================================================
Velocity

Class
==============================================================
CIS 355: Business Data Warehouses and Dimensional Modeling

Purpose
==============================================================
This project is based on the Financial Services case study for CIS 355.

Team Members
==============================================================
Manoj Panikkar,
Christopher Frame,
Schuyler Mortimer



Project Topic
==============================================================
Chapter 10: Financial Services
  * Banking Case Study and Business Matrix
      * This case study discusses a simple retail bank.  The bank's goal is to better analyze the bank's accounts in order to market more effectively by offering additional products to households that already have one or more acconts with the bank.  
      * The following requirements were developed:
          * See five years of historical monthly snapshot data on every account
          * Every account has a primary balnace.  The business wants to group different types of accounts in the same analyses and compary primary balances
          * Every type of account has a set of custom dimensional attributes and numeric facts
          * Every accout belongs to a single household
          * Users are also interested in demographic information of individual custmers and households.  Also, the bank captures and stores behavior scores relatng o the activity or characteristics of each account and household.
  * Dimension Triage to Avoid Too Few Dimensions
      * Household Dimension
      * Multivalued Dimensions and Weighting Factors
      * Mini-Dimensions Revisited
      * Adding a Mini-Dimension to a Bridge Table
      * Dynamic Value Banding of Facts
  * Supertype and Subtype Schemas for Heterogeneous Products
      * Supertype and Subtype Products with Common Facts
  * Hot Swappable Dimensions

Chapter 10 Summary
==============================================================
From Kimball, R., & Ross, M. (2013). *The Data Warehouse Toolkit (3rd ed.)*:
> We began this chapter by discussing the situation in which a fact table has too few dimensions and provided suggestions for ferreting out additional dimensions using a triage process.  Approaches for handling the often complex relationship between accounts, customers, and households were described.  We also discussed the use of multiple mini-dimensions in a single fact table, which is fairly common in financial service schemas.

> We illustrated a technique for clustering numeric facts into arbitrary value bands for reporting purposes through the use of a separate band table.  Finally, we provided recommendations for any organization that offers heterogeneous products to the same set of customers.  In this case, we create a supertype fact table that contains performance metrics that are common across all lines of business.  The companion dimension table contains rows for the complete account portfolio, but the attributes are limited to those that are applicable across all accounts.  Multiple subtype schemas, one of each line of business, complement the supertype schema with account-specific facts and attributes. 

