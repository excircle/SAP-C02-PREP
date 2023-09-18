# Domain 1: Development-with-AWS

This directory contains material related to Domain 1 of the AWS Certified Developer Exam.

# Task statement 1: Develop code for applications hosted on AWS

<details><summary>Architectural Patterns</summary>

## <u>Event-Driven Architecture</u>

An event-driven architecture (EDA) is an architecture pattern designed to connect service
components and enable complex systems to communicate. Event-driven architectures are
comprised of three key components:

- Event producers (Web app, mobile app, point-of-sale)
- Event brokers (AWS EventBridge)
- Event consumers (Database)

Events indicate a change in state (order placed, user created) and are passed between components
as messages with specific semantics. A producer publishes an event to the broker, which abstracts
producers and consumers from one another by allowing them to communicate asynchronously.
EDAs use events to coordinate communication between loosely coupled services

[Read More In This AWS Guide](https://d1.awsstatic.com/SMB/aws-modernization-intro-to-eda-guide-2022-smb-build-websites-and-apps-resource.pdf)

## Microservices Architecture

With a microservices approach, software is composed of
small services that communicate over well-defined application programming interfaces (APIs) that can
be deployed independently. These services are owned by small autonomous teams. This agile approach is
key to successfully scale your organization.

[Read More In This AWS Guide](https://docs.aws.amazon.com/pdfs/whitepapers/latest/microservices-on-aws/microservices-on-aws.pdf)

## Monolithic Architecture

To be written

## Choreography Architecture

To be written

## Orchestration Architecture

To be written

## Fanout Architecture

To be written

</details>
