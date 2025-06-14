﻿## 🌏 Contoso Sales Territory Dashboard - Power BI RLS Demo

This project demonstrates a **Power BI Dashboard** integrated with **Row-Level Security (RLS)** using a realistic sales dataset for Contoso. It features territory-wise country managers and their access-controlled visualizations based on assigned sales regions.

## 📊 Project Overview




The dashboard visualizes key business metrics such as:

- **Total Sales**
- **Sales Target**
- **Achievement %**
- **Quota Variance**
- **Month-over-Month (MoM) Growth**
- **Rolling 12-Month Sales**

## 📷 Dashboard Preview
![Contoso Sales RLS Dashboard](./ContosoRLSpage.jpg)

### Features:

- Yearly and Monthly filters
- Country-based Row-Level Security (RLS)
- Clear comparison between actual sales and targets
- Region-wise and product-wise breakdown

## 🧩 Dataset Overview

A manually curated table was used to define Country Managers and their respective sales territories. This table is the core of the RLS configuration in Power BI.

| Email                                         | Country Manager      | Sales Territory Country |
| --------------------------------------------- | -------------------- | ----------------------- |
| ahied.mahi@datacrafters.io                    | Ahied Mahi Chowdhury | Australia               |
| ahied.mahi@datacrafters.io                    | Ahied Mahi Chowdhury | Armenia                 |
| ahied.mahi@datacrafters.io                    | Ahied Mahi Chowdhury | Bhutan                  |
| golamrabbani@grsalman769gmail.onmicrosoft.com | Golam Rabbani Salman | Denmark                 |
| golamrabbani@grsalman769gmail.onmicrosoft.com | Golam Rabbani Salman | Canada                  |
| golamrabbani@grsalman769gmail.onmicrosoft.com | Golam Rabbani Salman | France                  |
| juwel.mallick@datacrafters.io                 | Juwel Mallick        | Germany                 |
| juwel.mallick@datacrafters.io                 | Juwel Mallick        | Greater China           |
| juwel.mallick@datacrafters.io                 | Juwel Mallick        | Greece                  |
| mirza.eshraq@datacrafters.io                  | Mirza Eshraq         | Iran                    |
| mirza.eshraq@datacrafters.io                  | Mirza Eshraq         | Ireland                 |
| mirza.eshraq@datacrafters.io                  | Mirza Eshraq         | India                   |
| sadman.nahid@datacrafters.io                  | Shadman Sakib Nahid  | Japan                   |
| sadman.nahid@datacrafters.io                  | Shadman Sakib Nahid  | Kyrgyzstan              |
| sadman.nahid@datacrafters.io                  | Shadman Sakib Nahid  | Italy                   |
| nasif.azam@datacrafters.io                    | Nasif Azam           | Pakistan                |
| nasif.azam@datacrafters.io                    | Nasif Azam           | Malta                   |
| nasif.azam@datacrafters.io                    | Nasif Azam           | Poland                  |
| nazmul.hasan.munna@datacrafters.io            | Nazmul Hasan Munna   | Romania                 |
| nazmul.hasan.munna@datacrafters.io            | Nazmul Hasan Munna   | Russia                  |
| nazmul.hasan.munna@datacrafters.io            | Nazmul Hasan Munna   | Portugal                |
| sadia.ani@datacrafters.io                     | Sadia Rahman Ani     | Slovenia                |
| sadia.ani@datacrafters.io                     | Sadia Rahman Ani     | South Korea             |
| sadia.ani@datacrafters.io                     | Sadia Rahman Ani     | UK                      |
| sadia.ani@datacrafters.io                     | Sadia Rahman Ani     | United States           |
| sadia.ani@datacrafters.io                     | Sadia Rahman Ani     | Singapore               |
| sourav.biswas@datacrafters.io                 | Sourav Biswas        | Sweden                  |
| sourav.biswas@datacrafters.io                 | Sourav Biswas        | Switzerland             |
| sourav.biswas@datacrafters.io                 | Sourav Biswas        | Spain                   |
| zehan.alam@datacrafters.io                    | Zehan Alam           | Thailand                |
| zehan.alam@datacrafters.io                    | Zehan Alam           | The Netherlands         |
| zehan.alam@datacrafters.io                    | Zehan Alam           | Turkmenistan            |
| zehan.alam@datacrafters.io                    | Zehan Alam           | Syria                   |

📁 You can also find this RLS table in the Excel file: **TerritoryManagers.xlsx**

## 🚀 How to Use

1. Clone this repository.
2. Open the Power BI report file (`.pbix`) in Power BI Desktop.
3. Import the Excel file `TerritoryManagers.xlsx` to configure RLS.
4. Configure RLS roles in Power BI under **Modeling > Manage Roles**.
5. Test RLS using **View As Roles** in Power BI Desktop.

## 📌 Technologies Used

- Power BI Desktop
- Excel (for managing access table)
- DAX & Power Query
- Row-Level Security

---

🔒 **Note**: RLS ensures that each country manager only sees data relevant to their assigned countries.

---

## 📫 Contact

If you have any queries or want to contribute, feel free to reach out!
