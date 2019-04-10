# Desc Statments

Team 11

## SQL Statment

```sql
desc INVOICELINE
/

desc PAYMENT
/

desc INVOICE
/

desc ACCOUNT
/

desc RECEVING_REPORT_LINE
/

desc RECEVING_RECIEPT
/

desc SHIPMENT
/

desc PURCHASE_ORDER_LINE
/

desc PURCHASE_ORDER
/

desc EMPLOYEE
/

desc DEPARTMENT
/

desc STOCKPILE
/

desc INVENTORY_ITEM
/

desc WAREHOUSE
/


```

## Results

```
Name              Null?    Type               
----------------- -------- ------------------ 
INVOICE_INVOICEID NOT NULL CHAR(10)           
INVOICELINEID     NOT NULL CHAR(10)           
ITEMTYPE                   VARCHAR2(30)       
DESCRIPTION                VARCHAR2(255 CHAR) 
QUANTITY                   NUMBER             
UNITPRICE                  NUMBER             
TAX                        NUMBER             
Name              Null?    Type               
----------------- -------- ------------------ 
ACCOUNT_ACCOUNTID          CHAR(10)           
PAYMENTID         NOT NULL CHAR(10)           
METHOD                     VARCHAR2(255 CHAR) 
PAYMENTDATE                DATE               
PAYMENTRECIVETIME          DATE               
PAYMENTAMOUNT              NUMBER             
INVOICE_INVOICEID          CHAR(10)           
Name                   Null?    Type               
---------------------- -------- ------------------ 
INVOICEID              NOT NULL CHAR(10)           
ISSUEDATE              NOT NULL DATE               
DUEDATE                         DATE               
SUBJECT                NOT NULL VARCHAR2(255 CHAR) 
PURCHASE_ORDER_ORDERID          CHAR(10)           
Name                 Null?    Type               
-------------------- -------- ------------------ 
ACCOUNTID            NOT NULL CHAR(10)           
ACCOUNTNAME                   VARCHAR2(50 CHAR)  
ACCOUNTNUMBER        NOT NULL NUMBER(10)         
ACCOUNTROUTINGNUMBER          NUMBER(5)          
ACCOUNTDESCRIPTION            VARCHAR2(255 CHAR) 
Name                 Null?    Type               
-------------------- -------- ------------------ 
RECEVINGREPORTLINEID NOT NULL CHAR(10)           
RECEVINGRECIEPTID    NOT NULL CHAR(10)           
ITEMDESCRIPTION               VARCHAR2(255 CHAR) 
ITEMQUANTITY                  NUMBER             
ITEMPRICE                     NUMBER             
Name                Null?    Type              
------------------- -------- ----------------- 
RECEVINGRECIEPTID   NOT NULL CHAR(10)          
SHIPMENT_SHIPMENTID          CHAR(10)          
EMPLOYEE_EMPLOYEEID          CHAR(10)          
SHIPPINGDOCK                 VARCHAR2(35 CHAR) 
DATERECIVED                  DATE              
Name                   Null?    Type              
---------------------- -------- ----------------- 
SHIPMENTID             NOT NULL CHAR(10)          
Date                            DATE              
PURCHASE_ORDER_ORDERID          CHAR(10)          
SUPPLIER                        VARCHAR2(35 CHAR) 
FULFILMENTMETHOD                VARCHAR2(35 CHAR) 
DROPLOCATION                    VARCHAR2(35 CHAR) 
PRICEPERPOUND                   NUMBER            
WEIGHT                          NUMBER            
Name                   Null?    Type     
---------------------- -------- -------- 
PURCHASE_ORDER_ORDERID NOT NULL CHAR(10) 
ORDERLINEID            NOT NULL CHAR(10) 
ESITMATEDITEMPRICE              NUMBER   
ITEMQUANTITY                    NUMBER   
INVENTORY_ITEM_ITEMID           CHAR(10) 
Name                Null?    Type     
------------------- -------- -------- 
ORDERID             NOT NULL CHAR(10) 
Date                         DATE     
DELIVERYDATE                 DATE     
EMPLOYEE_EMPLOYEEID          CHAR(10) 
Name                    Null?    Type              
----------------------- -------- ----------------- 
EMPLOYEEID              NOT NULL CHAR(10)          
FIRSTNAME                        VARCHAR2(50)      
LASTNAME                         VARCHAR2(50 CHAR) 
HIREDATE                         DATE              
PHONENUMBER                      VARCHAR2(10 CHAR) 
ADDRESS                          VARCHAR2(35 CHAR) 
DEPARTMENT_DEPARTMENTID          CHAR(10)          
SALARY                           NUMBER(9,2)       
BONUS                            NUMBER(9,2)       
RAISE                            NUMBER(2,2)       
Name         Null?    Type               
------------ -------- ------------------ 
DEPARTMENTID NOT NULL CHAR(10)           
BUILDING              VARCHAR2(35 CHAR)  
DESCRIPTION           VARCHAR2(255 CHAR) 
DUTIES                VARCHAR2(255 CHAR) 
Name                   Null?    Type     
---------------------- -------- -------- 
INVENTORY_ITEM_ITEMID  NOT NULL CHAR(10) 
WAREHOUSE_WAREHOUSEID  NOT NULL CHAR(8)  
LASTINVENTORYCHECKDATE NOT NULL DATE     
QUANTITY                        NUMBER   
Name           Null?    Type               
-------------- -------- ------------------ 
ITEMID         NOT NULL CHAR(10)           
DESCRIPTION             VARCHAR2(250 CHAR) 
QUANTITY                NUMBER             
HEIGHTINCHES            NUMBER             
WIDTHINCHES             NUMBER             
LENGTHINCHES            NUMBER             
WEIGHTPOUND             NUMBER             
MANUFACTURERER          VARCHAR2(30 CHAR)  
Name            Null?    Type               
--------------- -------- ------------------ 
WAREHOUSEID     NOT NULL CHAR(8)            
STREETADDRESS   NOT NULL VARCHAR2(95 CHAR)  
STATE                    VARCHAR2(2 CHAR)   
CITY                     VARCHAR2(35 CHAR)  
ZIPCODE                  VARCHAR2(35 CHAR)  
NAME                     VARCHAR2(255 CHAR) 
DATEESTABLISHED NOT NULL DATE               
```