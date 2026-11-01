---
title: "Digital Emblems - Use Cases and Requirements"
abbrev: "DIEM Use Cases and Requirements"
category: info

docname: draft-ietf-diem-requirements-latest
submissiontype: IETF  # also: "independent", "editorial", "IAB", or "IRTF"
number:
date:
consensus: true
v: 3
area: "Applications and Real-Time"
workgroup: "Digital Emblems"
keyword:
venue:
  group: "Digital Emblems"
  type: "Working Group"
  mail: "diem@ietf.org"
  arch: "https://mailarchive.ietf.org/arch/browse/diem"
  github: "ietf-wg-diem/diem-requirements"
  latest: "https://ietf-wg-diem.github.io/diem-requirements/draft-ietf-diem-requirements.html"

author:
  -
    fullname: Rahel A. Fainchtein
    organization: JHU/APL
    email: rahel.fainchtein@jhuapl.edu

  -
    fullname: Felix Linker
    email: linkerfelix@gmail.com

  -
    fullname: Alex Rosenberg
    organization: Veridigo
    email: alexr@veridigo.com

  -
    fullname: Casey Deccio
    organization: Brigham Young University
    email: casey@byu.edu

  -
    fullname: Allison Mankin
    organization: Packet Clearing House
    email: allison@pch.net

contributor:
  -
    fullname: Bill Woodcock
    organization: Packet Clearing House
    email: woody@pch.net

  -
    fullname: Jim Reid
    organization: RTFM llp
    email: jim@rfc1035.com

  -
    fullname: Samit D'Cunha
    organization: International Committee of the Red Cross
    email: sdcunha@icrc.org

  -
    fullname: Natasha Chabbra
    organization: Australian Red Cross
    email: nchabbra@redcross.org.au

normative:
  CHARTER:
    target: https://datatracker.ietf.org/doc/charter-ietf-diem/01/
    title: Digital Emblems
    date: 2025-05-27

