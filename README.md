SSIS Excel Data Import Project

This SSIS project is designed to import data from an Excel spreadsheet and perform control flow operations on the imported data. The project is built using SQL Server Integration Services (SSIS) and can be run using the SQL Server Data Tools (SSDT) or the SQL Server Management Studio (SSMS).

Prerequisites

SQL Server
SQL Server Data Tools (SSDT) or SQL Server Management Studio (SSMS)
Microsoft Excel

Getting Started
Clone or download the project to your local machine
Open the project in SSDT or SSMS
Update the Excel file path in the "Excel Source" task to match the location of your Excel file
Update the connection string in the "OLE DB Destination" task to match your database connection
Run the package by right-clicking on the package and selecting "Execute"
Control Flow
The package includes control flow tasks such as "Data Flow Task" and "Execute SQL Task" that can be configured as per your requirement.

![etl-in-ssis](https://github.com/eugeneaondo/ETL-Using-SSIS/assets/51509202/c6639577-c0a8-4075-bbcf-3abf5b9f185a)

Note
Please make sure that the excel sheet should have the same structure and columns as per the package has been designed.

Support
If you have any issues or questions, please open an issue on the GitHub repository or contact the maintainer.
