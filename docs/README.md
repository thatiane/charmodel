# CharModel

[[TOC]]

::: tip What is the CharModel?
The **CharModel** is a model for characterization of the architecture of service-based systems. The CharModel is composed by four dimensions, inspired on the following microservices guidelines:
- Small and independent services
- Loose coupling
- Lightweight communication mechanisms
- Deployment independence
- Decentralized data management
:::

![CharModel dimensions][charmodel]

## Key Features

- Focused on the structural attributes size and coupling
- Based on static metrics, extracted from APIs and relationships
- Can be adopted in different stages of software life cycle (Design-time, Architecture mapping, Architectural evolution)
- Allows to analyze different components and perspectives, according to the interest scope

## Dimensions

The CharModel dimensions are:

  1. [Size][size]
  2. [Data Source Coupling][data_source]
  3. [Synchronous Coupling][synchronous]
  4. [Asynchronous Coupling][asynchronous]

## Practical Application Example

Access [here][pingr_characterization] to view the characterization of a system architecture generated from the CharModel adoption.

[size]: ./dimensions/size.md
[data_source]: ./dimensions/data_source.md
[synchronous]: ./dimensions/synchronous.md
[asynchronous]: ./dimensions/asynchronous.md

[pingr_characterization]: ./pingr/overview.md
