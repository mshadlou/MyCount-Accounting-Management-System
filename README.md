# MyCount-Accounting-Management-System
This version of MyCount [8.2.4 released on 15th July] is designed to facilitate sales and accounting of almost all businesses. The simplicity of work accompanied by special features, the faster performance of accountants in different departments and at the same time to issue documents and receive desired financial and tax reports are the most important part of designing this accounting software.
<br>

## Basic definitions and features in MyCount: 
### Account permission: <br>
introduction of persons at a certain or privileged level and definition of the full characteristics of the account party<br>

### warehouse definition: <br>
the possibility of defining several warehouses and classifying warehouses into main and sub-groups such as warehouse name, product type or brand.<br>

### product definition: <br>
Definition of product specifications, including name, barcode, model, country of manufacture, exchange rate, technical codes and purchase and sale prices.<br>

### Defining bank accounts and specifying them to suppliers and customers: <br>
This menu can be used to introduce all current and savings bank accounts.<br>

## Accounting operations: 
Defining general, specific and special accounts and the possibility of grouping and changing their nature in the section of accounting headings or coding, issuing accounting documents automatically and manually, deleting and correcting issued documents, closing accounts at the end of the period (closing document or closing month) and automatic creation of a new financial year, a complete report of issued documents normally and selectively, the possibility of transferring documents, modifying the opening document, the possibility of inserting between documents, group deletion of documents and the general printing in the desired format.<br>

## Issuing all types of invoices: 
Issuing all types of invoices including purchase, sale, invoice, deposit, registration of combined payment and receipt operations: check, cash, credit, discount, check to spend, applying discounts. It also provides diversity on sales invoices, i.e. separation of discounts, cash and credit settlements, separate discounts for each account, calculating value-added tax, introducing one or more intermediaries when issuing an invoice, and differentiating product quality in stock and showing it in inventory controls and warehouse management.<br>

## Product-related operations: 
Product-related operations are carried out at levels of main, secondary, product name, minimum and maximum inventory control, warehouse and management decision-making, transfer between warehouses/stocks, and introducing specifications for products. <br>

## Check and bank: 
Registring the received and paid debits and checks, notification of collection, return from collection mode, notification of the receipt of checks automatically.<br>


## Technical point:
To design and implement this software, SQL Server and T-SQL scripting weres used for the database and C# was used for implementing the software. I will work on the Decentralised feature where MyCount software communicates with the MyCount server and Azure SQL database. <br>
Full infrastructure of the MyCount is shown as follows:<br>

[![MyCount Infrastructure](https://github.com/mshadlou/MyCount-Accounting-Management-System/blob/main/Infrastructure.JPG)]()

For this development, most of the ideas came from a valuable book written by Jack Johnson. I have made a thorough revision of his codes while have taken his design principles. The MyCount has more features i.e. SQL database has more entities and tables to support an advanced version of the accounting management system.<br>

ER Diagram is shown in following:
[![ER Diagram](https://github.com/mshadlou/MyCount-Accounting-Management-System/blob/main/ER%20Diagram.jpg)]()

#### Reference: 
<a href="https://www.amazon.co.uk/Practice-SERVER-Accounting-System-Project-ebook/dp/B08FGHK72F">Jack Johnson's book</a>

To view a demo of the software, you may check the youtube view at <a href="https://youtu.be/xhN0bpSIpD8
![image](https://user-images.githubusercontent.com/87391484/179256774-326d00c6-ba55-4f01-8829-fbb036392628.png)
">YouTube video</a>


