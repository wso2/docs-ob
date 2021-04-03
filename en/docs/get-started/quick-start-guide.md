WSO2 Open Banking Accelerator is a technology stack catered to speed up the implementation of an open banking solution. 
You can use the WSO2 Open Banking Accelerator on top of the WSO2 Identity Server and API Manager to obtain an environment 
for Identity Access Management and API management in open banking. 

Follow the instructions to find how you can quickly set up and try out a basic flow...

!!! tip "Prerequisites"
    1. Download Oracle JDK 1.8 to the local environment.
        - In the environment variables, update the JAVA_HOME and PATH variables. For instance, you can do this on a Mac/Linux server by adding the following to the ~/.bashrc file:
        ```
        export JAVA_HOME="<JDK_LOCATION>"
        export PATH=$PATH:$JAVA_HOME/bin
        ```
    2. Download and extract the following base products:
        1. WSO2 Identity Server (IS) 5.11.0 
        2. WSO2 API Manager (APIM) 4.0.0
        3. WSO2 Streaming Integrator (SI) 4.0.0
    3. Download WSO2 Open Banking Accelerator 3.0.0 and Identity Server as a Key Manager (IS KM) Connector.
        -  WSO2 Open Banking Accelerator contains the following accelerators.
           Wso2-ob-is-accelerator-3.0.0
           Wso2-ob-apim-accelerator-3.0.0
           wso2-ob-bi-accelerator-3.0.0
    4. Setup a database server using MySQL 8.0.23,  Microsoft SQL Server 2017, Oracle 19c, and PostgreSQL 13.0.

- This document using the following placeholders to refer to the following products:
        
| Product | Placeholder |
|---------|---------    |
|wso2-ob-is-accelerator-3.0.0|{IS_HOME}|
|wso2-ob-apim-accelerator-3.0.0|{APIM_HOME}|
|IS Extensions|{ISKM_HOME}|
|Open Banking Identity Server Accelerator|{OB_IS_ACCELERATOR_HOME}|
|Open Banking API Manager Accelerator |{OB_APIM_ACCELERATOR_HOME}|




    

