# Celebal Cloud Project

How to perform operations to create vm on Azure on terraform.

First step--
Download terraform from official site
https://www.terraform.io/downloads.html

Download Azure CLI and follow the Instructions from here
https://docs.microsoft.com/en-us/cli/azure/install-azure-cli

Then open Command line.
Navigate to this project in command line using cmd.
Then type these commands.
These commands may ask for your Azure Cloud credentials in order to work. So please provide them as asked for.


'''
az login 

terraform init

terraform plan -out out

terraform apply "out"
'''
