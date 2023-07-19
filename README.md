# LowCodeAppGeneration
Repository to test available Low Code app generation tools using **GitHub Codespaces.**

# App generation platforms I am evaluating:

 - BuideBase : https://budibase.com/ 
 - Retool: https://retool.com/

# Quick Comparision

|                                                                                           |     | BudiBase                                  | Retool                                                                         |   |   |   |
|-------------------------------------------------------------------------------------------|-----|-------------------------------------------|--------------------------------------------------------------------------------|---|---|---|
| Mobile App Generation                                                                     |     | No                                        | Yes                                                                            |   |   |   |
| Hosting Locally                                                                           |     | Yes                                       | Yes                                                                            |   |   |   |
| Use Docker-Compose                                                                        |     | Yes                                       | Yes, See note 1 on how I install Retool GitHub CodeSpace                       |   |   |   |
| Buit-in Database to store data. This is good for an app which does not use existing data. |     | Yes Budibase DB is the native datasource. | Yes Retool DB is a PostgreSQL with a spreadsheet-like interface to manage data |   |   |   |
| Connection to external Databases. This is a must for an which uses existing data          |     | Yes                                       | Yes                                                                            |   |   |   |                                                                                                         |   |   |   |


**Note 1:** 

 1. Goto https://my.retool.com/ Create an account 
 2. A  license key is displayed. Copy this. This is required in the next step
 3.  I used the steps in Deploy Retool with EC2 : https://docs.retool.com/docs/deploy-with-aws-ec2
 4. Use a 4-core • 8GB RAM • 32GB GitHub CodeSpace instance. Retool is beefy :-)
 5. Retool app will be available on Port 3000
