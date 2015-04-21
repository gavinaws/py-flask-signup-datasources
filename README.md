<<<<<<< HEAD
# py-flask-signup-datasources

Uses a CloudFormation Ruby DSL, [cloudformation-ruby-dsl](https://github.com/bazaarvoice/cloudformation-ruby-dsl), to build an AWS CloudFormation template to deploy the data sources, including MySQL server, SNS, SQS and Liquibase required for Python Flask Startup Signup application

## Usage
To build a template run:

	make template

This will create a JSON CloudFormation template flask-signup-datasources.template

To validate a template run:

	make validate

This will run the AWS CLI cloudformation validate-template action on the flask-signup-datasource.template file using the CloudFormation API of the local region

To clean up:

	make clean

=======
# py-flask-signup
This Python sample application uses the [Flask](http://flask.pocoo.org/) framework and [Bootstrap](http://getbootstrap.com/) to build a simple, scalable customer signup form that is deployed via [AWS Elastic Beanstalk](http://aws.amazon.com/elasticbeanstalk/) or [AWS CloudFormation](http://aws.amazon.com/cloudformation/). The application stores data in [Amazon RDS MySQL](http://aws.amazon.com/rds/), or optionally can use [Amazon DynamoDB](http://aws.amazon.com/dynamodb/), and publishes notifications to the [Amazon Simple Notification Service (SNS)](http://aws.amazon.com/sns/) when a customer fills out the form.

## Features

### Themes
The code includes several Bootstrap themes from [bootswatch.com](http://bootswatch.com/). You can dynamically change the active theme by setting the THEME environment variable in the [Elastic Beanstalk Management Console](https://console.aws.amazon.com/elasticbeanstalk) or setting OS environment variables imported by web server.

![](misc/theme-flow.png)

Installed themes include:

* [amelia](http://bootswatch.com/amelia)
* [default](http://bootswatch.com/default)
* [flatly](http://bootswatch.com/flatly)
* [slate](http://bootswatch.com/slate)
* [united](http://bootswatch.com/united)

### Flask Debugging
Similar to themes, you can control Flask debugging by toggling the FLASK_DEBUG env var from the [Elastic Beanstalk Management Console](https://console.aws.amazon.com/elasticbeanstalk) or setting an OS environment variable imported by web server.
>>>>>>> 77b5241652623832b87a583d4b6b0b9c3a94dc47
