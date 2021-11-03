![image](https://user-images.githubusercontent.com/71599740/140194394-8d8b8fe8-a7d6-4b2b-938e-e5b00dea3bd4.png)
# CI-_CD_Terraform  


## Requirements and Installations:
* [Node.js](https://nodejs.org/) 12.x or higher
* [Free Okta developer account](https://developer.okta.com/) for account registration, login
* Download Terraform from [terraform.io](https://www.terraform.io/downloads.html)
* Download and install [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli)
* Type `az login` and login to Azure.

## Configuration
* Use `azurerm` as a [provider](https://www.terraform.io/docs/language/providers/configuration.html).
* Create `.tfvars` file for your secret variables (for each environment):

## Basic commands
* clone the url using 'git clone'
Run the commands below:
* terraform init
* terraform fmt
* terraform validate 
* terraform apply
* it will ask you to enter password, username, and your ip address and the write "yes"
* now you will see in your azure portal your resource group with all the resources that your created.
* after you did it you can install the  Weight Tracker application in your VM'S.


# Node.js Weight Tracker

![Demo](docs/build-weight-tracker-app-demo.gif)

This sample application demonstrates the following technologies.

* [hapi](https://hapi.dev) - a wonderful Node.js application framework
* [PostgreSQL](https://www.postgresql.org/) - a popular relational database
* [Postgres](https://github.com/porsager/postgres) - a new PostgreSQL client for Node.js
* [Vue.js](https://vuejs.org/) - a popular front-end library
* [Bulma](https://bulma.io/) - a great CSS framework based on Flexbox
* [EJS](https://ejs.co/) - a great template library for server-side HTML templates


## Install and Configuration

1. Clone or download source files
1. Run `npm install` to install dependencies
1. If you don't already have PostgreSQL, set up using Docker
1. Create a [free Okta developer account](https://developer.okta.com/) and add a web application for this app
1. Copy `.env.sample` to `.env` and change the `OKTA_*` values to your application
1. Initialize the PostgreSQL database by running `npm run initdb`
1. Run `npm run dev` to start Node.js

The associated blog post goes into more detail on how to set up PostgreSQL with Docker and how to configure your Okta account.

