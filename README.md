# aws-documentdb-template
Use this template to setup documentdb on aws

## Usage Instructions:

### Variables

| Parameter            |  Type   | Description            | Default                      | Required |
| -------------------- | ------- | ---------------------- | ---------------------------- | -------- |
| ENV                  | String  | Environment            | "stage"                      | Y        |
| HostedZoneResource   | string  | Route53 Hosted Zone    | example.com                  | Y        |
| AppName              | string  | Application Name       | theawslab                    | Y        |
| DbUserName           | string  | Database Username      | admin                        | Y        |
| DbPassword           | string  | Database Password      | Password@123$                | Y        |
| DbInstanceClass      | string  | Database Instance Type | db.t3.medium                 | Y        |

## Execution Steps:

1. Goto AWS CloudFormation Console.
2. Click on Create stack with new resources
3. Specify Template >> Upload a Template >> Upload file >> Next
4. Give a Stack Name
5. Pass all the parameters
6. Click Next on Configure Stack Options
7. Review and Create Stack
