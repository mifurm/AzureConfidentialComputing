# Known Issues 😈
These are the currently known issues with the lab.

## Missing instructions

1. Deploying and testing Python app to store logs in Confidential Ledger
2. Attemping exploits using SQL Extended Events

## Configuration

1. Encrypting columns in the database (L04-02) breaks the ASP.NET web app - likely that it cannot access the enclave key in the HSM

## ASP.NET App

1. Bug in the ASP.NET app when sliding the salary filter control - clicking works

## Cleanup

1. I had a problem deleting a confidential ledger resource "internal server error" in portal and cli - needed PG to update before I could delete
2. Need to add correct permissions to allow purging the Managed HSM