informative:
  API1977:
    target: https://ihl-databases.icrc.org/assets/treaties/470-AP-I-EN.pdf
    title: "Protocol Additional to the Geneva Conventions of 12 August 1949, and relating to the Protection of Victims of International Armed Conflicts (Protocol I)"
    author:
       org: International Committee of the Red Cross
    date: 1977-06-08
  APIII2005:
    target: https://ihl-databases.icrc.org/assets/treaties/615-AP-III-EN.pdf
    title: "Protocol Additional to the Geneva Conventions of 12 August 1949, and relating to the Adoption of an Additional Distinctive Emblem (Protocol III)"
    author:
       org: International Committee of the Red Cross
    date: 2005-12-08
  BLUEHELMET:
    target: https://guide-humanitarian-law.org/content/article/3/peacekeeping/
    title: The Practical Guide to Humanitarian Law
    author:
       org: Doctors Without Borders
  BLUESHIELD:
    target: https://www.unesco.org/en/heritage-armed-conflicts/enhanced-protection-cultural-property-highest-importance-humanity
    title: Enhanced Protection - Cultural Property of Highest Importance to Humanity
    author:
       org: United Nations Educational, Scientific and Cultural Organization
  REDCROSS:
    target: https://www.icrc.org/en/doc/assets/files/other/protection_emblems.pdf
    title: The Protection of the Red Cross / Red Crescent Emblems
    author:
       org: International Committee of the Red Cross
  RCRCRES:
    target: https://rcrcconference.org/app/uploads/2024/10/34IC_R2-ICT-EN.pdf
    title: Protecting Civilians and Other Protected Persons and Objects Against the Potential Human Cost of ICT Activities During Armed Conflict
    author:
       org: 34th International Conference of the Red Cross and Red Crescent
    date: 2024-10
    seriesinfo:
      - Document prepared by the International Committee of the Red Cross in consultation with the International Federation of Red Cross and Red Crescent Societies
  UNESCORES:
    target: https://unesdoc.unesco.org/ark:/48223/pf0000396721.locale=en
    title: Resolutions Adopted During the 16th Meeting of the High Contracting Parties to the 1954 Hague Convention
    author:
       org: United Nations Educational, Scientific and Cultural Organization
    date: 2025-12-01
  PRESS:
    target: https://safety.rsf.org/appendix-i-protection-of-journalists-in-war-zones/
    title: RSF Resource for Journalists' Safety
    author:
       org: Reporters Without Borders
  DIPLOMAT:
    target: https://www.law.cornell.edu/cfr/text/19/148.83
    title: Personnel of Foreign Governments and International Organizations and Special Treatment for Returning Individuals
    author:
       org: Cornell Law School - Legal Information Institute
  GCI1949:
    target: https://ihl-databases.icrc.org/assets/treaties/365-GC-I-EN.pdf
    title: "Geneva Convention for the Amelioration of the Condition of the Wounded and Sick in Armed Forces in the Field"
    author:
       org: International Committee of the Red Cross
    date: 1949-08-12
  HAGUE1954:
    target: https://unesdoc.unesco.org/ark:/48223/pf0000082464
    title: Convention for the Protection of Cultural Property in the Event of Armed Conflict
    author:
       org: United Nations Educational, Scientific and Cultural Organization
    date: 1954-05-14
  RAMSAR:
    target: https://www.ramsar.org
    title: The Convention on Wetlands
    author:
       org: Convention on Wetlands Secretariat
  ISPM15:
    target: https://www.ippc.int/static/media/files/publication/en/2019/02/ISPM_15_2018_En_WoodPackaging_Post-CPM13_Rev_Annex1and2_Fixed_2019-02-01.pdf
    title: "International Standards for Phytosanitary Measures No. 15: Regulation of Wood Packaging Material in International Trade"
    author:
       org: International Plant Protection Convention, Food and Agriculture Organization of the United Nations
  UNMODELREGS:
    target: https://unece.org/transport/dangerous-goods/un-model-regulations-rev-23
    title: "UN Model Regulations on the Transport of Dangerous Goods"
    author:
       org: United Nations Economic and Social Council
  HARMONIZED:
    target: https://www.wcotradetools.org/en/harmonized-system
    title: "Harmonized System"
    author:
       org: World Customs Organization
  VIENNACONV:
    target: https://treaties.un.org/pages/Viewdetails.aspx/?src=TREATY&mtdsg_no=III-3&chapter=3&clang=en
    title: "Vienna Convention on Diplomatic Relations"
    author:
       org: United Nations
  CUSTOMARY:
    target: https://ihl-databases.icrc.org/en/customary-ihl
    title: "Customary IHL - IHL Databases"
    author:
       org: International Committee of the Red Cross
  IHL-GUIDE:
    target: https://guide-humanitarian-law.org/content/article/3/right-of-humanitarian-initiative/
    title: ""
  WHITEFLAG:
    target: https://standard.whiteflagprotocol.org/
    title: "Whiteflag Specification"
    author:
      org: Whiteflag Foundation


--- abstract

Digital emblems allow an issuer to signal that an asset should be protected or treated in a specific way,
using some normative framework.
This document lists the requirements and use cases that an architecture for digital emblems must accommodate.

--- middle

# Introduction

Digital emblems allow an issuer to signal to validating entities that an asset should be protected or treated in a specific way, using some normative framework.
The DIEM WG will define a set of standards for an architecture that enables discovery and validation of digital emblems.
This document lists the requirements that the architecture must accommodate.
These requirements were identified across different use cases.
Not all use cases share all requirements.
We envision an architecture comprising multiple standards, which can be flexibly profiled for different use cases.

# Conventions and Definitions {#defs}

{::boilerplate bcp14-tagged}

The definitions for the terms "(digital) emblem" and "validation" are reproduced from the charter {{CHARTER}} as of this writing.


(Digital) Emblem:
: Emblems such as the Red Cross, Red Crescent, Red Crystal, and Blue Shield can be symbols of protection governed by International Humanitarian Law (IHL).
  Emblems can also be identified by other laws, agreements, or standards.
  There is a need to present emblems through digital communication channels.
  Emblems presented in such ways are called digital emblems.
  Digital emblems extend the range of identifying marks from the physical (visual and tactile) to the digital realm.

Asset:
: A physical resource - such as a place or thing - or a digital resource, system, or service - such as a server, data repository, or networked device - that can be marked with a digital emblem.

Emblem issuer:
: The entity that issues a digital emblem.
  Depending on the applicable emblem, the issuer may have received authorization to issue emblems, and in such cases, emblem issuers are also called *authorized entities*.
  For example, emblem issuers could be a medical or humanitarian organization, a cultural institution, or an operator of installations containing dangerous forces, among others.

