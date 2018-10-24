# Biff Bang Pow - Oxford

## Application developer
### November 2015 to January 2018

Biff Bang Pow builds anything from small websites to larger-scale customised applications. Applications are built using Symfony or Silverstripe with Vue components on the frontend. Most of the larger projects are used as internal tools and proprietary software with as much automated integration as we could to ensure ongoing stability. Below are a few examples of clients and the type of work I have done.

## Example work

### [Amadeus](https://amadeus.co.uk)

Amadeus are SAS Training specialists and wanted to update their website and allow their end users to be able to log in and use the training materials available.

### [Pearn Kandola](https://pearnkandola.com/)

Pearn Kandola are business psychologists and they wanted to be able to mimic emails being delivered to a system and monitor response times from the users. The application needed to work even without an internet connection as they would sometimes hold their events in hotels with no internet.

This was achieved by a Symfony backend using Sonata admin to be able to deliver a JSON object to the browser that instructed the browser to "deliver" emails to a fake web e-mail client. The front end was done using VueJS that read in the main JSON object and used the time available in the browser to be able to deliver the e-mail at the right time.

### [The Glass Office People](https://theglassofficepeople.co.uk/)

The Glass Office People wanted to build a new dynamic site that included a quote calculator. They wanted to be able to set the costs of the components within the CMS so that quotes can be up to date. The calculations were taken from an Excel spreadsheet and implemented using a custom NodeJS component that was fully covered by tests using Mocha & Chai so that it was stable for any future development.

### Technologies used

* PHP (5.x & 7.2)
* Symfony (2.x & 3.x)
* Silverstripe (3.x)
* Vue (1.x)
* BDD
* OOP
* MySQL
* NodeJS
* TDD

### Links

* [Back to main](/)
* Next position: [Careplanner](careplanner.md)
* Previous position: [Kainos](kainos.md)
