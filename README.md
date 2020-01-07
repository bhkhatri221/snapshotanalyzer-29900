# snapshotanalyzer-29900
Deme project to manage AWS EC2 instance

## About

This project is a demo, and uses boto3 to manage AWS EC2 instance snapshots

## Configuration

shotty uses the configuration file created by the AWS cki. e.g. 

`aws configure --profile totty`

## Running

`pipenv run "python shotty/shotty.py"`

## Running

'pipenv run "python shotty/shotty.py <command> <--project=PROJECT>"`

*command* is list, start or stop
*project* is optional