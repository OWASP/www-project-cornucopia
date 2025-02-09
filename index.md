---

layout: col-sidebar
title: OWASP Cornucopia
site_side: true
tags: cc
project: true
level: 3.5
type: documentation

---

[![OWASP Production Project](https://img.shields.io/badge/owasp-production%20project-brightgreen)](https://owasp.org/other_projects/)
[![OpenSSF Best Practices](https://bestpractices.coreinfrastructure.org/projects/7125/badge)](https://bestpractices.coreinfrastructure.org/projects/7125)
[![Maintainability](https://api.codeclimate.com/v1/badges/4a7cda6ef1c2932a34f9/maintainability)](https://codeclimate.com/github/OWASP/cornucopia/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/4a7cda6ef1c2932a34f9/test_coverage)](https://codeclimate.com/github/OWASP/cornucopia/test_coverage)

![OWASP Cornucopia Website App Edition playing cards](assets/images/Cornucopia-header.jpg)

OWASP Cornucopia is a mechanism in the form of a card game to assist software development teams identify security requirements in Agile, conventional and formal development processes. It is language, platform and technology-agnostic.

## Introduction
The idea behind Cornucopia is to help development teams, especially those using Agile methodologies, to identify application security requirements and develop security-based user stories. Although the idea had been waiting for enough time to progress it, the final motivation came when [SAFECode](http://www.safecode.org/) published its [Practical Security Stories and Security Tasks for Agile Development Environments](https://safecode.org/publication/SAFECode_Agile_Dev_Security0712.pdf) in July 2012. Cornucopia was created and first used for developer training in August 2012.

The Microsoft SDL team had already published its super [Elevation of Privilege: The Threat Modeling Game](https://www.microsoft.com/en-gb/download/details.aspx?id=20303) (EoP) but that did not seem to address the most appropriate kind of issues that web application development teams mostly have to address. EoP is a great concept and game strategy, and was [published under](https://www.microsoft.com/security/blog/2010/03/02/announcing-elevation-of-privilege-the-threat-modeling-game/) a [Creative Commons Attribution License](http://creativecommons.org/licenses/by/3.0/). Cornucopia is based the concepts and game ideas in EoP, but those have been modified to be more relevant to the types of issues website app and mobile app developers encounter. It attempts to introduce threat-modelling ideas into development teams that use Agile methodologies, or are more focused on web application weaknesses than other types of software vulnerabilities or are not familiar with STRIDE and DREAD.

To start using Cornucopia:

1. Either: Obtain or buy a pre-printed deck of cards
2. Or: Download the document
   1. Print the cards onto plain paper or pre-scored card
   2. Cut/separate the individual cards
3. Identify an application, module or component to assess
4. Invite business owners, architects, developers, testers along for a card game
5. Get those infosec folk to provide chocolate, pizza, beer, flowers or all four as prizes
6. Select a portion of the deck to start with
7. [Play the game](https://owasp.org/www-project-cornucopia/#div-cards) to discuss & document security requirements (and to win rounds)
8. Remember, points make prizes!

## The Card Decks
Both current decks have six suits and there are also two Joker cards. Each suit contains 13 cards (Ace, 2-10, Jack, Queen and King).

### Website App Edition (previously called Ecommerce Website Edition)

Instead of EoP’s STRIDE suits, Cornucopia suits for the Website App Edition were selected based on the structure of the OWASP Secure Coding Practices - Quick Reference Guide (SCP). The content was mainly drawn from the SCP but with additional consideration of sections in the [OWASP Application Security Verification Standard](https://owasp.org/www-project-application-security-verification-standard/), the [OWASP Web Security Testing Guide](https://owasp.org/www-project-web-security-testing-guide) and David Rook's [Principles of Secure Development](https://owasp.org/www-pdf-archive//OWASP-SecureDevPrinciples-David-Rook.pdf). These provided five suits, and a sixth called “Cornucopia” was created for everything else:

* Data validation and encoding
* Authentication
* Session management
* Authorization
* Cryptography
* Cornucopia

### Mobile App Edition
The second Cornucopia deck, the "Mobile App Edition", follows the same principles and game rules as the original OWASP Cornucopia, but has different suits based on the MASVS categories, in addition to the Cornucopia suit:

* Platform & Code
* Authentication & Authorization
* Network & Storage
* Resilience
* Cryptography
* Cornucopia

## Mappings
The other driver for Cornucopia was to link the attacks with requirements and verification techniques. An initial aim had been to reference [CWE](http://cwe.mitre.org/) weakness IDs, but these proved too numerous, and instead it was decided to map each card to [CAPEC](http://capec.mitre.org/) software attack pattern IDs which themselves are mapped to CWEs, so the desired result is achieved.

Each Website App Edition card is also mapped to the 36 primary security stories in the [SAFECode document](https://safecode.org/resource-secure-development-practices/fundamental-practices-secure-software-development-2/), as well as to the OWASP [SCP](https://owasp.org/www-project-secure-coding-practices-quick-reference-guide/) v2, [ASVS](https://owasp.org/www-project-application-security-verification-standard/) v4.0.3 and [AppSensor](https://owasp.org/www-project-appsensor/) (application attack detection and response) to help teams create their own security-related stories for use in Agile processes.

Likewise, each Mobile App Edition is mapped to CAPEC and the SAFECode stories, but instead of SCP, ASVS and AppSensor, each card is mapped to OWASP's [Mobile Application Security Verification Standard (MASVS)](https://mas.owasp.org/MASVS/) v2.0 and [Mobile Application Security Testing Guide (MASTG)](https://mas.owasp.org/MASTG/) v2.0. 


## Licensing

OWASP Cornucopia is free to use. It is licensed under the [Creative Commons Attribution-ShareAlike 3.0 license](http://creativecommons.org/licenses/by-sa/3.0/), so you can copy, distribute and transmit the work, and you can adapt it, and use it commercially, but all provided that you attribute the work and if you alter, transform, or build upon this work, you may distribute the resulting work only under the same or similar licence to this one.

© OWASP Foundation

## Other Security Gamification

If you are interested in using gaming for security, also see [Elevation of Privilege: The Threat Modeling Game](https://www.microsoft.com/en-gb/download/details.aspx?id=20303), [Security Cards](http://securitycards.cs.washington.edu/) from the University of Washington, the commercial card game [Control-Alt-Hack](http://www.controlalthack.com/) ([presentation](http://www.youtube.com/watch?v=Kpnvsgiiz8s)), [OWASP Snakes and Ladders](https://owasp.org/www-project-snakes-and-ladders), [OWASP Cumulus](https://owasp.org/www-project-cumulus/), and web application security training tools incorporating gamification such as [OWASP Hackademic Challenges Project](https://owasp.org/www-project-hackademic-challenges), [OWASP Security Shepherd](https://owasp.org/www-project-security-shepherd) and [ITSEC Games](http://itsecgames.blogspot.co.uk/).

Additionally, Adam Shostack maintains a list of tabletop security games and related resources at [Tabletop Security Games + Cards](https://shostack.org/games.html).
