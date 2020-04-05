# CV19 Contact Tracing Privacy Principles

The Law.MIT.edu research team is actively collecting and curating privacy principles for contact tracing applications and services that leverage personal individual location and proximity data.  We intend to publish key developments in this space on an ongoing basis through the MIT Computational Law Report Special Release on CV19 Legal Frameworks.

---

# Law.MIT.edu Draft Contact Tracing Privacy Principles

* Developed by: MIT Volunteer Drafting Team including: [Dazza Greenwood](https://www.linkedin.com/in/dazzagreenwood/), [Gregory Nadeau](https://www.linkedin.com/in/greg-nadeau-54529514), [Pagona Tsormpatzoudi](https://www.linkedin.com/in/pagona-tsormpatzoudi-0324903a) (others to be added to list as permissions are received)
* As collected on April 2, 2020
* [https://mitmedialab.github.io/CV19-Data-Privacy-Principles](https://mitmedialab.github.io/CV19-Data-Privacy-Principles)

### 1. Summary

Each of us is the primary owner of our personal data.  Services that we each use may have additional limited rights and responsibilities to our personal data, based on specified terms and conditions appropriate to the service.  A doctor, for example, has the right to maintain patient data and the responsibility to preserve it and only share it with patient consent.

Health, education, location, and contact tracing data is personal data.  No service provider or government agency should be able to use that data without user consent.

#3# 2. Technology should follow the principles of Privacy by Design

* Proactive not reactive; preventive, not remedial
* Privacy as the default
* Privacy embedded in the design
* Full functionality – positive-sum, not zero-sum
* End-to-end security – full lifecycle protection
* Visibility and transparency – keep it open
* Respect for user privacy – keep it user-centric

### 3. Data should be protected in accordance with Fair Information Practice Principles (FIPPs)

#### Notice/Awareness

Consumers should be given notice of an entity's information practices before any personal information is collected from them.[10] This requires that companies explicitly notify some or all of the following:

* identification of the entity collecting the data;
* identification of the uses to which the data will be put;
* identification of any potential recipients of the data;
* the nature of the data collected and the means by which it is collected;
* whether the provision of the requested data is voluntary or required;
* the steps taken by the data collector to ensure the confidentiality, integrity, and quality of the data.

#### Choice/Consent

Choice and consent in an on-line information-gathering sense means giving consumers options to control how their data is used. Specifically, choice relates to secondary uses of information beyond the immediate needs of the information collector to complete the consumer's transaction. The two typical types of choice models are 'opt-in' or 'opt-out.'

The 'opt-in' method requires that consumers affirmatively give permission for their information to be used for other purposes. Without the consumer taking these affirmative steps in an 'opt-in' system, the information gatherer assumes that it cannot use the information for any other purpose.

The 'opt-out' method requires consumers to affirmatively decline permission for other uses. Without the consumer taking these affirmative steps in an 'opt-out' system, the information gatherer assumes that it can use the consumer's information for other purposes.

Each of these systems can be designed to allow an individual consumer to tailor the information gatherer's use of the information to fit their preferences by checking boxes to grant or deny permission for specific purposes rather than using a simple "all or nothing" method.

Implementation guidance:

It is recommended that the opt-in consent option is implemented as that will comply with a good number of data protection laws globally

Template consent language like the below should be considered:

“I consent to (Add Controller Name OR App Name if whitelabelled to the Controller) processing my:

(Add unticked checkbox OR toggle off) Location data

(Add unticked checkbox OR toggle off) Health data for the purpose of COVID 19 contact tracing in accordance with the (Add link to the Controller Privacy Notice).”

There are alternative ways to present substantially similar text in the UX. E.g. splitting the screens and adding a “continue” button. Then the language will be adapted to “By clicking continue..”

Access/Participation

Access includes not only a consumer's ability to view the data collected but also to verify and contest its accuracy. This access must be inexpensive and timely in order to be useful to the consumer.

#### Integrity/Security

Information collectors should ensure that the data they collect is accurate and secure. They can improve the integrity of data by cross-referencing it with only reputable databases and by providing access for the consumer to verify it. Information collectors can keep their data secure by protecting against both internal and external security threats. They can limit access within their company to only necessary employees to protect against internal threats, and they can use encryption and other computer-based security systems to stop outside threats.

#### Enforcement/Redress

In order to ensure that companies follow the Fair Information Practice Principles, there must be enforcement measures. The FTC identified three types of enforcement measures: self-regulation by the information collectors or an appointed regulatory body; private remedies that give civil causes of action for individuals whose information has been misused to sue violators; and government enforcement that can include civil and criminal penalties levied by the government.

### 4. Potential Application of these Principles to MIT Private Kit Safe Paths Open Source Project

* Possible contacts determined privately on a user’s own device using open source code and cryptographic algorithms
* Data never leave the user’s device (100% local), unless they become ill and opt to release it to a health official
* Trusted health officials remove all diagnosed patient personally identifiable information – only releasing the redacted location trail
* Only release the redacted, disconnected, and aggregated space-time points
* Space-time points will be deleted after they are no longer actively needed, estimated at between 21 and 28 days.

---------

# Contact Tracing Bill of Rights

* Developed by: CoEpi and CovidWatch Source:
* As collected on April 2, 2020
* https://github.com/Co-Epi/CEN/blob/main/ContactTracingBillOfRights.md 

### 1. Users must be able to install and use a contact tracing app without having to divulge any personal information to anyone.

### 2. Contact tracing apps must not disclose any information during normal operation that can be used by third parties to track a user’s interactions or locations.

### 3. All information disclosed by users through a contact-tracing app must be completely opt-in, with clear informed consent both as to the nature of what they’re disclosing and the likely impacts of doing so.

### 4. When users choose to altruistically share information, that information must remain completely anonymous: no information may be required other than that which is essential for alerting others to potential exposure.

### 5. If apps collect any information, such as location histories, that is not essential for alerting others who may be exposed, users must not be expected or coerced to share that information by default. If a contact tracing app allows for the sharing of any location history, symptom reports, demographic information, or similar with public health officials or similar, such sharing must be completely anonymous, voluntary, and opt-in, and based on clear and easy to understand informed consent.


------


# Evaluating COVID-19 contact tracing apps? Here are 8 privacy questions we think you should ask.

* Developed by: Yves-Alexandre de Montjoye, Florimond Houssiau, Andrea Gadotti and Florent Guepin
* As collected on April 2, 2020
* https://cpg.doc.ic.ac.uk/blog/evaluating-contact-tracing-apps-here-are-8-privacy-questions-we-think-you-should-ask 

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