Authorizing entity:
: An entity competent to grant authorization for the use, by an authorized entity, of a digital emblem.
  The authorizing entity ensures that such authorization is issued and recorded in accordance with applicable legal requirements, enabling validation.
  In certain specific cases, the authorizing entity is also the authorized entity.

Validator:
: An entity that seeks to determine whether an asset is marked with a valid digital emblem.
  Validators may include technical systems, network operators, or other actors.

Digital emblem profile:
: A specification for a digital emblem design addressing one or more use cases.
  Will include a specifcation of an emblem's data elements, what type each has, which are required or confidential, how validators interpret them, etc.
  A profile also states how emblems are discovered and whether it requires validation or authorization mechanisms.

Validation:
: "To validate an emblem" means to confirm the authenticity or legitimacy of a particular digital emblem.
  Validation can be performed by cryptographic checks, e.g., signature verification, by using domain-specific knowledge, or by following particular business processes.
  Validation may include ensuring that the emblem has not been forged, stolen, or tampered with.

# Requirements

The DIEM architecture will allow validators to discover and validate digital emblems that are associated with assets. This section contains the requirements that this architecture will address. They are based on use cases identified thus far (see {{use-cases}}), but note that not all use cases share all requirements. We categorize these requirements into: requirements on digital emblems and their format, on their discovery, on their validation, and other requirements.

The requirements for individual use cases are independent, and the requirements for one use case MUST NOT constrain, override, or otherwise affect the requirements of any other use case.
Where a use case specifies a limited domain of application for a particular emblem (e.g. only digital or physical assets, a narrow scope of valid issuers or validators, or a specific discovery mechanism), such a limitation SHOULD be understood as reflecting current use case constraints only.

Drafts will likely address a subset of the requirements set out in this document, and there will likely be different digital emblem profiles, each of which will address one or more use cases.
Whenever a profile addresses one use case's requirement, this must not be interpreted as that profile inheriting all limitations of the respective use case.
Future or different drafts and profiles should be able to reuse any draft or parts thereof, in particular, when an addressed use case has a different or expanded domain of application.

## Digital Emblem Requirements

### Digital Emblem Format

Digital emblems MUST identify the marked asset and what kind of emblem they resemble.
Beyond that, digital emblems MAY include other data, for example, an issuer or a validity window.
To accommodate use cases requiring extensible data, a digital emblem architecture SHOULD introduce minimal size overhead except for fields required to fulfil other requirements in this document.

As of this writing, the DIEM charter requires that digital emblems MUST explicitly identify the marked asset by a Fully Qualified Domain Name (FQDN).

### Emblem Semantics

Digital emblem profiles MUST specify the semantics of the emblem. It must be clearly stated how discovery and validation of a digital emblem should inform validator behavior.

## Discovery Requirements

### Discovery

Digital emblem profiles MUST specify how validators, given an asset, can check for the presence of a digital emblem.
For example, verifying whether an FQDN has an emblem associated with it could be realized by fetching digital emblem-associated records for that FQDN.

### Query Response {#response-reqs}

Digital emblem profiles MUST determine how servers must respond to queries for digital emblems.
Specifically, they must determine the responsiveness and consistency requirements for emblems and
provide explanations of how the chosen requirements apply and the rationales for their selection.

For responsiveness, a digital emblem profile can either require that all queries must be responded to (Assured Response), or can allow for selectively responding to a subset of incoming queries (Selective Response).

For consistency of response, digital emblem profiles must denote whether all queries for an
asset's records (as denoted by its FQDN) must return all respective digital emblems associated with the
asset (Consistent Content), or whether the inclusion of emblems in a response may vary based on specific requester attributes (Selective Content).

Note that as of this writing, neither the baseline definition for the minimum set of attributes that constitute a unique digital
emblem nor the attributes needed to attain Consistent Content have been defined.
Given the limited scope of this document, that definition as well as the mechanism to ensure its extensibility across
newly defined emblem profiles will be outlined in the architecture document.


### Removable {#removable}

Some use cases require that digital emblems are removable.
"Removing" an emblem means that one cannot determine whether an emblem ever was applied to a particular asset.
This means, in particular, emblems do not count as removed when they become invalid, e.g., due to expiry.

