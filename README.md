# Security-Report-System-by-KQL
## Microsoft Defender can show status on devices such as Antivirus status , Attack surface reduction , Alert get data with KQL query and Power quert to sort data .Then use powerbi  to show dashboard and Power Automate to send email went device alert. 

### Data security is an essential aspect in the current era where data is of utmost importance. Data is a vital asset in today's digital age, and ensuring its security is crucial.
#### The objectives are as follows:
#### 1.To study and acquire knowledge regarding data security measures.
#### 2.To study and learn the usage of KQL (Kusto Query Language).
#### 3.To study and understand the design of security reporting using reports.
#### 4.To develop an automated alert system that notifies of risks or threats.

## Architecture
![image](https://github.com/nomnut/Security-Report-System-by-KQL/assets/75019120/5187b185-bc0c-4e6d-b669-b30b3c939fda)

### Microsoft 365 Defender incorporates Advanced Hunting, a sophisticated detection system that allows for threat hunting based on provided queries. It retains raw data for up to 30 days, enabling the investigation of network events for proactive identification of indicators and threat alerts. The flexible data access empowers users to search for both known and potential threats without limitations.
![image](https://github.com/nomnut/Security-Report-System-by-KQL/assets/75019120/0805bc8f-610f-4ddf-93cb-f49ac015f549)

### The API Explorer is a tool used to retrieve connection information from one system to another (API), making it easier to build, test, query, and send requests to the Defender for Endpoint API. The API Explorer allows for performing operations and retrieving data from the system in a JSON format using OData. This functionality is available within the Power BI tool.
![image](https://github.com/nomnut/Security-Report-System-by-KQL/assets/75019120/eb665bfc-ff7e-4352-a01e-fb9b6a7ad8ff)

### The Advanced Editor is a feature in Power Query that allows for advanced editing of formulas and scripts. It utilizes the M language, which is the underlying language that powers Microsoft Power BI. By leveraging the capabilities of the M language, the Advanced Editor enables efficient manipulation of data.

#### The M language is a scripting language that works behind the scenes when creating formulas using Power Query. It works seamlessly with other Microsoft technologies, allowing for effective utilization of all available data. With the M language, users can create powerful data transformations and manipulations in the background using Power Query.
![image](https://github.com/nomnut/Security-Report-System-by-KQL/assets/75019120/d295437e-df4f-4778-ba6b-c7134b474c69)

### The Advanced Editor is a feature within Power Query, which is a part of Microsoft Power BI. When creating queries using Power Query, the Advanced Editor provides a backstage view that allows for advanced customization. It utilizes the M language, which is responsible for executing the operations in the background.

#### The M language is a scripting language that works in conjunction with Microsoft technologies to efficiently process data. By leveraging the M language, users can work with data effectively, performing powerful transformations and manipulations.

#### Furthermore, the Advanced Editor in Power Query allows for incorporating Kusto Query Language (KQL), a query language specifically designed for efficient data retrieval and customizable data visualization options. KQL is similar to Structured Query Language (SQL) in terms of querying data but differs in that KQL is primarily used for querying and doesn't support data updating or deletion.

![image](https://github.com/nomnut/Security-Report-System-by-KQL/assets/75019120/db36d670-5ed1-43c5-b24f-d50a9f37e67a)
