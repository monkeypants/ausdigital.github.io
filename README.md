# Purpose of this site

The [Australian Digital Business Council](http://digitalbusinesscouncil.com.au/) has published an interoperability framework that aims to increase national productivity through automation of common buisness processes such as invoicing.  This site makes the framework easy to implement by providing 
* simple and readable technical specifications that are the normative reference for what to build.
* links to reference implementations that you may use to speed up your own implementation.
* links to test cases and test end-points that you can use to be sure that your implementation will work.
* links to collaboration forums and mailing lists for special interest groups that seek to leverage or extend the framework.

As an implementer you may choose to just read the information and use the tools presented here - or you may wish to participate more actively by contributing to the specification development or reference implementations.  

# Framework Overview

Unlike single provoder APIs (eg google or facebook), a B2B community needs many different systems to implement the same service interfaces (eg an e-invoicing end-point) so that any business can send any other business an invoice.  The many-to-many aspect of B2B transactions requires a few extra components in the framework as shown in the conceptual overview diagram.

![Framework Diagram](AusDigitalHomepage.png)

For any of the millions of buisnesses in an economy to be able to exchange electronic business documents with any other business:
* Buyers and sellers may have different ledger systems but they must expose access points that conforms to a common interface standard.
* Independent and trusted identity providers need to be able to confirm business identity (to avoid every business having to issue passwords to every other business)
* Electronic service end-point information needs to be discoverable via a registry because a sender system will generally know the identity of a receiver (eg ABN 1234) but not necessarily the technical data about how and where to send and electronic invoice.
* Security measures such as signatures, encryption, and notaries are essential to provide trust and reduce fraud opportunities.

The success of the interoperability framework depends on uptake by the ledger software providers. Those systems must implement a numebr of interfaces in a consistent way - which requires clear standards, good test services, and easy to use tooling.  That is the purpose of this site.

# The Specifications

There is one or more interface specifications for each of the interactions in the overview diagram.  All technical specifications are developed using the [COSS](http://rfc.unprotocols.org/spec:2/COSS/) (Consensus Oriented Specification System) governance model.  COSS ensures that any interested party can participate (because it imposes no restrictins on contributions). It also maximises consensus because, if the editor does not accept your contribution, you can always fork the specification and become the new editor (if others agree they'll follow, but if nobody else likes your fork then you'll be editor of a lonely specification that will wither on the vine).

## The Identity Provider

## The Digital Capability Locator

## The Service Metadata Publisher

## The Access Point

## The Notary

## Invocing Semantics

## Purchase Order Semantics

## Shipping Notice Semantcis

# The Special Interest Groups

Some interest groups cross multiple specifications and may have an impact on many of them but are not, in themselves, the logical owners of a particular specification.  We value the support and opinions of such groups and so we are happy to provide some collaboration tools to facilitate consultation and collaboration with such groups.  If you'd like to participate (or just watch the conversation) of a particular group then please follow the links to subscribe.

## Security Interest Group

## Trade Finance Interest Group



