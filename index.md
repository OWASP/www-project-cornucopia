---

layout: col-sidebar
title: OWASP Cornucopia
site_side: true
tags: cc
project: true
level: 3
type: documentation

---

[![OWASP Lab](https://img.shields.io/badge/owasp-lab%20project-yellow.svg)](/projects)
[![Twitter Follow](https://img.shields.io/twitter/follow/OWASPCornucopia?style=social)](https://twitter.com/OWASPCornucopia)

![OWASP Cornucopia Ecommerce Website Edition playing cards](assets/images/Cornucopia-header.jpg)

OWASP Cornucopia is a mechanism in the form of a card game to assist software development teams identify security requirements in Agile, conventional and formal development processes. It is language, platform and technology agnostic.

## Introduction
The idea behind Cornucopia is to help development teams, especially those using Agile methodologies, to identify application security requirements and develop security-based user stories. Although the idea had been waiting for enough time to progress it, the final motivation came when [SAFECode](http://www.safecode.org/) published its [Practical Security Stories and Security Tasks for Agile Development Environments](http://www.safecode.org/publications/SAFECode_Agile_Dev_Security0712.pdf) in July 2012.

The Microsoft SDL team had already published its super [Elevation of Privilege: The Threat Modeling Game](http://www.microsoft.com/security/sdl/adopt/eop.aspx) (EoP) but that did not seem to address the most appropriate kind of issues that web application development teams mostly have to address. EoP is a great concept and game strategy, and was [published under](http://blogs.msdn.com/b/sdl/archive/2010/03/02/announcing-elevation-of-privilege-the-threat-modeling-game.aspx) a [Creative Commons Attribution License](http://creativecommons.org/licenses/by/3.0/). Cornucopia Ecommerce Website Edition is based the concepts and game ideas in EoP, but those have been modified to be more relevant to the types of issues ecommerce website developers encounter. It attempts to introduce threat-modelling ideas into development teams that use Agile methodologies, or are more focused on web application weaknesses than other types of software vulnerabilities or are not familiar with STRIDE and DREAD.

To start using Cornucopia:

1. Download the document
1. Print the cards onto plain paper or pre-scored card
1. Cut/separate the individual cards
1. Identify an application, module or component to assess
1. Invite business owners, architects, developers, testers along for a card game
1. Get those infosec folk to provide chocolate, pizza, beer, flowers or all four as prizes
1. Select a portion of the deck to start with
1. [Play the game](/www-project-cornucopia#div-cards) to discuss & document security requirements (and to win rounds)
1. Remember, points make prizes!

## The Card Decks
### Ecommerce Website Edition

Instead of EoP’s STRIDE suits, Cornucopia suits were selected based on the structure of the OWASP Secure Coding Practices - Quick Reference Guide (SCP), but with additional consideration of sections in the [OWASP Application Security Verification Standard](/www-project-application-security-verification-standard/), the [OWASP Web Security Testing Guide](/www-project-web-security-testing-guide) and David Rook's [Principles of Secure Development](http://www.securityninja.co.uk/secure-development/the-principles-place/). These provided five suits, and a sixth called “Cornucopia” was created for everything else:

* Data validation and encoding
* Authentication
* Session management
* Authorization
* Cryptography
* Cornucopia

Each suit contains 13 cards (Ace, 2-10, Jack, Queen and King) but, unlike EoP, there are also two Joker cards. The content was mainly drawn from the SCP. Full Wiki Deck.

### Other Decks
Future editions such as for mobile app development will use different sources of information and suits.

## Mappings
The other driver for Cornucopia is to link the attacks with requirements and verification techniques. An initial aim had been to reference [CWE](http://cwe.mitre.org/) weakness IDs, but these proved too numerous, and instead it was decided to map each card to [CAPEC](http://capec.mitre.org/) software attack pattern IDs which themselves are mapped to CWEs, so the desired result is achieved.

Each card is also mapped to the 36 primary security stories in the [SAFECode document](http://www.safecode.org/publications/SAFECode_Agile_Dev_Security0712.pdf), as well as to the OWASP [SCP](/www-project-secure-coding-practices-quick-reference-guide/) v2, [ASVS](/www-project-application-security-verification-standard/) v3.0.1 and [AppSensor](/www-project-appsensor/) (application attack detection and response) to help teams create their own security-related stories for use in Agile processes.


## Licensing

OWASP Snakes and Ladders is free to use. It is licensed under the [Creative Commons Attribution-ShareAlike 3.0 license](http://creativecommons.org/licenses/by-sa/3.0/), so you can copy, distribute and transmit the work, and you can adapt it, and use it commercially, but all provided that you attribute the work and if you alter, transform, or build upon this work, you may distribute the resulting work only under the same or similar license to this one.

© OWASP Foundation

## Other Security Gamification

If you are interested in using gaming for security, also see [OWASP Cornucopia](/www-project-cornucopia), [Elevation of Privilege: The Threat Modeling Game](http://www.microsoft.com/security/sdl/adopt/eop.aspx), [Security Cards](http://securitycards.cs.washington.edu/) from the University of Washington, the commercial card game [Control-Alt-Hack](http://www.controlalthack.com/) ([presentation](http://media.blackhat.com/bh-us-12/Briefings/Kohno/BH_US_12_Kohno_Control_Alt_Hack_Slides.pdf)), and web application security training tools incorporating gamification such as [OWASP Hackademic Challenges Project](/www-project-hackademic-challenges), [OWASP Security Shepherd](/www-project-security-shepherd) and [ITSEC Games](http://itsecgames.blogspot.co.uk/).

Additionally, Adam Shostack maintains a list of tabletop security games and related resources at [security games](http://adam.shostack.org/games.html).