Note that removability is a security requirement.
Therefore, digital emblem profiles and drafts that address removability MUST specify a threat model for removability that specifies when and under what conditions it is acceptable that someone can learn after the fact that an emblem was applied.

### Undetectable Validation {#undet-validation}

Some use cases require that digital emblem discovery and validation are undetectable.
This requirement is motivated by emblems that mark their assets as protected and ask validators to not disrupt the marked asset.
If emblem discovery were detectable, malicious parties could misuse the digital emblem as an intrusion detection system.

For specific digital emblem profiles, it may be acceptable that certain parties can detect emblem discovery and validation, for example, when the validator can hide in a sufficiently large anonymity set, or it is acceptable that the given party could detect the discovery or validation.
Digital emblem profiles and drafts MUST specify a threat model for undetectable validation.
This threat model must detail which parties can detect emblem discovery and validation, under which conditions, and to what extent.

## Validation Requirements

### Validation {#validation}

Some use cases require that digital emblems be validated.
When a profile specifies validation procedures, those procedures MUST ensure that the emblem was issued for the respective asset.
Some use cases MAY use unvalidated digital emblems.

The digital emblem architecture MUST allow individual profiles and drafts to support validation of all the digital emblem's data or a defined subset.
This ensures digital emblems can support static or dynamic data without having to account for the pain of frequent re-signing of dynamic data if its validation is not required by a given digital emblem profile.

### Authorization {#authorization}

For some use cases, issuing a digital emblem requires authorization by third parties.
When a digital emblem profile requires authorization, it MUST define a trust model that describes how validators can discover authorities and how the system selects authorities.
The generalized digital emblem architecture MUST NOT assume that Internet access is available or required so that individual digital emblem profiles can choose to take a dependency on Internet access or not.
For example, a given digital emblem profile MAY use a PKI or the DNS as a root of trust if desired, but the generalized digital emblem architecture cannot mandate this or other options and MUST make this a point of extensibility.

Any authorization mechanism MUST account for the possibility of compromise of cryptographic key material, for example, by specifying revocation mechanisms or using short-lived credentials.

## Other Requirements

### Extensibility

The digital emblem architecture should be extensible.
The initial work should not preclude future extensions, and individual standards should be designed to be as general as possible.

# Extensions

In this section, we sketch how the digital emblem architecture could be extended by future standards to accommodate more use cases, but it is not a comprehensive list.

## Data Formats

Emblems for additional use cases may be defined via new profiles in future standards, potentially including new types of atomic data elements requiring additional specification.

## Asset Identifier Discovery

It may be non-obvious for some use cases to learn the identifiers associated with an asset, and thus impossible to discover emblems associated with that asset.
To accommodate such use cases, one could specify means to discover identifiers for different types of assets.

## Implicit Discovery

An alternative approach to the above problem would be to bind emblems implicitly to the marked asset.
Implicit binding could identify the marked asset by the emblem's location.
For example, if emblems were distributed via NFC, the marked asset could be the asset to which the NFC chip was attached.
As of this writing, the current charter scope requires that digital emblems explicitly identify their asset, but such discovery mechanisms could be investigated in future WG work.

## Confidentiality

Some use cases may contain confidential or sensitive data, and may require mechanisms to protect such data.
For example, this could be realized with encryption of the general emblem data format that will be part of the architecture or by only serving emblems over channels with access control mechanisms.

## Proof of Presence {#proof-pres}

Since emblems themselves are unable to directly protect assets against attack, emblems which indicate that assets are entitled to protections may require a mechanism through which violations of their laws or provisions can be verified forensically.
This would be particularly relevant in cases where emblems can be applied and removed dynamically.
These proofs of presence are defined at three different levels, listed from weakest to strongest.

Level 1 - presence and validation possible: Establishing that a validator was able to obtain the emblem at the
time of violation. That is, forensically demonstrating or proving that the emblem was discoverable and could be validated at the
time of an alleged violation.

Level 2 - presence, validation possible, and access: Establishing Level 1 and additionally that the validator accessed the digital emblem.

Level 3 - presence, validation possible, access, and validation: Establishing Level 2 and that the validator validated the emblem upon accessing it. This level of proof can only be provided by the validator.

Note that Levels 2 and 3 are intended to be mutually exclusive requirements with undetectable validation ({{undet-validation}}).
An example from the Diplomatic Pouches use case, described in {{diplo-pouch}}, illustrates the
Level 3 proof of presence requirement, and how it in some cases may need to be part of a chain of custody and/or
 accompanied by additional security measures to provide adequate security guarantees.


