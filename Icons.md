# ApiGateway (classic)

aws.apigateway.api                      - existing: aws logo for API Gatway

aws.apigateway.stage                    - is currently same as aws.apigateway.api: prefer something indicating it is refering to one stage like PRODUCTION or TEST

aws.apigateway.resource                 - is currently same as aws.apigateway.api: prefer something you find at the end of a path you follow few branches

aws.apigateway.method                   - prefer something that says HTTP (it would be good to have different ones for GET/PUT/POST/DELETE/HEAD/OTHER)

aws.apigateway.method.http.integration  - is currently same as aws.apigateway.api: something like a target (like used in events)

# ApiGateway V2:
aws.httpapi.api                         - same as aws.apigateway.api (maybe for the http ones we could add v2 somewhere?)

aws.httpapi.stage                       - same as aws.apigateway.stage (maybe for the http ones we could add v2 somewhere?)

aws.httpapi.route                       - not yet

aws.httpapi.integration                 - not yet

# Autoscaling
aws.autoscaling                         - existing aws logo

# Cloudformation
aws.cloudformation.stack                - existing aws logo

aws.cloudformation.stackset             - not yet - set of stacks

# DynamoDB
aws.dynamodb.table                      - existing aws logo

aws.dynamodb.stream                     - existing books falling? maybe generic stream symbol to be reused

aws.dynamodb.globaltable                - not yet

aws.dynamodb.kinesisstream              - not yet

aws.dynamodb.globalindex                - not yet

aws.dynamodb.localindex                 - not yet

# EC2
aws.ec2                                 - current logoaws logo, I like the square chip, compute background is orange gradient

aws.security-group                      - icon

aws.subnet                              - icon, indicates failover network parts, usually 3, A/B/C

aws.vpc                                 - icon, indicates network private

aws.vpngateway                          - gateway one entry multiple exits

# ECS
aws.ecs.cluster                         - existing, aws logo (maybe with chip)

aws.ecs.task                            - existing

aws.ecs.service                         - existing

# ELB (classic)
aws.elb_classic                         - existing

# ELV V2
aws.elb_v2                              - existing

aws.elb_v2_target_group                 - existing

aws.elb_v2_target_group_instance        - existing

# Events
aws.events.bus

aws.events.rule

aws.events.rule-schedule

aws.events.target

aws.events.event_source

aws.events.replay

aws.events.archive

aws.events.connection

aws.events.api_destination

# Firehose
aws.firehose                           - aws logo

# IAM
aws.iam.user

aws.iam.group

aws.iam.role

aws.iam.policy

aws.iam.instance_policy                - i like the chip, combine with policy?

# Kinesis
aws.kinesis                            - aws logo

# Lambda
aws.lambda                             - aws logo

aws.lambda.alias                       - not yet, same, prefer indicating it is an alias

aws.lambda.version                     - not yet, same, indicating it is a version (not same as alias)

aws.lambda.layer                       - not yet

# RDS
aws.rds_cluster                        - aws logo rds

aws.rds_instance                       - i like the chip

probably we will also want to show the db type here:
https://aws.amazon.com/rds/ (aurora, postgresql, mysql, orcale, sqlserver other)

# Redshift
aws.redshift                           - aws logo

# Route53
aws.route53.domain                     - icon

aws.route53.hostedzone                 - icon

# S3
aws.s3.bucket                          - aws logo

# SNS
aws.sns.topic                          - aws logo

# SQS
aws.sqs.queue                          - aws logo

# StepFunctions
aws.stepfunction.statemachine          - aws logo

aws.stepfunction.state.task            - one state of the statemachine, a leaf, there is a state it is coming from and one that it is going to

aws.stepfunction.state.branch          - not yet

aws.stepfunction.state.iterate         - not yet

aws.stepfunction.state.choice          - not yet

aws.stepfunction.state.success         - not yet

aws.stepfunction.state.failed          - not yet

aws.stepfunction.activity              - a job to execute at the state, it is in the compute layer