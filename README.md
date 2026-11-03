✨✨ ✨✨

## Tartar 

**Railway Carrier Document Adaptation System**  

Tartar is a VBA-based document transformation solution designed to standardize transportation settlement documents received from multiple railway carriers. 

The system addresses a common business challenge where carriers provide transportation acts in different Excel formats, with varying field names, structures, layouts, and calculation rules. These differences prevent direct loading of carrier data into enterprise systems and require extensive manual processing. 

Tartar automates the adaptation process by converting carrier-specific documents into a unified, business-approved format containing the standardized fields required for downstream SAP upload processes. 

 
 

## Business Problem 

Transportation acts received from carriers are not submitted in a single agreed format. Each carrier may use: 

- Different field names 

- Different column structures 

- Different numbers of fields 

- Carrier-specific calculations 

- Different document layouts 

- Unique business rules 

- As a result, manual preparation of documents for SAP loading is time-consuming and prone to errors. 

- The organization required a solution capable of transforming documents from multiple carriers into a single standardized format while maintaining compliance with business requirements. 

 
 

## Solution 

Tartar implements a configurable transformation framework based on carrier-specific processing logic. 

For each carrier, a dedicated adaptation procedure is developed according to functional specifications provided by business users. These specifications define: 

- Source document structure 

- Required business fields 

- Field mapping rules 

- Transformation logic 

- Calculation formulas 

- Validation requirements 

- Output file structure 

- Each carrier is assigned a unique creditor code used during processing and file generation. 

- The system transforms source data into a normalized format that can be used directly by SAP data loading procedures. 

 
 

## Key Features 

- Automated adaptation of transportation acts from multiple carriers 

- Carrier-specific transformation and mapping logic 

- Business-driven processing rules 

- Data validation and quality checks 

- Automated generation of standardized output files 

- Automatic file naming based on creditor code and act number 

- Support for multiple carrier document formats 

- Extensible architecture for onboarding new carriers 

- Reduction of manual processing effort 

- Generation of SAP-ready datasets 

 
 

## Workflow 

- The user selects a carrier from the application interface. 

- The user uploads the transportation act received from the selected carrier in Excel format. 

- The system executes the carrier-specific transformation procedure. 

- Source fields are mapped and transformed according to the approved functional specification. 

- Required calculations and validations are performed. 

- A standardized output dataset is generated. 

- The user saves the resulting file. 

- The generated file is subsequently used by SAP upload processes. 

- The output filename is automatically generated using: 

<Creditor Code>_<Act Number>.xlsx 
 

- This naming convention ensures consistency, traceability, and easier processing of generated files. 

 
 

## Architecture 

Carrier Excel File 
         | 
         v 
Carrier-Specific Handler 
         | 
         v 
Transformation Engine 
         | 
         v 
Validation Rules 
         | 
         v 
Standardized Dataset 
         | 
         v 
Output File 
         | 
         v 
SAP Upload Process 
 

 
 

## Technology Stack 

- Microsoft Excel 

- VBA (Visual Basic for Applications) 

- VBA Class Modules 

- VBA UserForms 

- Excel Automation 

- Data Transformation and Validation Logic 

 
 

# Business Value 

The solution significantly improves operational efficiency by automating the standardization of carrier transportation documents. 

**Benefits** 

- Reduced manual document processing effort 

- Faster preparation of data for SAP loading 

- Improved data quality and consistency 

- Reduced risk of user errors 

- Standardized processing across carriers 

- Easier onboarding of new carrier formats 

- Improved auditability and traceability 

- Increased reliability of downstream business processes 

 
 

## Project Structure 

Tartar/ 
│ 
├── Forms/ 
├── Modules/ 
├── Classes/ 
├── CarrierHandlers/ 
├── Examples/ 
├── Documentation/ 
└── README.md 
 

 
 

## Security and Data Protection 

This public repository does not contain: 

Production data 

Business-sensitive information 

Carrier documents 

SAP credentials 

Customer data 

Internal company records 

Sample files, if provided, contain only demonstration data. 

 
 

## Author 

Nikolay Kiyanovskiy 

SAP Specialist | Business Analyst | VBA Developer 

 
 

