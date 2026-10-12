Mustangproject - Schematron Test
===

<b>Disclaimer</b>: This is work in progress and not recommended for production mode testing. Nor is it meant to be a template of any kind that you might want to simply copy.

About
===

This project is my private schematron test project used exclusively for verification of the invoice documents created using the ZUGFeRD / [Mustang project](http://www.mustangproject.org/) libs.

I uses the latest version of phax / ph-schematron version [10.2.0](https://github.com/phax/ph-schematron/releases) it's only a very minimal project that in fact offers no additonal work done by me - please send kudos to the original author [Philip Helger](https://github.com/phax) :-)
All of the configuration is being done via the project's pom.xml and it should be pretty self explanatory.

The main purpose of this program to be able to run a schematron verifier that doesn't have any limititations at all. Most of the providers for French e-Invoicing seem to tolerate additional data elements not in the official schema files. We had issues with documents that our provider's tests passed but these failed on the side of the receiving invoice party.

The official schemas and schematron files for Factur-X 1.09.2 - ZUGFeRD 2.5.2 can be downloaded from forum national de la facture electronique [fnfe](https://fnfe-mpe.org/factur-x/factur-x_en/) website.

License
-----

Subject to the [Apache-2.0 license](http://www.apache.org/licenses/LICENSE-2.0.html).
