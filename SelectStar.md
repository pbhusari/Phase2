# Select * Statments

Team 11


## SQL Statments

### Results

```sql
select * from INVOICELINE
/

select * from PAYMENT
/

select * from INVOICE
/

select * from ACCOUNT
/

select * from RECEVING_REPORT_LINE
/

select * from RECEVING_RECIEPT
/

select * from SHIPMENT
/

select * from PURCHASE_ORDER_LINE
/

select * from PURCHASE_ORDER
/

select * from EMPLOYEE
/

select * from DEPARTMENT
/

select * from STOCKPILE
/

select * from INVENTORY_ITEM
/

select * from WAREHOUSE
/
```


### Results

```

INVOICE_IN INVOICELIN ITEMTYPE                       DESCRIPTION                                                                                                                                                                                                                                                       QUANTITY  UNITPRICE        TAX
---------- ---------- ------------------------------ --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ---------- ---------- ----------
1          1          Service                        Consultation Fee                                                                                                                                                                                                                                                         2         15          0
1          2          Product                        Monitors Sold                                                                                                                                                                                                                                                            3        150        .08
2          1          Product                        Desktop Computers                                                                                                                                                                                                                                                       10        666        .08
3          1          Service                        Server Space Rent                                                                                                                                                                                                                                                       12         .5          0
4          1          Product                        Laptops Sold For DataTech Equipment                                                                                                                                                                                                                                      2        300        .08
5          1          Service                        Fake data population                                                                                                                                                                                                                                                     5         75          0
6          1          Service                        Pied Piper Legal Fees, lawyer hours                                                                                                                                                                                                                                     10       1000          0
7          1          Product                        Endframe licensing fee for 2 computers                                                                                                                                                                                                                                   2        150        .08
8          1          Service                        Messaging service, quantity per client                                                                                                                                                                                                                                  30         10        .01
9          1          Product                        Pizza                                                                                                                                                                                                                                                                   10          5        .08
10         1          Product                        Pizza                                                                                                                                                                                                                                                                   10          5        .08

INVOICE_IN INVOICELIN ITEMTYPE                       DESCRIPTION                                                                                                                                                                                                                                                       QUANTITY  UNITPRICE        TAX
---------- ---------- ------------------------------ --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ---------- ---------- ----------
10         2          Product                        Pizza                                                                                                                                                                                                                                                                   10          5        .08
10         3          Product                        Pizza                                                                                                                                                                                                                                                                   10          5        .08
10         4          Product                        Pizza                                                                                                                                                                                                                                                                   10          5        .08
9          2          Product                        Pizza                                                                                                                                                                                                                                                                   10          5        .08
9          3          Product                        Pizza                                                                                                                                                                                                                                                                   10          5        .08
9          4          Product                        Pizza                                                                                                                                                                                                                                                                   10          5        .08

17 rows selected. 


ACCOUNT_AC PAYMENTID  METHOD                                                                                                                                                                                                                                                          PAYMENTDA PAYMENTRE PAYMENTAMOUNT INVOICE_IN
---------- ---------- --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- --------- --------- ------------- ----------
10         1          Client Checking                                                                                                                                                                                                                                                 07-APR-14 10-APR-19           516 1         
1          10         Credit Card                                                                                                                                                                                                                                                     07-FEB-19 07-FEB-19           113 10        
2          11         Checking                                                                                                                                                                                                                                                        07-FEB-19 07-FEB-19           113 10        
1          2          Investor Checking                                                                                                                                                                                                                                               08-MAY-14 08-MAY-14        7192.8 2         
3          3          Investor Checking                                                                                                                                                                                                                                               15-SEP-14 10-APR-19             6 3         
2          4          Investor Checking                                                                                                                                                                                                                                               07-OCT-14 10-APR-19           648 4         
3          5          Investor Checking                                                                                                                                                                                                                                               05-DEC-14 10-APR-19           375 5         
2          6          Investor Checking                                                                                                                                                                                                                                               08-JAN-15 10-APR-19           500 6         
3          12         Investor Checking                                                                                                                                                                                                                                               08-JAN-15 10-APR-19           500 6         
2          7          Investor Checking                                                                                                                                                                                                                                               09-AUG-16 10-APR-19           324 7         
2          8          Investor Checking                                                                                                                                                                                                                                               09-AUG-16 13-APR-19           203 8         

ACCOUNT_AC PAYMENTID  METHOD                                                                                                                                                                                                                                                          PAYMENTDA PAYMENTRE PAYMENTAMOUNT INVOICE_IN
---------- ---------- --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- --------- --------- ------------- ----------
4          13         Checking                                                                                                                                                                                                                                                        09-AUG-16 13-APR-19           203 8         
1          9          Credit Card                                                                                                                                                                                                                                                     16-AUG-18 16-AUG-18           108 9         
1          14         Credit Card                                                                                                                                                                                                                                                     16-AUG-18 16-AUG-18           108 9         

14 rows selected. 


INVOICEID  ISSUEDATE DUEDATE   SUBJECT                                                                                                                                                                                                                                                         PURCHASE_O
---------- --------- --------- --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ----------
1          07-APR-14 07-MAY-14 Purdue Analytics Consultation Sale                                                                                                                                                                                                                              1         
2          08-MAY-14 08-JUN-14 DataTech Equipement Purchase                                                                                                                                                                                                                                    2         
3          15-SEP-14 15-NOV-14 DataTech Server Lease                                                                                                                                                                                                                                           3         
4          07-OCT-14 07-NOV-14 DataTech Employee Laptops                                                                                                                                                                                                                                       4         
5          05-DEC-14 05-JAN-15 DataTech Fake SQL Data                                                                                                                                                                                                                                          5         
6          08-JAN-15 08-OCT-15 Pied Piper Legal Fees                                                                                                                                                                                                                                           6         
7          09-AUG-16 09-NOV-16 Endframe License                                                                                                                                                                                                                                                7         
8          11-SEP-17 11-OCT-17 Optimoji Messaging Service                                                                                                                                                                                                                                      8         
9          12-AUG-18 12-SEP-18 Sliceline Pizza                                                                                                                                                                                                                                                 9         
10         07-FEB-19 07-MAR-19 Sliceline Pizza                                                                                                                                                                                                                                                 10        

10 rows selected. 


ACCOUNTID  ACCOUNTNAME                                        ACCOUNTNUMBER ACCOUNTROUTINGNUMBER ACCOUNTDESCRIPTION                                                                                                                                                                                                                                             
---------- -------------------------------------------------- ------------- -------------------- ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
1          Purdue Fed                                                 77687                  985 Personal                                                                                                                                                                                                                                                       
2          Breem Hall                                                 87686                  112 Investor                                                                                                                                                                                                                                                       
3          Pete Gregory Foundation                                    24828                  564 Investor                                                                                                                                                                                                                                                       
4          Pied Piper                                                 15971                  546 Client                                                                                                                                                                                                                                                         
5          Endframe                                                   31804                  329 Client                                                                                                                                                                                                                                                         
6          DataTech                                                   22071                  684 Company                                                                                                                                                                                                                                                        
7          FastFit                                                    64777                  645 Client                                                                                                                                                                                                                                                         
8          SliceLine                                                  81634                  321 Client                                                                                                                                                                                                                                                         
9          Optimoji                                                   31358                  215 Client                                                                                                                                                                                                                                                         
10         Purdue Analytics                                            6131                  798 Client                                                                                                                                                                                                                                                         

10 rows selected. 


RECEVINGRE RECEVINGRE ITEMDESCRIPTION                                                                                                                                                                                                                                                 ITEMQUANTITY  ITEMPRICE
---------- ---------- --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ------------ ----------
1          RR9        Pizza                                                                                                                                                                                                                                                                      9          4
4          RR9        Pizza                                                                                                                                                                                                                                                                     10          5
3          RR9        Pizza                                                                                                                                                                                                                                                                      8       4.99
2          RR9        Pizza                                                                                                                                                                                                                                                                     10          5
1          RR7        Endframe licensing fee for 2 computers                                                                                                                                                                                                                                     2        150
1          RR4        Laptops Sold For DataTech Equipment                                                                                                                                                                                                                                        2        300
1          RR2        Desktop Computers                                                                                                                                                                                                                                                         10        666
1          RR10       Pizza                                                                                                                                                                                                                                                                     15          5
4          RR10       Pizza                                                                                                                                                                                                                                                                     10          5
3          RR10       Pizza                                                                                                                                                                                                                                                                     10          5
2          RR10       Pizza                                                                                                                                                                                                                                                                     10          5

11 rows selected. 


RECEVINGRE SHIPMENT_S EMPLOYEE_E SHIPPINGDOCK                        DATERECIV
---------- ---------- ---------- ----------------------------------- ---------
RR1        1          0010       Dock A                              11-APR-14
RR2        4          0010       Dock A                              17-APR-14
RR3        5          0012       Dock C                              26-APR-14
RR4        6          0012       Dock C                              18-OCT-14
RR5        7          0010       Dock A                              22-OCT-14
RR6        8          0012       Dock C                              18-AUG-16
RR7        9          0012       Dock C                              21-JUL-17
RR8        10         0012       Dock C                              08-AUG-17
RR9        2          0011       Dock C                              09-SEP-14
RR10       3          0011       Dock D                              16-SEP-14

10 rows selected. 


SHIPMENTID Date      PURCHASE_O SUPPLIER                            FULFILMENTMETHOD                    DROPLOCATION                        PRICEPERPOUND     WEIGHT
---------- --------- ---------- ----------------------------------- ----------------------------------- ----------------------------------- ------------- ----------
1          07-APR-14 1          Alibaba                             Over Land                           Warehouse                                       1         20
4          07-APR-14 9          Berts Pizza                         Delivery                            Office                                          5          1
5          07-APR-14 10         Berts Pizza                         Delivery                            Office                                          5          1
6          07-OCT-14 4          Yang's Laptops                      Over Land                           Warehouse                                      .5         10
7          10-OCT-14 4          Yang's Laptops                      Over air                            Office                                          2         10
8          09-AUG-16 7          EndFrame                            Electronic                          Office                                          0          0
9          08-JUL-17 11         Sandisk Consumer                    Over Land                           Warehouse                                     .75          3
10         08-JUL-17 11         Sandisk Consumer                    Over Land                           Office                                        .75          3
2          07-APR-14 10         Berts Pizza                         Delivery                            Office                                          5          1
3          07-APR-14 1          Alibaba                             Over Land                           Warehouse                                       1         20
11         08-MAY-14 2          Alibaba                             Over Land                           Warehouse                                       2         10

11 rows selected. 


PURCHASE_O ORDERLINEI ESITMATEDITEMPRICE ITEMQUANTITY INVENTORY_
---------- ---------- ------------------ ------------ ----------
10         1                        10.5           10 1         
10         2                           9           10 1         
10         3                          10           10 1         
10         4                        10.6           10 1         
9          1                         8.8           10 1         
9          2                          10           10 1         
9          3                          10           10 1         
1          1                         150            3 2         
2          1                         600            5 3         
4          1                         315            2 4         
7          1                         150            2 5         

11 rows selected. 


ORDERID    Date      DELIVERYD EMPLOYEE_E
---------- --------- --------- ----------
1          07-APR-14 10-APR-14 0003      
2          08-MAY-14 11-MAY-14 0003      
3          15-SEP-14 09-SEP-14 0003      
4          07-OCT-14 11-OCT-14 0003      
5          05-DEC-14 18-DEC-14 0003      
6          08-JAN-15 11-JAN-19 0002      
7          09-AUG-16 14-AUG-16 0002      
8          11-SEP-17 13-SEP-17 0003      
9          12-AUG-18 11-AUG-18 0003      
10         07-FEB-19 14-FEB-19 0003      
11         08-JUL-17 10-JUL-19 0003      

11 rows selected. 


EMPLOYEEID FIRSTNAME                                          LASTNAME                                           HIREDATE  PHONENUMBE ADDRESS                             DEPARTMENT     SALARY      BONUS      RAISE
---------- -------------------------------------------------- -------------------------------------------------- --------- ---------- ----------------------------------- ---------- ---------- ---------- ----------
0001       Christian                                          Chandler                                           06-APR-19 2025550139 366 Brookside Court Florence        TECH              100          0        .01
0002       Patrick                                            Bateman                                            06-NOV-99 2025550101 8287 Kent Ave. owosso               EXEC              120          2        .01
0003       Huey                                               Lewis                                              02-APR-01 2025550107 7778 High Point Ave. Willoughby     SHIP               60          3        .01
0004       Paul                                               Allen                                              06-SEP-18 2025550187 8974 Argyle Court South Portland    TECH              100          5        .01
0005       Andrew                                             Yang                                               11-OCT-15 2025550183 8526 Gartner St. West Warwick       HR                 70          6        .01
0006       Donald                                             Sanders                                            27-NOV-01 2025550133 9498 Vermont Ave. Oak Park          PAY                30          2          0
0007       Bernie                                             Trump                                              20-NOV-13 2025550119 9837 Wild Rose Lane Metairie        TECH              100          0        .01
0008       Alexandria                                         Ramerez                                            11-JUN-12 2025550132 176 Mill Pond Ave.                  TECH              120          9          0
0009       Ricardo                                            Chandler                                           27-SEP-13 2025550167 279 Galvin St. Sicklerville         MGMT               70          0        .01
0010       Christian                                          Chantor                                            13-AUG-14 2025550137 15 Railroad Ave. Lenoir             REC                30          9        .01
0011       Myles                                              Lesser                                             09-APR-13 2023214030 14 Ross Ade Dr.                     REC                                        

EMPLOYEEID FIRSTNAME                                          LASTNAME                                           HIREDATE  PHONENUMBE ADDRESS                             DEPARTMENT     SALARY      BONUS      RAISE
---------- -------------------------------------------------- -------------------------------------------------- --------- ---------- ----------------------------------- ---------- ---------- ---------- ----------
0012       Pranav                                             Bhusari                                            13-JUN-12 2025551489 15 Tarkington Bolevard              REC                                        

12 rows selected. 


DEPARTMENT BUILDING                            DESCRIPTION                                                                                                                                                                                                                                                     DUTIES                                                                                                                                                                                                                                                         
---------- ----------------------------------- --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
SHIP       200 North Side                      Shipping                                                                                                                                                                                                                                                        Send outgoing packages                                                                                                                                                                                                                                         
REC        200 North Side                      Receving                                                                                                                                                                                                                                                        Receving incoming packages                                                                                                                                                                                                                                     
ACCT       200 North Side                      Accounting                                                                                                                                                                                                                                                      Account for losses/gains                                                                                                                                                                                                                                       
MGMT       120 South St                        Management                                                                                                                                                                                                                                                      Act as an intermediary between execs and low level employees                                                                                                                                                                                                   
PAY        120 South St                        Payment                                                                                                                                                                                                                                                         Draft invoices                                                                                                                                                                                                                                                 
INV        200 North Side                      Inventory                                                                                                                                                                                                                                                       Update Inventory                                                                                                                                                                                                                                               
TECH       110 South St                        Technology                                                                                                                                                                                                                                                      Keep tech working how its supposed to work                                                                                                                                                                                                                     
SALES      100 South St                        Sales                                                                                                                                                                                                                                                           Meet potential customers and turn them into customers                                                                                                                                                                                                          
HR         100 South St                        Human Resources                                                                                                                                                                                                                                                 Fire people                                                                                                                                                                                                                                                    
EXEC       100 South St                        Executive                                                                                                                                                                                                                                                       Make descisions about the company                                                                                                                                                                                                                              

10 rows selected. 


INVENTORY_ WAREHOUS LASTINVEN   QUANTITY
---------- -------- --------- ----------
1          9        05-APR-19          5
1          9        06-APR-19          5
1          2        06-APR-19          7
2          3        05-APR-19          6
2          3        03-APR-19         20
2          4        08-MAR-19         10
7          7        03-APR-19          2
1          6        06-JAN-19          7
1          10       07-APR-19          3

9 rows selected. 


ITEMID     DESCRIPTION                                                                                                                                                                                                                                                  QUANTITY HEIGHTINCHES WIDTHINCHES LENGTHINCHES WEIGHTPOUND MANUFACTURERER                
---------- ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ---------- ------------ ----------- ------------ ----------- ------------------------------
1          Pizza                                                                                                                                                                                                                                                              10            1          24           24           3 Sliceline                     
2          Monitor                                                                                                                                                                                                                                                            10            9          16            3          20 LG                            
3          Desktop Computer                                                                                                                                                                                                                                                    3           12           6           12          20 MSI                           
4          Laptop Computer                                                                                                                                                                                                                                                     2            5          12            2           2 Dell                          
5          EndFrame License                                                                                                                                                                                                                                                    2                                                   EndFrame                      
6          Raspberry pi                                                                                                                                                                                                                                                       30            5           3            1          .5 Raspi Foundation              
7          Micro USB Cable                                                                                                                                                                                                                                                    30            2           5            2          .5 Monoprice                     
8          32 GB SD Card                                                                                                                                                                                                                                                      30            1           2            1          .1 Sandisk                       
9          1 TB SSD                                                                                                                                                                                                                                                            5            2           3            5          .1 Seagate                       
10         Thunderbolt Adapter                                                                                                                                                                                                                                                10            2           5            2          .5 Monoprice                     

10 rows selected. 


WAREHOUS STREETADDRESS                                                                                   ST CITY                                ZIPCODE                             NAME                                                                                                                                                                                                                                                            DATEESTAB
-------- ----------------------------------------------------------------------------------------------- -- ----------------------------------- ----------------------------------- --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ---------
1        617 Gann Rd                                                                                     TN Milan                               38358                               FIrst warehouse                                                                                                                                                                                                                                                 08-APR-98
2        612 2nd St                                                                                      NC Fairmont                            28340                               DateaTech WorldHub                                                                                                                                                                                                                                              13-APR-13
3        13137 E 2nd St                                                                                  IA Moulton                             52572                               DataTech MainStorage                                                                                                                                                                                                                                            15-SEP-01
4        10600 E 640th S                                                                                 IN Hudson                              46747                               DataTech Consumer Resources Warehouse                                                                                                                                                                                                                           22-OCT-05
5        12546 Oxnard St                                                                                 CA North Hollywood                     91606                               DataTech Furniture Storage                                                                                                                                                                                                                                      23-OCT-16
                                                                                                                                                                                                                                                                                                                                                                                                                                                             

6        2215 73rd St E #LOT 147,                                                                        FL Palmetto                             34221                              DataTech SmartWareHouse                                                                                                                                                                                                                                         19-JUN-06
7        15853 Lawton St                                                                                 MI Detroit                             48238                               DataTech GreenHouse                                                                                                                                                                                                                                             12-SEP-14
8        223 S Fraley St                                                                                 PA Kane                                 16735                              DataTech SmartGreenHouse                                                                                                                                                                                                                                        08-OCT-15
9        11539 Padgett Switch Rd                                                                         AL Irvington                           36544                               DataTechPizzaStorage                                                                                                                                                                                                                                            14-AUG-19

WAREHOUS STREETADDRESS                                                                                   ST CITY                                ZIPCODE                             NAME                                                                                                                                                                                                                                                            DATEESTAB
-------- ----------------------------------------------------------------------------------------------- -- ----------------------------------- ----------------------------------- --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- ---------
10       611 N Cottage Ave                                                                               MT  Miles City                         59301                               DataTech Technology resource center                                                                                                                                                                                                                             06-APR-19

10 rows selected. 


```
