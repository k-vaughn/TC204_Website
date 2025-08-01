# Architecture (ISO TC 204 WG 1)

## Domain of interest

{% include "ag4/wg1doi.html" %}

## News and highlights

- [ISO/TS 14812:2025 (edition 2) _ITS Vocabulary_](https://www.iso.org/obp/ui#iso:std:iso:ts:14812) is now published.The new version includes over 70 new terms.
- ISO/PWI 25965 _ITS Ontologies - Model management_ was approved as a preliminary work item at the May TC 204 plenary meeting. This document will define how to define data for ITS uses and define how projects can register their data into a central registry to gain broader recognition.
- Based on systematic review results, WG 1 plans to update ISO 14813-5 _Requirements for architecture description in ITS standards_ to better reflect lessons learned.

## Vocabulary

??? note "[ISO/TS 14812:2025](https://www.iso.org/obp/ui#iso:std:iso:ts:14812) _Intelligent transport systems — Vocabulary_"

    **Status:** Approved

    **Abstract:** This document defines terms relating to intelligent transport systems (ITS).

    ### Description

    The definition of terms are available for free via [ISO's online browsing preview](https://www.iso.org/obp/ui#iso:std:iso:ts:14812), [ISO's online browsing platform search engine](https://www.iso.org/obp/ui/en/#home), or the [Geolexica website](https://isotc204.geolexica.org). The standard itself
    includes an annex that provides the complete concept model that graphically depicts the relationships among the terms defined in the standard.

    Edition 2 adds terms for:

    - information security (e.g., authentication)
    - concept realization (e.g., implementation)
    - device components (e.g., sensor)
    - additional alternate modes (e.g., shared-space)
    - additional road concepts (e.g., alley)
    - facilities (e.g., bridge)
    - kerbside usage (e.g., loading area)
    - additional road equipment (e.g., traffic control device)
    - additional location concepts (e.g., geographic feature)
    - jurisdictional concepts (e.g., campus)
    - additional travellers (e.g., vulnerable road user)
    - additional vehicle attributes (e.g., vehicle fuel type)
    - financial terms (e.g., payment mode)

## Reference ITS architecture

??? note "[ISO 14813-1:2024](https://www.iso.org/obp/ui#iso:std:iso:14813:-1) _Intelligent transport systems — Reference model architecture(s) for the ITS sector — Part 1: ITS service domains, service groups and services_"

    **Status:** Approved

    **Abstract:** This document provides a description of the primary services
    that have been internationally defined to promote consistency among
    implementations. Implementations can provide any of these services in
    combination with any other services that are appropriate. This document
    organizes ITS services by defining service groups, which are placed into
    one of several service domains. Each service group contains one or more
    individual services, each of which is described.

    ### Description

    This document is intended for use by at least two groups of people involved
    in the ITS sector:

    - those who are looking for ideas about the services that ITS
    implementations can provide, and
    - those who are developing International Standards.

    For the first group, this document provides service descriptions that can
    act as the catalyst for more detailed descriptions. The level of detail can
    differ from one ITS implementation to another, depending on whether or not
    a national ITS architecture is involved, and whether or not this
    architecture is based directly on services, or on groups of functions. The
    service descriptions in this document are pitched at a high-level as too
    much detail can be prescriptive and reduces flexibility.

    For standards developers, this document is applicable to Technical
    Committees who are developing International Standards for the ITS sector.
    This document is designed to provide information and explanations of
    services that can form the basis and reason for developing standards.

    Due to its nature, this document is largely advisory and informative with
    minimal requirements. It is designed to assist the integration of services
    into a cohesive reference architecture, thereby promoting interoperability
    and the use of common data definitions. Specifically, services defined within
    the service groups can be the basis for defining “use cases”, “user needs”
    or "user service requirements” depending on the methodology being used to
    develop the resultant ITS architecture functionality. They can also assist
    with defining applicable data within data dictionaries, and applicable
    communications and data exchange standards.

## Documentation in TC 204 Standards

??? note "[ISO 14813-5:2020](https://www.iso.org/obp/ui#iso:std:iso:14813:-5) *Intelligent transport systems — Reference model architecture(s) for the ITS sector — Part 5: Requirements for architecture description in ITS standards*"

    **Status:** Approved **(under revision)**{style="color: red;"}

    **Abstract:** This document defines documentation rules for standards that
    define interfaces between or among system elements of an ITS reference
    architecture. This includes:

    1. requirements for documenting aspects of the ITS reference architecture;
    2. terminology to be used when documenting or referencing aspects of the
    ITS reference architecture.

??? note "[ISO 14813-6:2017](https://www.iso.org/obp/ui#iso:std:iso:14813:-6) _Intelligent transport systems — Reference model architecture(s) for the ITS sector — Part 6: Use of ASN.1_"

    **Status:** Approved

    **Abstract:** Provides a formal means to achieve consistency in the use of
    ASN.1 when specifying data types that are to be used in ITS International
    Standards. This is designed to ensure unambiguous and interoperable data
    exchange while providing consistent documentation of these exchanges. This
    document provides the necessary specifications to ensure consistent
    interpretation by providing formal references to several standards and in
    some cases specifying additional rules to promote greater consistency among
    standards.

## Common Data Model

??? note "[ISO 14817-1:2015](https://www.iso.org/obp/ui#iso:std:iso:14817:-1) Intelligent transport systems — ITS central data dictionaries — Part 1: Requirements for ITS data definitions"
    **Status:** Approved

    **Abstract:** This document specifies the logical structure (framework) and
    the data content (substance) of intelligent transport systems (ITS) data
    dictionaries (DDs).

    Specifically, this part of ISO 14817 specifies the following:

    - framework used to identify and define all data concepts;
    - meta-attributes used to describe, standardize and manage each of the data
    concepts defined within this framework;
    - requirements used to record these definitions;
    - naming conventions for the data concepts;
    - a set of preferred data concepts within the ITS domain;
    - data modelling method for defining ITS data concepts, when used.

??? note "[ISO 14817-2:2015](https://www.iso.org/obp/ui#iso:std:iso:14817:-2) Intelligent transport systems — ITS central data dictionaries — Part 2: Governance of the Central ITS Data Concept Registry"
    **Status:** Approved

    **Abstract:** ISO 14817-2:2015 specifies the registration process to enter
    data concepts into the Central ITS Data Concept Registry (CIDCR).

    The CIDCR is designed to include data concepts that conform to ISO 14817-1.
    These data concepts may be derived from the system architecture defined in
    ISO 14813, but may also support data concepts using alternative
    International, Regional or National System Architecture methodologies or
    techniques.

??? note "[ISO 14817-3:2017](https://www.iso.org/obp/ui#iso:std:iso:14817:-3) Intelligent transport systems — ITS data dictionaries — Part 3: Object identifier assignments for ITS data concepts"
    **Status:** Approved

    **Abstract:** ISO 14817-3:2017 specifies how to assign an object identifier
    to a data concept under the "its" arc of the international object identifier
    tree.

## Application of Technologies

??? note "[ISO/TR 23255](https://www.iso.org/obp/ui#iso:std:iso:tr:23255) Intelligent transport systems — Architecture — Applicability of data distribution technologies within ITS"
    **Status:** Approved

    **Abstract:** A variety of general-purpose data distribution technologies
    have emerged within the Information and Communications Technologies (ICT)
    industry. These technologies generally provide services at the Open System
    Interconnect (OSI) session, presentation and application layers (i.e. layers
    5-7). Within Intelligent Transport Systems (ITS), these layers roughly
    correspond to the facilities layer of the ITS station (ITS-S) reference
    architecture, as defined within ISO 21217.

    This document investigates the applicability of these data distribution
    technologies within the ITS environment.
