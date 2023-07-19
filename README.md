# LowCodeAppGeneration
Repository to test available Low Code app generation tools using **GitHub Codespaces.**

# App generation platforms I am evaluating:

 - BuideBase : https://budibase.com/ 
 - Retool: https://retool.com/

# Quick Comparision

|                                                                                           |     | BudiBase                                  | Retool                                                                                                         |   |   |   |
|-------------------------------------------------------------------------------------------|-----|-------------------------------------------|----------------------------------------------------------------------------------------------------------------|---|---|---|
| Mobile App Generation                                                                     |     | No                                        | Yes                                                                                                            |   |   |   |
| Hosting Locally                                                                           |     | Yes                                       | Yes                                                                                                            |   |   |   |
| Use Docker-Compose                                                                        |     | Yes                                       | Yes,  I am getting an error when docker-compose up is run. See note 1 on how I install Retool GitHub CodeSpace |   |   |   |
| Buit-in Database to store data. This is good for an app which does not use existing data. |     | Yes Budibase DB is the native datasource. | Yes Retool DB is a PostgreSQL with a spreadsheet-like interface to manage data                                 |   |   |   |
| Connection to external Databases. This is a must for an which uses existing data          |     | Yes                                       | Yes                                                                                                            |   |   |   |

**Note 1:** 

 1. Goto https://my.retool.com/ Create an account 
 2. A  license key is displayed
 3.  Look for Local machine --> Copy and run the script on GitHub CodeSpace.

     The software get installed in:  **~/retool/retool-onpremise**