{:aside}
> Level 1 proof of presence could be available to the validator without violating undetectable validation ({{undet-validation}}).
> However, making Level 2 proof of presence available to the asset, emblem issuer, or authorizing entity would violate that requirement.


# Use Cases {#use-cases}

Different use cases have different requirements.
The purpose of this document is to list the requirements that will be addressed with the initial architecture.
The use cases overlap and would benefit from a DIEM architecture developed to provide the requirements listed above, though some may require additional extensions.
We alphabetically list use cases here so that relevant stakeholders can provide input on whether their use case would indeed benefit from a DIEM architecture, and invite participants to provide use cases or details that we have missed.

We provide auxiliary material under Informative References.

## Basel Convention

Regulates the trans-boundary movement of hazardous wastes. Use cases are functionally identical to OPCW and IAEA.

## Diplomatic Pouches (1961 Vienna Convention on Diplomatic Relations) {#diplo-pouch}

Digital emblems can protect diplomatic pouch shipments, diplomatic couriers, and diplomatic envoys.
All three of these are protected
under the 1961 Vienna Convention on Diplomatic Relations {{VIENNACONV}}, which states that they may not be stopped, delayed, or
inspected. This creates the paradox that the validity of their credentials must be evaluated, yet doing so has
historically compromised the very rights that are intended to be signaled. Diplomatic markings have also been
misappropriated as cover for the smuggling of drugs and other contraband. Digital emblems, which can be validated
instantaneously, at a distance, and without interrupting the subject, address both of these problems, while streamlining
and automating customs and immigration processes.

The use case for diplomatic pouches involves the following entities:
- Point of Entry Country/Customs Agent(s): Validator
- Origin Country or Accredited Organization: Issuer and Authorizing entity
- Diplomat: Agent of Country or Accredited Organization
- Pouch: Asset

As noted in Section {{proof-pres}}, a Level 3 proof of presence record could help demonstrate, for the benefit of the customs service, that customs agent(s) in a point of entry country validated the diplomatic pouch.
To that end, the proof of presence record of processing a diplomatic pouch's digital emblem could include the following information.

- Specific point of entry
- Time/Date of arrival at point of entry
- Identifier(s) of customs agent(s) validating the pouch
- A baseline record establishing the emblem's existence and accessibility (or a pointer thereto)
- Record of the customs agent's attempt to validate the digital emblem and its result signed by the customs agent(s)


### Limitations of proof of presence:

As indicated in Section {{proof-pres}}, Level 3 proof of presence alone does not provide proof that
no tampering with the diplomatic pouch or inspection of its contents has occurred.
This is because a proof of presence neither provides a chain of custody nor any mechanisms to detect
tampering should it occur. For this reason, Level 3 proof of presence may be used alongside or as part of an attested
chain of custody and/or accompanied by the use of physical mechanisms for tamper-proofing a physical asset.
Any such chain of custody specification or anti-tampering mechanism is out of the scope of the DIEM WG.



## International Atomic Energy Agency (IAEA)

IAEA administers several treaties, especially related to the controlled shipment of atomic fuels and wastes across borders.
Similar use case as OPCW.

## International Civil Aviation Organization (ICAO)

Requires protection of civil aviation flights and the ability to assert that they are not dual-use (i.e., not carrying military cargo).
Digital emblem would carry a geographic description of the flight plan, its current location, and an indicator of its identity (i.e., tail number).
Potential need for the emblem to reference a limited or partially redacted flight manifest.

## Protective Emblems under the Geneva Conventions, their Additional Protocols, and the 1954 Hague Convention

### Background

The Geneva Conventions and their Additional Protocols constitute the core of International Humanitarian Law (IHL).
Some assets enjoy certain specific protections under IHL, including that they must not be attacked. In addition to recognizing other signs, IHL codifies four types of protective emblems for armed conflict, which inform other parties that marked assets benefit from one or several of these specific or special protections.
In other words, protective emblems under IHL signal the applicability of a specific or special protection under IHL.
Namely, these emblems are:

