# [George Banco](https://www.georgebanco.com/)/[Everyday Loans](https://www.everyday-loans.co.uk/) - Trowbridge

## Contract developer
### May 2018 - August 2019

I started the contract working for George Banco but during my time they were brought into the Everyday Loans group and so my contract was also moved over. Their internal tool is a large Symfony 2.3 application that has had a lot of features bolted onto it and code rarely removed. I have been helping them to try and break down this behemoth and improve the current implementation. A lot of the older code is not using dependency injection in the manner it was designed. There are also very few unit tests and all integration testing was being done manually.

During my time I started instructing the dev team to begin to change some of the older code so that it did not always pull in the whole of the service container. The majority of the work was focusing on changing George Banco to begin to use the tools that are already being used by Everyday Loans. Additionally, I designed and implemented an OpenAPI microservice that could take payments for a loan provided by Everyday Loans, Trust Two and George Banco. This had a full suite of automated tests automatically tested using Bitbucket Pipelines. There has been a significant amount of work done on closing some security holes that were highlighted during a penetration test.

## Skills Being Used

* PHP (5.x & 7.2)
* Symphony (2.3 & 4.x)
* OpenAPI (3)
* OOP
* AWS deployment & integration
* MySQL
* TDD
* BDD

### Links

* [Back to main](/)
* Next position: [Finance company](current.md)
* Previous position: [Careplanner](careplanner.md)
