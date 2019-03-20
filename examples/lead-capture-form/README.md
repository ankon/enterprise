# Example – Serverless Email Sign-Up Form

This demo application helps you test Serverless Framework Enterprise's main features:

* **Insights** - Monitoring, metrics and alerts for your functions.
* **Safeguards** - Best practice policies that run before you perform a deployment.
* **Secrets** - Store sensitive credentials in the Serverless Enterprise Dashboard and reference them in your Serverless Framework Project.

## Installation

#### Clone this repository

```shell
$ git clone https://github.com/serverless/enterprise.git
```

#### Install Front-End & Back-End Dependencies

Navigate into this example project and install dependencies on the frontend and backend.

```shell
# location - enterprise/frontend
$ npm i
```

```shell
# location - enterprise/backend
$ npm i
```

#### Create a Tenant and Application in Serverless Framework Enterprise

The Serverless Enterprise Plugin adds a `login` command to the Serverless Framework, use it like this to log you in:

```shell
# location - enterprise/backend
$ serverless login
```

Make sure to follow the prompts and create your Tenant (it's like a Github Org) and Application.

#### Add the Tenant and Application to this project's `serverless.yml`



#### Deploy the back-end

```shell
# location - enterprise/backend
$ serverless deploy
```

#### Run the front-end

```shell
# location - enterprise/backend
$ npm run start
```

## Testing Serverless Insights - Monitoring