- The emblems of the Red Cross, Red Crescent, and Red Crystal, defined in the Geneva Conventions and Additional Protocol III of the Geneva Conventions {{GCI1949}} {{APIII2005}}
- The Blue Shield emblem, defined in the 1954 Hague Convention {{HAGUE1954}}
- The international distinctive sign of civil defence, defined in Additional Protocol I of the Geneva Conventions {{API1977}}
- The dangerous forces special sign, defined in Additional Protocol I of the Geneva Conventions {{API1977}}

However, these emblems can currently only be used to mark physical assets, and there is no way to mark digital, network-connected infrastructure that enjoys the same protections.
A digital emblem using the DIEM architecture could address this gap, and resolutions from UNESCO and the International Conference of the Red Cross and Red Crescent have expressed support for such a digital emblem {{RCRCRES}} {{UNESCORES}}.

### Domain Model and Stakeholders {#ihl-stakeholders}

In the context of digital protective emblems under IHL, emblems will mark assets that are digital services and that solely serve protected purposes (for example, a medical unit, a cultural site, or an installation containing dangerous forces).
Such emblems will be issued by the party controlling the marked service, and they signal that these assets must be respected and protected.
Emblems must only be issued by entities that have been authorized to bear a digital emblem or other distinctive sign under international law.
Such authorizations must be issued by a state, other party to an armed conflict, or other entity competent under international law.

For digital protective emblems under IHL, validators will typically be armed forces under the command of either state or non-state actors.
In situations of armed conflict, all such actors are under an obligation to check whether assets subject to military activities bear an emblem.
Similarly, other cyber operators, whilst not necessarily obligated under IHL, may choose to respect assets bearing the emblem.
Concretely, we can assume that they will typically first identify an asset that they plan to engage with and then check whether that asset bears an emblem.

### Requirements

The purpose of a digital emblem is to prevent disruptions of assets by informing validators that marked assets enjoy protection under IHL.
Digital emblems will only be able to do so when validators are willing to pay attention to them.
As validators intend to engage with assets that are not protected under IHL, this will only be the case when they are confident that their targets cannot fake protection and that they do not alert their target.
Therefore, digital protective emblems under IHL require validation for authenticity ({{validation}}) that is undetectable ({{undet-validation}}).

At the same time, digital protective emblems under IHL should fit well into the existing framework of IHL and not put emblem issuers at increased risk.
First, IHL requires that emblem issuers must seek authorization from a competent authority prior to issuing emblems (see {{authorization}} and {{ihl-stakeholders}}).
The authorization must be decentralized, i.e., there must be no central authorities that govern the use or distribution of digital emblems.
Second, bearing an emblem can increase the risk of targeted attacks.
We require that emblem issuers must be able to individually assess that risk and remove emblems whenever they see the risks as outweighing the benefits, i.e., we require that digital emblems are removable ({{removable}}).

Beyond the DIEM architecture as described in this document, digital protective emblems under IHL would benefit from discovery mechanisms other than the DNS, as not all assets may have domain names associated with them.

## Organization for the Prohibition of Chemical Weapons (OPCW)

Emblem would include the UN packaging symbol, and identify the UN Packaging Code, Proper Shipping Name, four-digit UN hazardous material identification number, GHS Class 6.1 Toxic Substances pictogram, any other applicable GHS pictogram, the Chemical Abstracts Service registry number, the IUPAC chemical name, the quantity, and Consignee and Consignor details.
In addition, the place, date, and volume of production may be required.
The OPCW also employs diplomatic pouches for its equipment, and its staff are protected in the same way as couriers or diplomats while on mission.

## Other IHL-related use cases

Many organizations use recognizable insignia or logos to mark staff, vehicles, buildings, and materials that derive protection from IHL and Customary IHL {{CUSTOMARY}}.
Most humanitarian medical international non-governmental organizations (NGOs) use their own logos rather than using the Red Cross or Red Crescent emblem, even when they would have authorization to do so.

As humanitarian NGOs have a "right of initiative" {{IHL-GUIDE}} established by IHL, and many NGOs have been operating for years in a location before conflict breaks out, their presence is natural and they are often first to provide medical care.
Customary IHL requires combatants to provide the same protection to a marked hospital or identified medical staff as they would to those marked with a Red Cross or Red Crescent, provided the combatant reasonably understands that the mark is associated with a humanitarian medical function.
Community acceptance of unarmed humanitarian staff requires awareness of their presence and identity, whether in time of conflict or in time of peace.

