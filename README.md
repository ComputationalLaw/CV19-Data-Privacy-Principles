# COVID-19 Contact Tracing Privacy Principles

For the Law.MIT.edu current public published "working draft" (likely a few versions behind the content in this GitHub repository) please see: [https://law.mit.edu/pub/covid19contacttracingprivacyprinciples](https://law.mit.edu/pub/covid19contacttracingprivacyprinciples)

-----

This draft document is for rapid input in support of an upcoming Special Release on COVID-19 Legal Frameworks to be published as part of the [MIT Computational Law Report at Law.MIT.edu](https://law.mit.edu).  An editorial and research tiger team are actively collecting and curating privacy principles for COVID-19 (CV19) contact tracing applications and services that leverage personal individual location and proximity data.  To offer feedback on or other contributions to this specific content on CV19 contact tracing privacy principles please make a [pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests) or add a [GitHub Issue](https://github.com/ComputationalLaw/CV19-Data-Privacy-Principles/issues/new) to this repository with proposed edits to this file.  To propose other content for publication as part of the MIT Computational Law Report please refer to our [Submission](https://law.mit.edu/submissions) page.

We have included materials from other groups on contact tracing privacy principles as well, potentially to synthesise into an overall set of principles.

-----

# Law.MIT.edu Draft Contact Tracing Privacy Principles

* Developed by: MIT Volunteer Drafting Team including: [Dazza Greenwood](https://www.linkedin.com/in/dazzagreenwood), [Gregory Nadeau](https://www.linkedin.com/in/greg-nadeau-54529514), [Pagona Tsormpatzoudi](https://www.linkedin.com/in/pagona-tsormpatzoudi-0324903a), [Bryan Wilson](https://www.linkedin.com/in/bryangw), [Jeffrey Saviano](https://www.linkedin.com/in/jeffrey-saviano-1398775), and [Alex "Sandy" Pentland](https://www.linkedin.com/in/alexsandypentland) (others to be added to list as permissions are received)
* This is the current development version of the Law.MIT.edu Draft Contact Tracing Privacy Principles at [https://computationallaw.github.io/CV19-Data-Privacy-Principles/](https://computationallaw.github.io/CV19-Data-Privacy-Principles)

### 1. Lawful


### 2. Voluntary


### 3. Informed Consent

Given the potential sensitivity of COVID-19 contact tracing data, not only is “opt-in” agreement necessary but the more rigorous standards governing “informed consent” are recommended.  

> Implementation guidance:

> It is recommended that the opt-in consent option is implemented as that will comply with a good number of data protection laws globally

> Template consent language like the below should be considered:

> “I consent to (Add Controller Name OR App Name if whitelabelled to the Controller) processing my:

> (Add unticked checkbox OR toggle off) Location data

> (Add unticked checkbox OR toggle off) Health data for the purpose of COVID 19 contact tracing in accordance with the (Add link to the Controller Privacy Notice).”

> There are alternative ways to present substantially similar text in the UX. E.g. splitting the screens and adding a “continue” button. Then the language will be adapted to “By clicking continue..”

### 4. Identity Control

* Possible contacts determined privately on a user’s own device
* Data never leave the user’s device (100% local), unless they become ill and opt to release it to a health official

* anonymity, pseudonymity
* manage risk of reidentification 
* Do not reveal to the authority the identity of users who are at risk

### 5. Access

Access includes not only a consumer's ability to view the data collected but also to verify and contest its accuracy. This access must be inexpensive and timely in order to be useful to the consumer.

### 6. Transparency 

Consumers should be given notice of an entity's information practices before any personal information is collected from them.[10] This requires that companies explicitly notify some or all of the following:

* identification of the entity collecting the data;
* identification of the uses to which the data will be put;
* identification of any potential recipients of the data;
* the nature of the data collected and the means by which it is collected;
* whether the provision of the requested data is voluntary or required;
* the steps taken by the data collector to ensure the confidentiality, integrity, and quality of the data.

Furthermore, to promote transparency, it is recommended that contact tracing apps use open source code and pubicly vetted cryptographic algorithms

### 7. Accountability

In order to ensure that companies adhere to contact tracing privacy principles, there must be enforcement measures. The FTC identified three types of enforcement measures: self-regulation by the information collectors or an appointed regulatory body; private remedies that give civil causes of action for individuals whose information has been misused to sue violators; and government enforcement that can include civil and criminal penalties levied by the government.

### 8. Proportionality

Proportional to Effectiveness at Combatting Epidemic
 - Deletion of Individual Data after no longer than duration needed [28 days]
 - The potential risk that private information may be exposed or misused as a result of the contact tracing system must be proportional to the public health benefits of that system for combatting the epidemic. 
 - Data Minimization
 
* Trusted health officials remove all diagnosed patient personally identifiable information
* Only release the redacted, disconnected, and aggregated space-time points (from location data) or obfuscated identifiers (from e.g.,Bluetooth)
* Space-time points will be deleted after they are no longer actively needed, estimated at between 21 and 28 days.

 
[Drafting note: Does the balance change for contact tracing systems used not for public health but for private sector workforce health protection?]

### Legitimacy

In a system that includes an aggregate data holder, the capabilities, duties and motivations of such entity must be appropriate to it's responsibility to safeguard the rights of people whose data it holds.  Ideally, such entity would hold fiduciary obligations to the people whose data it holds, but other combinations of requirements, constraints, incentives and counter-incentives can perform the same function.  

 -  Page 6: https://www.aclu.org/report/aclu-white-paper-limits-location-tracking-epidemic?redirect=aclu-white-paper-limits-location-tracking-epidemic
 -  Open questions: Should there ever be individual central authorities or should this role always be comrpised of a range of relevant stakeholders in governance of a system?  Should such a system always be distributed and decentralized?
 

## Other Pillars

This document addresses privacy principles as a key pillar supporting successful contact tracing systems, however this is not the only pillar.  The following are other pillars that are related to privacy but discernable from and beyond the scope of privacy principles.

#### Security

Information collectors should ensure that the data they collect is accurate and secure. They can improve the integrity of data by cross-referencing it with only reputable databases and by providing access for the consumer to verify it. Information collectors can keep their data secure by protecting against both internal and external security threats. They can limit access within their company to only necessary employees to protect against internal threats, and they can use encryption and other computer-based security systems to stop outside threats.

#### Effectiveness

Effectiveness at combatting epidemic.
 - measurably achieves the purpose for contact tracing
 - accuracy and precision 
 - audit, testing, etc

#### Usability

#### Equity 

---------

> _Below, Please find other relevant sources currenbtly under consideration for incorporation into a general set of CV19 Contact Tracing Principles.  If you are aware of other example materials relevant to CV19 contact tracing please let us know in our [GitHub Issues](https://github.com/ComputationalLaw/CV19-Data-Privacy-Principles/issues/new)._

---------

# CoEpi and CovidWatch Contact Tracing Bill of Rights

* Developed by: CoEpi and CovidWatch
* As collected on April 2, 2020
* [https://github.com/Co-Epi/CEN/blob/main/ContactTracingBillOfRights.md](https://github.com/Co-Epi/CEN/blob/main/ContactTracingBillOfRights.md)

**1. Users must be able to install and use a contact tracing app without having to divulge any personal information to anyone.**

**2. Contact tracing apps must not disclose any information during normal operation that can be used by third parties to track a user’s interactions or locations.**

**3. All information disclosed by users through a contact-tracing app must be completely opt-in, with clear informed consent both as to the nature of what they’re disclosing and the likely impacts of doing so.**

**4. When users choose to altruistically share information, that information must remain completely anonymous: no information may be required other than that which is essential for alerting others to potential exposure.**

**5. If apps collect any information, such as location histories, that is not essential for alerting others who may be exposed, users must not be expected or coerced to share that information by default. If a contact tracing app allows for the sharing of any location history, symptom reports, demographic information, or similar with public health officials or similar, such sharing must be completely anonymous, voluntary, and opt-in, and based on clear and easy to understand informed consent.**

-----


# Contact Tracing Bill of Rights

* Developed by: TCN Coalition (drafters and signatories listed below)
* As collected on April 16, 2020
* [https://github.com/TCNCoalition/TCN/blob/main/ContactTracingBillOfRights.md](https://github.com/TCNCoalition/TCN/blob/main/ContactTracingBillOfRights.md)

## Digital Contact Tracing and Alerting Data Use Definition

Digital contact tracing apps can be effective without a user having to divulge any personal information to anyone. Data processed within digital contact tracing applications and infrastructure may only reveal the following types of information to the following types of individuals:

* Plausibly exposed individuals that they may have been exposed
* Health officials, of general, high level trends in exposure (not individual level)
* Verifying to authorities that an individual is healthy or sick, with the explicit consent of the individual at each verification.

Contact tracing data or derived data may not be disclosed to third parties, such as analytics and ad targeting services. 

Aggregate data should be processed with privacy-protecting techniques such as differential privacy. The methodologies and techniques should be available for public review. 

Private-sector contact tracing apps should be open source and/or available for audit from an independent third party.

When developing a contact tracing app, developers should identify one or more well-defined problems that will be mitigated, solved, or improved.

## Individual Data Rights for Digital Contact Tracing


1. Data collection should be limited to achieve a defined purpose. 
2. All information disclosed by users through a contact-tracing app should be completely opt-in, with clear informed consent both as to the nature of what they’re disclosing how it is used, the likely impacts of disclosure and use, and any choices the user may have. Any new use requires fresh consent. Users can withdraw their consent at any given time.
3. When users choose to altruistically share their health information, that information should remain completely anonymous: no information should be required other than that which is essential, based on epidemiological standards, for alerting others to potential exposure. 
4. Information such as location history, symptom reports, demographic information, or similar shared with public health officials or researchers must never be linked back to or used to re-identify individuals, and must not be shared with entities legally allowed to perform such linkage unless required by law, such as with a subpoena.
5. Data may be aggregated so that it may not allow for the identification of individuals. Aggregate data may be maintained for public research purposes. Precautions should be taken to ensure that shared aggregate data may not be re-identified downstream.  
6. Application developers should have a very clear and reasonable data retention policy based on epidemiological standards, and must not retain any data for longer than required to achieve the app’s objective.
7. Data should be secured on the users device according to industry standards.
8. An individual has ownership over the data collected and stored on their mobile device. 
9. Data collected by or derived from contact tracing apps should not be monetized, shared, or used for any other non-public-health purpose. 
10. Contact tracing apps shall be developed in collaboration with the privacy and security community, government agencies, technology community, and public health professionals, including epidemiologists.
11. All contact tracing apps must be in compliance with local data protection laws and regulations.
12. Contact tracing apps should use an openly published protocol to ensure that their solution is verifiable and interoperable. For example, [the TCN Protocol](https://github.com/TCNCoalition/TCN), and [Apple/Google COVID-19 contact tracing technology](https://www.apple.com/newsroom/2020/04/apple-and-google-partner-on-covid-19-contact-tracing-technology/). 

## Stakeholders
* Public health / Government
* Infectious disease / Epidemiologists / Scientists
* Users / Consumers

## Drafters
* Harper Reed (harper@modest.com)
* Cari Spivack (cari@usdigitalresponse.org)
* Andrew Trask (andrew@openmined.org)
* Scott Leibrand, CoEpi.org (scottleibrand@gmail.com)
* Dana Lewis, CoEpi.org (dana+CoEpi@OpenAPS.org)
* Tina White (crwhite@stanford.edu)
* Martin Häcker (mhaecker@mac.com)
* Sebastian Presiner (kreativmonkey@calyrium.org)
* Clara Fischer (clara@voiceof.tech)

## Other notable privacy principles:
* https://www.ccc.de/en/updates/2020/contact-tracing-requirements
* https://law.mit.edu/pub/covid19contacttracingprivacyprinciples

## Signatories: 
* Jenny Wanger, TCN Coalition
* Andreas Gebhard, TCN Coalition

-----

# Evaluating COVID-19 contact tracing apps? Here are 8 privacy questions we think you should ask.

* Developed by: Yves-Alexandre de Montjoye, Florimond Houssiau, Andrea Gadotti and Florent Guepin
* As collected on April 2, 2020
* [https://cpg.doc.ic.ac.uk/blog/evaluating-contact-tracing-apps-here-are-8-privacy-questions-we-think-you-should-ask](https://cpg.doc.ic.ac.uk/blog/evaluating-contact-tracing-apps-here-are-8-privacy-questions-we-think-you-should-ask)

As strong measures are being put in place to slow down the spread of COVID-19, many are looking at how technology and data could help. With many countries using mobile phone location data to analyze the effectiveness of social distancing measures and help predict the potential geographic spread of the disease, the focus has now shifted to whether mobile phones could also help warn users if they have been exposed to an infected person.

Contact tracing apps are being developed in the UK, US, Germany, with one already deployed in Singapore. These apps have increasingly come under the spotlight as a potential long-term way to monitor the virus. Epidemiologists say that it could prove vitalto avoid long-term extreme confinement measures. The data handled by these apps, from location datato fine-grained close proximity information and whether a person might be infected and should self-quarantine is however very sensitive.

In our Mar 21 blog post, we emphasized how we do not have to pause privacy laws and regulations and how privacy engineering can help measure and limit the spread of the virus without resorting to mass surveillance.

When it comes to contact tracing, this however requires to go beyond simple reassurances that the phone numbers aren’t recorded, that everything is encrypted, that pseudonyms are changing, or that the app is based on consent. Indeed, a large range of techniques exist to circumvent those protections. For instance, scoreshave been developed to re-identify individuals in locationor graph datasets, session fingerprintingcould be used to link a pseudonymous app user to an authenticated web visitor, and node-based intrusions would allow to track users.

Apps are being developed around the world and are likely to be available within weeks. If they are proven useful, governments, health authorities, and users will have to evaluate the different approaches and decide whether to adopt them.

Privacy is a crucial component in the equation. In this post, we propose 8 questions one should ask to assess privacy in contact tracing apps.

### Contact tracing – Setup

We here focus on contact tracing apps installed by users and empowering them: apps informing users that they have been in close proximity with an infected individual in the past and providing them with recommendations on what to do.

The privacy setting for such an app typically involves the following entities:

Users who install the app on their phone;

Authority (e.g. the government or a healthcare provider) that runs a central server coordinating the contact tracing;

External entities: malicious apps, users, a foreign agency, or a company who is trying to take advantage of the situation to collect data or tamper with the contact tracing.

We use userto refer to anyone using the app, infectedfor users who have been tested and were found to be positive, and at risk for users who have been in close contact with someone who was later found to be infected.

A digital contact tracing app would typically work like this: Bluetooth signals or location information are recorded by phones; when a user is diagnosed positive (infected), they upload their data (under some form) to the authority, which then arranges for other users to learn that they are at risk because they interacted with an infected person.

To illustrate the vulnerabilities our questions are meant to surface, we use three “toy” protocols. Note that they are only meant to illustrate the questions and are not complete, deployable solutions for contact tracing, nor even good protocols.

#### Toy protocol 1 (using location):

Each app only records its own location.

When a user reports as infected, they send their trajectory (location and time) to the authority.

The authority shares the pseudonymous trajectories of all infected users with every user. Users can then check if they were in close contact with an infected individual.

#### Toy protocol 2 (using Bluetooth):

Each app broadcasts a unique identifier assigned by the authority through Bluetooth.

When two phones are near to one another, they exchange these identifiers.

When a user reports as infected, they send all the identifiers they encountered to the authority.

The authority contacts all the users whose identifier was encountered by an infected user.

#### Toy protocol 3 (using Bluetooth):

Each app broadcasts a unique identifier using Bluetooth, assigned by the authority. This unique identifier is reset every hour.

When two phones are near to one another, they exchange these identifiers.

When a user reports as infected, they send all the identifiers that they have used (one per hour) to the authority.

The authority shares the identifiers of all infected users with every user. Users can then check if they encountered one of these identifiers recently.

Using this vocabulary and definitions, we propose 8 privacy questions that we would like app developers to answer. We hope these questions will help start a high-level discussion to systematically evaluate potential vulnerabilities and real risks in existing and future contact tracing apps.

### The questions

#### 1. How do you limit the personal data gathered by the authority?

Large-scale collection of personal data can quickly lead to mass surveillance.

In protocol 1, the authority learns the whole trajectory of infected users. In protocol 2, the authority learns the entire pseudonymous social graph of infected users, along with timestamps, which has been shown to be easily re-identifiable. Both collect large amounts of personal data. Protocol 3 does better in that regard, with the authority only observing the pseudonyms of infected users (with changing identifiers).

#### 2. How do you protect the anonymity of every user?

Users’ identities should be protected. Special measures should be put in place to limit the risk that users can be re-identified by the authority, other users, or external parties.

Protocol 1 doesn’t technically give the authority the identity of users. However, researchshows that location traces are highly unique, and could probably be easily linked back to a person. Protocol 2 is worse, as the users are given a unique identifier by the authority, which can link these identifiers to the phone. Protocol 3 is much better – as long as connections with the server are anonymous (e.g. using Toror mixes), the user’s identity could be kept secret.

#### 3. Does your system reveal to the authority the identity of users who are at risk?

The goal of contact tracing is to let people know they have been in contact with someone who was infected. The authority should not know who these people are.

No for protocols 1 and 3, which never require data from non-infected users. Yes for Protocol 2, in which the authority explicitly contacts at risk users, and could use this information to, e.g., force them into quarantine.

#### 4. Could your system be used by users to learn who is infected or at risk, even in their social circle?

Having been in contact and infecting someone may become a matter of life and death. Digital contact tracing should warn people at risk without revealing who might have infected them.

Protocol 1 exposes the full data of infected users publicly: every user can then check if a particular person they know is in the dataset. In protocol 3, a user at risk learns the hour at which they met an infected user, and can probably find out who infected them. Protocol 2, on the other hand, prevents users from learning anything about one another.

#### 5. Does your system allow users to learn any personal information about other users?

Apps should not need to leak information on a user’s locations or social networks to other users.

All three protocols protect data of non-infected users, but only protocol 2 prevents users from learning anything about infected users. Protocol 1 exposes their entire trajectory. Protocol 3 leaks small amounts of information: identifiers encountered by infected individuals. It is possible for a user to recognize identifiers they have encountered and learn that the user to whom the identifier belongs is at risk.

#### 6. Could external parties exploit your system to track users or infer whether they are infected?

The system should take into account the risk of external adversaries, including well-resourced ones.

Both protocols 2 and 3 force phones to broadcast an identifier. An entity could install Bluetooth trackers to cover a city, or install malicious code on phones, and record the identifiers that they observe in specific locations. In our research, we showed that trackers installed on the phones 1% of London’s population would allow an attacker to track the real-time location of over half of the city. Protocol 3 makes this attack much more difficult, as the identifiers change every hour.

#### 7. Do you put in place additional measures to protect the personal data of infected and at risk users?

The system design may require revealing more personal information about users who are infected or exposed. But these are often the people who are more vulnerable and at risk.

Protocol 1, and to some extent protocols 2 and 3, require infected users to share more data. Users at risk are however safe in protocol 1 and 2, but not in protocol 3, where some of the identifiers that they have used are published.

#### 8. How can we verify that the system does what it says?

Large-scale contact tracing is too sensitive to rely on blind trust. Transparency is essential to prove that the app functions as advertised.

Transparency of the full system is absolutely fundamental to guarantee privacy. This requires open protocol specifications, but also public source code, reproducible builds, and verifiability of what is being broadcasted by apps.

---

In the next few weeks, most of us are likely to install a contact tracing app to help slow down the spread of coronavirus. The questions we propose here represent a starting point for an informed conversation on the privacy risks of apps we are being offered.

Importantly though, they cannot replace a full independent privacy audit. In-depth formal analysis of the protocol is necessary before deployment and should be published. Protecting privacy should rely on mathematical proofs of correctness, with mitigation strategies considered only when necessary. Our questions focus on privacy aspects, but ensuring security is similarly crucial. This means, for example, supervising the integrity and authenticity of the crowdsourced data, evaluating how mobile malware could affect the app’s behavior, or assessing the resilience of the authority’s servers against intrusions.

Building a contact tracing app that allows all of us to participate in the fight against COVID19 is possible, but it will require us to go beyond shallow reassurances that privacy is protected.

[PDF version](https://cpg.doc.ic.ac.uk/blog/pdf/evaluating-contact-tracing-apps-here-are-8-privacy-questions-we-think-you-should-ask.pdf)

-----

# 10 requirements for the evaluation of "Contact Tracing" apps

* Developed by: German "Chaos Computer Club" (CCC) Europe's largest association of hackersan and advisor of the German government
* As collected on April 7, 2020
* [10 requirements for the evaluation of "Contact Tracing" apps](https://www.ccc.de/en/updates/2020/contact-tracing-requirements)

"Corona apps" are on everyone's lips as a way to contain the SARS-CoV-2 epidemic. CCC publishes 10 requirements for their evaluation from a technical and societal perspective.

Currently, technically supported "contact tracing" is being considered as means to counteract the spread of SARS-CoV-2 in a more targeted manner. The general motivation is to allow greater freedom of movement for the broad spectrum of society by allowing quick tracing and interruption of infection chains. Contacts of infected persons should be alerted more quickly and thus be able to quarantine themselves more quickly. This, in turn, should prevent further infections. A "corona app" could therefore protect neither ourselves nor our contacts: It would be designed to break chains of infection by protecting the contacts of our contacts.

### Contact Tracing as a risk technology

There are a number of suggestions for the technical implementation of this concept. These proposals range from dystopian systems of full surveillance to targeted, completely anonymous methods of alerting potentially infected persons without knowledge of the specific person.

In principle, the concept of a "Corona App" involves an enormous risk due to the contact and health data that may be collected. At the same time, there is a chance for "privacy-by-design" concepts and technologies that have been developed by the crypto and privacy community over the last decades. With the help of these technologies, it is possible to unfold the epidemilogical potential of contact tracing without creating a privacy disaster. For this reason alone, all concepts that violate or even endanger privacy must be strictly rejected.

In the following, we outline social and technical minimum requirements for such technologies. The CCC sees itself in an advisory and observation role in this debate. We will not recommend specific apps, concepts or procedures. We however advise against the use of apps that do not meet these requirements.

### I. Societal requirements

1. Epidemiological sense & purpose

The basic prerequisite is that "contact tracing" can realistically help to significantly and demonstrably reduce the number of infections. The validation of this assessment is the responsibility of epidemiology. If it turns out that "contact tracing" via app is not useful or does not fullfil the purpose, the experiment must be terminated.

The application and any data collected must be used exclusively to combat SARS-CoV-2 infection chains. Any other use must be technically prevented as far as possible and legally prohibited.

2. Voluntariness & freedom from discrimination

For an epidemiologically significant efficacy, a "contact tracing" app requires a high degree of dissemination in society. This wide distribution must not be achieved by force, but only by implementing a trustworthy system that respects privacy. Against this background, there must be no levying of fees for use as well as no financial incentives for usage.

People who refuse to use it must not experience any negative consequences. Ensuring this is a matter for politics and legislation.

The app must regularly inform people about its operation. It must allow for simple temporary deactivation and permanent removal. Restrictive measures, e.g. an "electronic shackles" function to control contact restrictions, must not be implemented.

3. Fundamental privacy

Only with a convincing concept based on the principle of privacy can social acceptance be achieved at all.

At the same time, verifiable technical measures such as cryptography and anonymisation technologies must ensure user privacy. It is not sufficient to rely on organisational measures, "trust" and promises. Organisational or legal hurdles against data access cannot be regarded as sufficient in the current social climate of state-of-emergency thinking and possible far-reaching exceptions to constitutional rights through the Infection Protection Act.

We reject the involvement of companies developing surveillance technologies as "covid washing". As a basic principle, users should not have to 'trust' any person or institution with their data, but should enjoy documented and tested technical security.

4. Transparency and verifiability

The complete source code for the app and infrastructure must be freely available without access restrictions to allow audits by all interested parties. Reproducible build techniques must be used to ensure that users can verify that the app they download has been built from the audited source code.

### II. Technical requirements

5. No central entity to trust

A completely anonymous contact tracing without omniscient central servers is technically possible. A dependence of the users' privacy on the trustworthiness and competence of the operator of central infrastructure is technically not necessary. Concepts based on this "trust" are therefore to be rejected.

In addition, promised security and trustworthiness of centralised systems - for example against the connection of IP addresses with anonymous user IDs - cannot be effectively verified by users. Systems must therefore be designed to guarantee the security and confidentiality of user data exclusively through their encryption and anonymisation concept and the verifiability of the source code.

6. Data economy

Only minimal data and metadata necessary for the application purpose may be stored. This requirement prohibits the central collection of any data that is not specific to a contact between people and its duration.

If additional data such as location information are recorded locally on the phones, users must not be forced or tempted to pass this data on to third parties or even publish it. Data that is no longer needed must be deleted. Sensitive data must also be securely encrypted locally on the phone.

For voluntary data collection for epidemiological research purposes that goes beyond the actual purpose of contact tracing, a clear, separate consent must be explicitly obtained in the app's interface and it must be possible to revoke it at any time. This consent must not be a prerequisite for use.

7. Anonymity

The data that each device collects about other devices must not be suitable for deanonymizing their users. The data that each person may pass on about themself must not be suitable for deanonymising the person. It must therefore be possible to use the system without collecting or being able to derive personal data of any kind. This requirement prohibits unique user identifications.

IDs for "contact tracing" via wireless technology (e.g. Bluetooth or ultrasound) must not be traceable to persons and must change frequently. For this reason, it is also forbidden to connect or derive IDs with accompanying communication data such as push tokens, telephone numbers, IP addresses used, device IDs etc.

8. No creation of central movement or contact profiles

The system must be designed in such a way that movement profiles (location tracking) or contact profiles (patterns of frequent contacts traceable to specific people) can't be established intentionally or unintentionally. Methods such as central GPS/location logging or linking the data to telephone numbers, social media accounts and the like must therefore be rejected as a matter of principle.

9. Unlinkability

The design of the temporary ID generation must be such that IDs cannot be interpreted and linked without possession of a user controlled private key. They must therefore not be derived from other directly or indirectly user identifying information. Regardless of the way IDs are communicated in the event of infection, it must be ruled out that the collected "contact tracing" data can be chained over longer periods of time.

10. Unobservability of communication

Even if the transmission of a message is observed in the system (e.g. via communication metadata), it must not be possible to conclude that a person is infected himself or herself or has had contact with infected persons. This must be ensured both with regard to other users and to infrastructure and network operators or attackers who gain insight into these systems.

### Role of the CCC

For well over 30 years, CCC has engaged in voluntary work at the intersection between technology and society. Our ethical principles stand for privacy, decentralization and data economy – and against any form of surveillance and coercion.

Without claiming to be exhaustive, in this article we name minimum privacy requirements that a "Corona App" must meet in order to be socially and technologically tolerable at all. CCC will under no circumstances ever provide a concrete implementation with approval, recommendation, a certificate or test seal.

It is the responsibility of the developers of contact tracing systems to prove the fulfillment of these requirements or to have them proven by independent third parties.

