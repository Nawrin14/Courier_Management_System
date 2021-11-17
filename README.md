# Courier Management System

It is a database software that allows the courier service companies to manage and monitor all the data. The project details can be found [here](https://github.com/Nawrin14/Courier_Management_System/blob/master/Courier%20Management%20System.pdf).

# Instructions

Firstly, a database named 'CourierManagementSystemDatabase' has to be created Secondly, 'CUSTOMER', 'RECEIVER' & 'DELIVERYMAN' tables have to be created  After creating the 'CUSTOMER' table, 'PAYMENT' table has to be created since 'CustomerNID' is a foreign key from 'CUSTOMER' table. Then, 'PACKAGE' & 'VEHICLE' tables have to be created. Now, 'ORDERS' table is created because it contains foreign keys from the previous 6 tables. Lastly, 'Admin' table has to be created and later, the 'UNIQUE' constraint must be added to the 'AdminUserName' attribute.

Two changes have to be made after creating the 'DELIVERYMAN' table:
1. The 'UNIQUE' constraint has to be added to the 'Email' attribute.
2. A new attribute 'DeliverymanPassWord' has to added.

After sequentially doing the steps above, the project can be built and run in the NetBeans IDE.

# Software Requirements

1. SQL Server 2014 Management Studio
2. SQL Server 2014 Configuration Manager
3. Java SE Development Kit 8
4. Apache NetBeans IDE 12.0

# Other Contributors

1. [Monjure Mowla Abir](https://github.com/abir2727) 
2. [Kaji Fuad Bin Akhter](https://github.com/FuadBinAkhter)