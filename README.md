# Sales Analysis

This is a project aimed at performing data analysis on sales data. The initial inspiration for this project came from a sample business demand overview gathered from a stakeholder email. The email contained valuable insights into what he would like to see in a sales dashboard to make data-driven decisions and gain a better understanding of our sales performance.

The project involves creating a SQL Server using Microsoft SQL Server Express, uploading data via a .bak file, and building a dashboard around that data using Power BI. The dashboard visualizes various sales metrics and KPIs, providing actionable insights to optimize sales strategies.
## Technologies Used

- Microsoft SQL Server
- SQL Server Management Studio
- Power BI
- Sample Data (AdventureWorks sample databases)

## Prerequisites

To run this project locally or deploy it on your own server, you'll need the following software installed:

- Microsoft SQL Server Express
- SQL Server Management Studio
- Power BI Desktop

## Installation

1. Clone or download this repository to your local machine.
2. Install Microsoft SQL Server Express if you haven't already (download link: [https://www.microsoft.com/en-us/sql-server/sql-server-downloads](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)).
3. Open SQL Server Management Studio and connect to your SQL Server Express instance.
4. Restore the sample data using the provided .bak file. You can find the .bak file in the "data" folder of this repository.
   - Open SQL Server Management Studio.
   - Right-click on "Databases" in the Object Explorer.
   - Choose "Restore Database."
   - Select "Device" and browse to the .bak file.
   - Click "OK" to restore the database.
5. Open Power BI Desktop and connect to your SQL Server Express database to build the sales dashboard.

## Usage

Once you have set up the project, you can use Power BI to explore and analyze the sales data. The dashboard provides various visualizations, such as sales trends, top-selling products, regional performance, and more.

## Folder Structure

- `data/`: Contains the .bak file for sample data.
- `dashboard/`: Includes Power BI files and resources for the sales dashboard.

## Data Source

The project uses the AdventureWorks sample databases as a data source. You can find more information about this dataset and other sample databases from Microsoft's official documentation.