IHL generally requires combatants to limit the impact on civilians and infrastructure that civilians rely on.
For example, destroying an electrical substation that serves a hospital and serves no military function is usually prohibited by IHL.
Other types of infrastructure important to civilians include drinking water reservoirs, water towers, and gas lines.
Likewise, schools and elder care facilities usually contain a high concentration of civilians.
Digital emblems could be defined to identify such civilian infrastructure.
The Whiteflag Protocol {{WHITEFLAG}} specifically identifies several categories of infrastructure.

## Press

Journalists in conflict zones use protective markings that indicate their status as non-combatants.
Assets belonging to the press, such as cameras and satellite terminals, could be digitally marked, and protective markings in conflict zones could be digitized.

## Ramsar Convention on the Wetlands

The Convention on Wetlands of International Importance especially as Waterfowl Habitat "provides the single most global framework for intergovernmental cooperation on wetland issues" and it features a list of geographic areas designated by Member States.
A digital emblem for the geographic areas potentially requires

* Indication of location
* Access to presence or absence of Ramsar designation of a specified location
* Textual description
* Ability to validate the presence or absence of Ramsar designation


## United Nations Economic and Social Council (ECOSOC)

UN Model Regulations {{UNMODELREGS}} includes "Recommendations on the Transport of Dangerous Goods."
This includes labeling of items with a four digit "UN Number" that indicates the comounds contained within, such as chemicals, explosives, flammable liquids, etc.
For example, items containing lithium-based batteries are labeled with 3480 or 3481 and accompanied by a specific "battery mark" emblem.


## United Nations Food and Agriculture Organization (FAO)

Among other things is responsible for the International Plant Protection Convention (IPPC) and International Standards for Phytosanitary Measures standards including ISPM 15 that requires wood packaging materials (pallets, crates, dunnages) to be debarked, heat-treated or fumigated with methyl-bromide, and stamped or branded with a compliance mark known as a "wheat stamp."

## United Nations Peacekeepers

Peacekeepers' blue helmets may require protective marking in a theater for the duration of a deployment, or may be more specifically and individually located using GPS and dynamic DNS, as with shipments of sensitive goods, diplomatic pouches, and couriers and envoys.
The `invalid_treatment` flag could be used in conjunction with the `contact` TXT record to report strays.
Barracks and other facilities can be denoted using polygonal LOC records for the TIME of their use.

## World Customs Organization (WCO)

Specifies "Harmonized Systems" codes {{HARMONIZED}} that classify items such as livestock, arms and ammunition, chemicals, plastics, machinery, foodstuffs, etc.
They also provide a system for labeling origin of items and valuation of items, all enforced by numerous international trade agreements between individual nations and groups of nations.

## World Health Organization (WHO)

Similar to the use case of the Red Cross, Red Crystal, and Red Crescent.


## World Intellectual Property Organization (WIPO)

WIPO administers 26+ treaties with different protections for different things.
Brands that are protected under international law (e.g., Madrid Protocol) can mark their shipments with an emblem allowing customs agents to positively identify legitimate products.


# Security Considerations

Many of the requirements defined in this document have security implications: in particular, query response ({{response-reqs}}), removability ({{removable}}), undetectable validation ({{undet-validation}}), validation ({{validation}}), and authorization ({{authorization}}).
The DIEM architecture and respective standards will include discussions of desired security guarantees and respective threat models.
For example, in a use case where removability is needed, there are security considerations such as the potential for replay of removed emblems.
Similarly, for emblems that require validation or authorization, specifications will discuss falsified presentation of emblems.

Moreover, there may be use-case-specific risks.
Some emblems convey that a marked asset has specific rights or a specific status by law, convention, or agreement.
As with physical emblems, the presence of a digital emblem exists to inform; it does not ensure that the corresponding rights or status will be respected by those who are privy to the emblem.
In some cases, the presentation of an emblem may even result in a greater likelihood of attack.
Specifications that address specific use cases should consider such use-case-specific risks and their consequences.

# IANA Considerations

This document has no IANA actions.

--- back

# Acknowledgments
{:numbered="false"}

Brian Haberman and Bill Woodcock created an early version of a use cases and requirements document, from which this draws ideas.
We also thank Eric Vynke, Suresh Krishan, Antonio DeSimone, Nick Doty, Tommy Jensen, and Michael Christie for their valuable input.
