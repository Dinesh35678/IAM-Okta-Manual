# Automate Bulk User Creation Using CSV in Okta

## Steps

### 1. Login to Okta Admin Console

Login to your Okta Admin Console with administrator credentials.

### 2. Navigate to Import Option

Go to: **Directory → People → More Actions → Import Users from CSV
File**

### 3. Download and Fill Template

-   Download the CSV template.
-   Fill in the mandatory fields.
-   Ensure **username is the email ID**.

#### Sample Users

  -----------------------------------------------------------------------
  First Name  Last Name Email (Username)         Login
  ----------- --------- ------------------------ ------------------------
  John        Doe       john.doe@gmail.com       john.doe@gmail.com

  Priya       Sharma    priya.sharma@yahoo.com   priya.sharma@yahoo.com

  Arun        Kumar     arun.kumar@outlook.com   arun.kumar@outlook.com

  Meena       R         meena.r@company.com      meena.r@company.com

  Rahul       Verma     rahul.verma@gmail.com    rahul.verma@gmail.com
  -----------------------------------------------------------------------

### 4. Upload CSV File

Upload the completed CSV file into Okta.

### 5. Configure Import Settings

-   Select **Import Users**
-   Enable **Automatically activate new users**

### 6. Set Password and Activate

-   Select imported users
-   Click **Set Password and Activate**

### 7. Verify User Access

-   Login to the **End User Dashboard**
-   Use the **temporary password**
-   Verify access to applications

------------------------------------------------------------------------

## Outcome

Bulk users are successfully created and activated in Okta using CSV
import.
