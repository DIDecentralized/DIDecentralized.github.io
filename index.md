# Decentralized-ID.com 
**Self-Sovereign, Blockchain and Decentralized Identity Resources**


>A good self‐sovereign identity system will allow individuals to directly influence how companies, governments, and others correlate our interactions across different services and locations by default. It won’t fix all identity problems nor preclude alternative identity approaches, but it will put the individual in control of most uses of identity and give organizations a simpler, easier, more ethical way to use identity to improve how they provide services and products. When successful, it will not only enable individuals to exercise greater control over how companies and governments keep track of us, it will also illuminate those situations where self‐sovereign identity is restricted, facilitating a conversation about when and where such limits are appropriate. [Joe Andrieu -A Technology‐Free Definition of Self‐Sovereign Identity](https://github.com/jandrieu/rebooting-the-web-of-trust-fall2016/blob/master/topics-and-advance-readings/a-technology-free-definition-of-self-sovereign-identity.pdf)

## NOTE

**[/awesome-decentralized-id](https://github.com/infominer33/awesome-decentralized-id) is transitioning to [decentralized-id.com](https://decentralized-id.com) to become a community-led resource.** 

What does that exactly mean? 

It means that I'm working to build a foundation that can facilitate information exchange between communities and initiatives in the DID ecosystem, as well as provide a platform for that community. 

If your organization doesn't have a page of its own, build one and submit a pull request! 

I would happy to work with you and create a space where it's easy to find information on any topic in SS\DDI. 

And that I'm not the only one with commit access, making it easier for the community to change as seen fit.

but for the time being, [/awesome-decentralized-id](https://github.com/infominer33/awesome-decentralized-id) is still the most reliable source for this info, as I'm still working out the deets.

## Contents
[[**T**](#contents)]witter • [[**G**](#contents)]ithub • [[**B**](#contents)]log • [[**wp**](#contents)] whitepaper • [[**D**](#contents)]ocumentation • [[**F**](#contents)]orums • [[**C**](#contents)]hat • [[**tele**](#contents)]gram • [[**web**](#contents)]site
• [[**ϟ**](#contents)] related resource • [[**>**](#contents)] related section • [[**^**](#contents)] back to the contents.

* [Link Shorthand](#link-shorthand)
* [What is Decentralized ID?](#what-is-decentralized-id-)
* [What is Self Sovereign Identity?](#self-sovereign-identity-)
* [DID Related Web Standards](did-related-web-standards-)
  * [W3C](#w3c-)
    * [DID the Decentralized Identifier](#did-the-decentralized-identifier-)
    * [Verifiable Claims](#verifiable-claims-)
  * [Decentralized Key Managment DKMS](#decentralized-key-management-dkms-)
  * [DID Auth](#did-auth-) 
  * [Learning Machine](#learning-machine-)
    * [Blockcerts](#blockcerts-)
  * [ERC - EIP](#erc---eip-)
    * [ERC 725 - 735](#erc-725---735-)
    * [ERC Other](#erc-other-)
  * [Schema](#schema-)
  * [Assorted Thought Around Identity](#assorted-thought-around-identity)
* [DID Adoption](#did-adoption-)
* [Directory](#directory) 
  * [SSI\DID History](history.md)
  * [Self Sovereign Identity](self-sovereign-identity)
  * [Identity Related GitHub Repositories](identity-github.md)
  * [Literature](literature.md)
  * [Rebooting Web of Trust](rebooting-web-of-trust.md)
  * [Media](assorted-media.md) - Video, Podcasts and Slideshare  
  * [Indy Ecosystem](indy-ecosystem/)
  * [Decentralized Identity Foundation—DIF](identity-foundation.md)
  * [Ethereum](ethereum)
  * [State Sponsored](state-sponsored.md)
  * [IBM](ibm.md)
  * [Microsoft](microsoft.md)
  * [Humanitarian](humanitarian.md)
  * [GDPR](gdpr)
* [Sources](#sources-)


*Pull Requests Welcome*




![](https://i.imgur.com/9KpJRDr.png)


## What is Decentralized ID? [**^**](#contents)

That's a big question, and what follows are just some notes, until I work out a more thoughtful answer.

The essence of Decentralized-ID is in creating open standards for a privacy preserving internet-wide identity layer — not owned by any one particular organization, but interoperable between all.

It's impossible to have a conversation about decentralized-id without discussing blockchain and self sovereign identity: 
  * Self Sovereign Identity principles (with some help from the GDPR) have helped to shape the narrative around putting the identity owner in control over their personal information.
  * Blockchain fueled longstanding efforts to create a privacy preserving internet-wide identity protocol, and inspired development of decentralized networks for online identification. 
  * The United Nations Sustainable Development Goals (SDGs) have also helped to fueled efforts for a global and widely accessible identity solution.

—[infominer.id](https://infominer.id)

## DID-SSI History 

* [The Augmented Social Network and the IDCommons](/history.md#the-augmented-social-network-and-the-idcommons-)
* [Internet Identity Workshop—IIW](/history.md#internet-identity-workshop-) 
* [Bitnation and the United Nations](/history.md#bitnation-and-the-united-nations-)
* [#Rebooting-Web-of-Trust (RWoT)](/history.md#rebooting-the-web-of-trust-)
* [ID2020 and the GDPR](/history.md#id2020-and-the-gdpr-)
* [Additional IID Standards History](/history.md#additional-iid-standards-history-)

## Self Sovereign Identity [**^**](#contents)

![](https://imgur.com/3zz62kpl.png)


* [Christopher Allen](http://www.lifewithalacrity.com/)[[**info**](https://christophera.info/)] details the overarching history of internet idenitity standards and outlines [10 Principles of Self Sovereign Identity](https://github.com/WebOfTrustInfo/self-sovereign-identity/blob/master/self-sovereign-identity-principles.md) in his seminal work [The Path to Self-Soverereign Identity](http://www.lifewithalacrity.com/2016/04/the-path-to-self-soverereign-identity.html)[[**ϟ**](https://www.coindesk.com/path-self-sovereign-identity/amp/)]
* <a href="https://github.com/jandrieu/rebooting-the-web-of-trust-fall2016/raw/master/topics-and-advance-readings/a-technology-free-definition-of-self-sovereign-identity.pdf"><u>A Technlogy-Free Definition of Self-Sovereign Identity</u></a> is a continuation of the discussion started by Allen, offering 3 "Core Characteristics of Sovereign Identity".
* [7 Myths of Self Sovereign Identity](https://medium.com/evernym/7-myths-of-self-sovereign-identity-67aea7416b1)
* [Inevitable Rise of Self-Sovereign Identity](https://sovrin.org/wp-content/uploads/2018/03/The-Inevitable-Rise-of-Self-Sovereign-Identity.pdf)
* [SSIMeetup](http://ssimeetup.org/) [[**S**](https://www.slideshare.net/SSIMeetup/presentations)] [[**V**](https://www.youtube.com/channel/UCSqSTlKdbbCM1muGOhDa3Og)] [[**tele**](https://t.me/SSIMeetup)]
\- SSI Meetup is an open, collaborative community to help SSI evangelists around the world, independent of company interests or standards. 
* [SSI: A Roadmap for Adoption](https://github.com/WebOfTrustInfo/rebooting-the-web-of-trust-spring2018/blob/master/final-documents/a-roadmap-for-ssi.md)
* **[/awesome-decentralized-id/self-sovereign-identity](https://github.com/infominer33/awesome-decentralized-id/tree/master/self-sovereign-identity)** SSI documentation is still under development. This directory is to organize existing thought on SSI in one place for ease of study, and the development of new documentation.
* [Matching Identity Management Solutions to Self Sovereign Identity Solutions](https://www.slideshare.net/TommyKoens/matching-identity-management-solutions-to-selfsovereign-identity-principles)


<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">0/ “Self-Sovereign Identity: A Progress Report”…</p>&mdash; Christopher Allen (@ChristopherA) <a href="https://twitter.com/ChristopherA/status/989120215702261761?ref_src=twsrc%5Etfw">April 25, 2018</a></blockquote>


## DID Related Web Standards [**^**](#contents)

### W3C [**^**](#contents)

![](https://imgur.com/Lz6RTysl.png)

* [World Wide Web Consortium(W3C)](https://www.w3.org/) [[**T**](https://twitter.com/w3c)] [[**G**](https://github.com/w3c)]
  >The [World Wide Web Consortium (W3C)](https://www.w3.org/Consortium/) is an international community where Member organizations, a full-time staff, and the public work together to develop Web standards. Led by Web inventor and Director Tim Berners-Lee and CEO Jeffrey Jaffe, W3C's mission is to lead the Web to its full potential.
* <a href="https://lists.w3.org/Archives/Public/public-vc-wg/" target="_blank">Verifiable Claims WG - Mailing List</a> (and archives)
* [Credentials Community Group](https://www.w3.org/community/credentials/)[[**B**](https://w3c-ccg.github.io/)]  
* <a href="http://lists.w3.org/Archives/Public/public-credentials/" target="_blank">Public mailing list for the Credentials Community Group</a> (and archives) - Anyone may read or write to this list.
* <a href="https://github.com/opencreds/website" target="_blank">/opencreds/website</a> 
  * [opencreds.org — Identity Credentials 1.0](https://opencreds.org/specs/source/identity-credentials/)
* <a href="https://sea-region.github.com/w3c-dvcg/w3c-dvcg.github.io" target="_blank">/w3c-dvcg/w3c-dvcg.github.io</a> - Landing site for W3C Digital Verification Community Group. [<a href="https://www.w3.org/community/digital-verification/">**W**</a>]
* [JSON-LD 1.0, W3C Recommendation](https://www.w3.org/TR/json-ld/)

![](https://imgur.com/6MLNgXal.png)\
<sup><a href="https://www.youtube.com/watch?v=RllH91rcFdE">The Story of Open SSI Standards - Drummond Reed/Evernym SSIMeetup.org</a>[<b><a href="https://www.slideshare.net/SSIMeetup/self-sovereign-identity-ssi-open-standards-with-drummond-reed">ϟ</a></b>]</sup>

#### DID the Decentralized Identifier [**^**](#contents) 

<a href="https://www.w3.org/2018/vocabws/presentations/Sabadello.pdf"><img src="https://i.imgur.com/7NRcJbq.png"/></a>

* [A Universally Unique IDentifier (UUID) URN Namespace](https://www.ietf.org/rfc/rfc4122.txt) <-DID's modeled after
  * [All you need to know about sequential UUID generators](https://blog.2ndquadrant.com/sequential-uuid-generators/)
* [w3c- Decentralized Identifiers (DIDs) v0.11](https://w3c-ccg.github.io/did-spec/)
  * Authors:
     * [Drummond Reed](https://equalsdrummond.name/) [[**T**](https://twitter.com/drummondreed)] ([Evernym](https://www.evernym.com/))  
     * [Manu Sporney](http://manu.sporny.org/)[[**T**](https://twitter.com/manusporny)]  ([Digital Bazaar](https://digitalbazaar.com))
     * Dave Longley ([Digital Bazaar](https://digitalbazaar.com))
     * [Christopher Allen](http://www.lifewithalacrity.com/) [[**info**](https://github.com/ChristopherA/info)] ([Blockstream](https://blockstream.com/))
     * Ryan Grant
     * [Markus Sabadello (Peacekeeper)](http://mydata2016.org/speaker/markus-sabadello/) [[**T**](https://twitter.com/peacekeeper)] [[**G**](https://github.com/peacekeeper)] [[**B**](https://medium.com/@markus.sabadello)] ([Danube Tech](https://github.com/projectdanube))
* [Understanding Decentralized IDs (DIDs)](https://medium.com/@adam_14796/understanding-decentralized-ids-dids-839798b91809)
* [DID Primer](https://github.com/WebOfTrustInfo/rebooting-the-web-of-trust-fall2017/blob/master/draft-documents/did-primer.md) [[**ϟ**](https://github.com/WebOfTrustInfo/rwot7-fall2018/blob/master/topics-and-advance-readings/did-primer-extended.md)]
* [Decentralized IDentifers (DIDs)](https://www.w3.org/2018/vocabws/presentations/Sabadello.pdf) 
* [Requirements for DIDs](https://github.com/WebOfTrustInfo/ID2020DesignWorkshop/blob/master/final-documents/requirements-for-dids.pdf)
* [DIDs in DPKI](https://github.com/WebOfTrustInfo/rwot7/blob/master/topics-and-advance-readings/dids-in-dpki.md)
* [What is a DID?](https://docs.google.com/document/d/1Ym85y_bDVN9xkRZ-oD-zlUUIeZjVGWNihfZBk2GQidk/edit)
* [The Path from an id (DID) to a Real-Life Something](https://hyperonomy.com/2019/01/04/the-path-from-a-id-did-to-a-real-life-something)

<a href="https://hyperonomy.files.wordpress.com/2019/01/path-id-did-real-life-somethings-v0.2-1.png"><img src="https://hyperonomy.files.wordpress.com/2019/01/path-id-did-real-life-somethings-v0.2-1.png?w=500"/></a>

#### Verifiable Claims [**^**](#contents) 

<a href="https://www.w3.org/2018/vocabws/presentations/Sabadello.pdf"><img src="https://i.imgur.com/nsZ0X7r.png"/></a>


* [Verifiable Claims Working Group](https://www.w3.org/2017/vc/WG/) [[**D**](https://www.w3.org/2017/vc/charter.html)]
* [Verifiable Claims Data Model 1.0](https://w3c.github.io/vc-data-model/) [[**G**](https://github.com/w3c/vc-data-model)] [[**D**](https://w3c.github.io/vc-use-cases/)]
* [Verifiable Credentials 101 for SSI – Tyler Ruff – Webinar 11](http://ssimeetup.org/verifiable-credentials-101-ssi-tyler-ruff-webinar-11/)


### DID Auth [**^**](#contents) 

![](https://imgur.com/XMaq5cil.png)


   * [DID Auth and the Little I-am-Me](https://medium.com/@markus.sabadello/did-auth-and-the-little-i-am-me-ec14d757ff09)
   * [Introduction to DID Auth](https://github.com/WebOfTrustInfo/rebooting-the-web-of-trust-spring2018/blob/master/final-documents/did-auth.md) [[**ϟ**](http://ssimeetup.org/introduction-did-auth-markus-sabadello-webinar-10/)]

<a href="http://ssimeetup.org/introduction-did-auth-markus-sabadello-webinar-10/"><img src="https://i.imgur.com/YNlk8RY.png"/></a>\
http://ssimeetup.org/introduction-did-auth-markus-sabadello-webinar-10


### Decentralized Key Management-Agents [**^**](#Contents) 

<img src="https://i.imgur.com/0SLcjUv.png"/>

* [Decentralized Key Management (DKMS): An Essential Missing Piece of the SSI Puzzle - Drummond Reed](https://www.slideshare.net/SSIMeetup/decentralized-key-management-dkms-an-essential-missing-piece-of-the-ssi-puzzle-drummond-reed)
* [Recommendations for Decentralized Key Management Systems](https://github.com/WebOfTrustInfo/rebooting-the-web-of-trust-fall2017/blob/master/topics-and-advance-readings/dkms-recommendations.md)
* [Agent to Agent Communication](https://drive.google.com/file/d/1PHAy8dMefZG9JNg87Zi33SfKkZvUvXvx/view): Daniel Hardman explains the goals of agent to agent communication


![](https://i.imgur.com/5qc1qrG.png)\
<sup><a href="http://ssimeetup.org/decentralized-key-management-dkms-essential-missing-piece-ssi-puzzle-drummond-reed-webinar-8/">DKMS - An Essential Missing Piece of the SSI Puzzle. Drummond Reed. SSIMeetup.org</a></sup>

* <a href="https://query.prod.cms.rt.microsoft.com/cms/api/am/binary/RE2DjfY" target="_blank">Microsoft- Decentralized Identity — Own and Control Your Identity.</a>
![](https://i.imgur.com/ozOLCuW.png)


### Learning Machine [**^**](#contents) 

[Learning Machine](https://www.learningmachine.com/)
* [Academic Credentialing and the Blockchain](https://www.learningmachine.com/academic-credentialing-blockchain/)

#### Blockcerts [**^**](#contents) 

* [Blockcerts](https://www.blockcerts.org), developed by learning machine is an open standard for issuing and verifying blockchain-based official records; The project offers  open-source libraries, tools, and mobile apps. MIT has [issued](https://www.insidehighered.com/news/2017/10/19/mit-introduces-digital-diplomas) digital certificates based on this standard.
  * [CXC (Carribean) Pilots E-Certificates on the Blockchain](https://www.cxc.org/cxc-pilots-e-certificates-on-the-blockchain/)
  * [A Decentralized Approach to Blockcerts Credential Revocation](https://github.com/WebOfTrustInfo/rebooting-the-web-of-trust-fall2017/blob/master/final-documents/blockcerts-revocation.md)

### ERC - EIP [**^**](#contents)

#### ERC 725 - 735 

* [ERC725](https://github.com/ethereum/EIPs/issues/725) • [ERC735](https://github.com/ethereum/EIPs/issues/735)
   * proposals in the Ethereum community to standardize smart contracts for certain identity-related operations such as key management, as well as signing transactions, documents, and "claims", which may be attested by third parties or self-asserted.
   * [Origin partners on ERC725](https://coinjournal.net/origin-protocol-partners-on-new-erc-725-alliance-to-promote-the-adoption-of-blockchain-based-identity-standard)
* [Managing Identity with a UI—ERC-725](https://medium.com/originprotocol/managing-identity-with-a-ui-for-erc-725-5c7422b38c09)
* [Ethereum ERC725 Blockchain Based, Self-Sovereign Identity Management](https://bitcoinexchangeguide.com/ethereum-erc725-blockchain-based-self-sovereign-identity-management/)
* [erc725alliance.org](https://erc725alliance.org)

#### ERC Other [**^**](#contents)

* [ERC: Lightweight Identity #1056](https://github.com/ethereum/EIPs/issues/1056) —This ERC describes a standard for creating and updating identities with a limited use of blockchain resources. An identity can have an unlimited number of delegates and attributes associated with it. Identity creation is as simple as creating a regular key pair ethereum account, which means that it's fee (no gas costs) and all ethereum accounts are valid identities. Furthermore this ERC is fully DID compliant.
* [ERC-1484: Digital Identity Aggregator #1495](https://github.com/ethereum/EIPs/issues/1495) —A protocol for aggregating digital identity information that's broadly interoperable with existing, proposed, and hypothetical future digital identity standards.
* [ERC1056 ❤ ERC780 — an open identity and claims protocol for Ethereum](https://medium.com/uport/erc1056-erc780-an-open-identity-and-claims-protocol-for-ethereum-aef7207bc744)
* [ERC-1077 and ERC-1078: The magic of executable signed messages](https://ethereum-magicians.org/t/erc-1077-and-erc-1078-the-magic-of-executable-signed-messages-to-login-and-do-actions/351)

### Schema [**^**](#contents)
* [Schema](https://schema.org) — a collaborative, community activity with a mission to create, maintain, and promote schemas for structured data on the Internet. Schema.org vocabulary can be used with many different encodings, including RDFa, Microdata and JSON-LD. These vocabularies cover entities, relationships between entities and actions, and can easily be extended through a well-documented extension model. Over 10 million sites use Schema.org to markup their web pages and email messages. Many applications from Google, Microsoft, Pinterest, Yandex and others already use these vocabularies to power rich, extensible experiences."

## Assorted Thought around Identity [**^**](#contents)
* [Decentralized Identity Trilemma](http://maciek.blog/decentralized-identity-trilemma/)
   >There seems to exist a trilemma in decentralized identity analogous to @Zooko's triangle. None of the existing solutions are at the same time: 1) privacy-preserving, 2) Sybil-resistant 3) self-sovereign -[[**T**](https://twitter.com/MaciekLaskus/status/1031859093072424960)]
   * [Maciek Laskus | BLOCKWALKS](https://www.youtube.com/watch?v=KAgJpQfQXxs) (video)
   * "I designed an algorithm that mapped out people [working on identity](https://twitter.com/MaciekLaskus/status/1066780557906976768) using Twitter data:" [Identity list](https://docs.google.com/spreadsheets/d/1hBBVA0-jqmRRZ_JFQ8HEck9tFub7crsqRzlBZWf01xg/edit?usp=sharing)
* [Proof of Thought (PoT)](https://bitcointalk.org/index.php?topic=4459113.0)
* [Queer Privacy](https://leanpub.com/queerprivacy)
   >Stories about using the Internet as a tool to find out more about yourself, and as a tool to express and empower; about the dangers of Internet censorship and about the practical realities of maintaining multiple distinct digital identities. 
* [@SarahJamieLewis Twitter thread on Identity](https://twitter.com/SarahJamieLewis/status/1041043532654542848)
   >Any technology which relies on the existence of, or attempts to create a, global, unique identity is oppressive by design. Stop" innovating" oppressive structures.


## DID Adoption [**^**](#contents)

**[DID Method Registry](https://w3c-ccg.github.io/did-method-registry/#the-registry)**
* did:example:   - [DID Specification](https://w3c-ccg.github.io/did-spec/)
* did:btcr:      - [BTCR DID Method](https://w3c-ccg.github.io/didm-btcr/) 
  * The Bitcoin Reference DID method (did:btcr) supports DIDs on the public Bitcoin blockchain. The Bitcoin Reference method has minimal design goals: a DID trust anchor based on the Bitcoin blockchain, updates publicly visible and auditable via Bitcoin transactions, and optionally, additional DID Document information referenced in the transaction OP_RETURN data field. No other Personal Identifiable Information (PII) would be placed on the immutable blockchain.
  * [btcr tx conversion playground](https://weboftrustinfo.github.io/btcr-tx-playground.github.io/) 
* did:stack:     - [Blockstack DID Method](https://github.com/blockstack/blockstack-core/blob/master/docs/blockstack-did-spec.md) [[**ϟ**](https://forum.blockstack.org/t/did-method-at-identity-foundation/4287/9)] 
  - Blockstack is a network for decentralized applications where users own their identities and data. Blockstack utilizes a public blockchain to implement a decentralized naming layer, which binds a user's human-readable username to their current public key and a pointer to their data storage buckets.
* did:cnsnt:   - Consent 	
* did:erc725:  - [erc725 DID Method](https://github.com/WebOfTrustInfo/rebooting-the-web-of-trust-spring2018/blob/master/topics-and-advance-readings/DID-Method-erc725.md)
* did:ipid:    - [IPID DID method](https://did-ipid.github.io/ipid-did-method/)
  - Implementation of the DID spec over IPFS (Interplanetary File System) 
* did:life:    - [lifeID DID Method](https://lifeid.github.io/did-method-spec/)
* did:sov: 	   - [Sovrin DID Method](https://sovrin-foundation.github.io/sovrin/spec/did-method-spec-template.html)
* did:uport: 	- uPort 	
* did:v1: 	   - [Veres One DID Method](https://w3c-ccg.github.io/didm-veres-one/)
  * [**veres.one**](https://veres.one) — a permissionless public ledger designed specifically for the creation and management of decentralized identifiers (DIDs)
* did:dom:     - Dominode 	
* did:ont: 	   - [Ontology DID Method](https://github.com/ontio/ontology-DID/blob/master/docs/en/DID-ONT-method.md)
* did:vvo: 	   - [Vivvo DID Method](https://vivvo.github.io/vivvo-did-scheme/spec/did-method-spec-template.html)
* did:icon:    - [ICON DID Method](https://github.com/icon-project/icon-DID/blob/master/docs/ICON-DID-method.md)
* did:iwt: 	   - [InfoWallet DID Method](https://github.com/infowallet/did_method/blob/master/did_method.md)
* did:ockam:   - [Ockam DID Method](https://github.com/ockam-network/did-method-spec/blob/master/README.md)
  * [did:ockam:](https://medium.com/ockam/an-introduction-to-did-ockam-8626d5aecc53) [[**ϟ**](https://twitter.com/Ockam_io/status/1064589363269365763)]
* did:ala: 	   - [Alastria DID Method](https://github.com/alastria/alastria-identity/wiki/Alastria-DID-Method-Specification-(Quorum-version))
* did:op:      - [Ocean Protocol DID Method](https://github.com/oceanprotocol/OEPs/blob/master/7/did-method-spec.md)
* did:jlinc:   - [JLINC Protocol DID Method](https://did-spec.jlinc.org/)
* did:ion:     - [ION DID Method](https://github.com/decentralized-identity/ion-did-method)
* did:jolo:    - Jolocom 	
* did:ethr:    - [ETHR DID Method](https://github.com/uport-project/ethr-did-resolver/blob/develop/doc/did-method-spec.md)

---

* [@ChristopherA on DID adoption](https://twitter.com/ChristopherA/status/989122017348784130)
   > "22/ Over a dozen companies and organizations, using multiple blockchains (Bitcoin, Ethereum, Hyperledger, etc.), have committed to deploying DIDs, including IBM, Microsoft, Digital Bazaar, Consensys, Evernym, Learning Machine, British Columbia, and more:" —[How blockchain could solve the internet privacy problem](https://www.computerworld.com/article/3267930/blockchain/how-blockchain-could-solve-the-internet-privacy-problem.html)
* [Peer DID Method Spec](https://dhh1128.github.io/peer-did-method-spec/index.html)
* [Spidchain](http://www.spidchain.com/) [[**wp**](https://drive.google.com/file/d/0B89WE3IIHmy1Z0ZSSWVmVEtaaG8/view)]
   * "offers a platform for self-sovereign identity, including desktop and mobile apps for end-users. It uses Decentralized Identifiers (DIDs) - backed by optionally Bitcoin or Ethereum - to implement a marketplace for verifiable claims. The Spidchain applications allow individuals to create, recover, and revoke DIDs, to authenticate, to sign and verify files and claims, and more."

![](https://oneworldidentity.com/wp-content/uploads/2018/10/companies.png)

2018 Identity Landsacpe brought to you by: [One World Identity](https://oneworldidentity.com/) — independent advisory and digital strategy consultancy focused on trust and the data economy.

## Directory [**^**](#contents)
Other files and folders within this repository:

* [SSI\DID History](history.md)
* [Self Sovereign Identity](self-sovereign-identity)
* [Identity Related GitHub Repositories](identity-github.md)
* [Literature](literature/) - Research and Reports
* [Rebooting-Web-of-Trust](rebooting-web-of-trust.md) 
* [Media](assorted-media.md) - Video, Podcasts and 
* [Indy Ecosystem](indy-ecosystem/)
  * [Indy Github](indy-ecosystem/indy-github.md)
  * [Literature](indy-ecosystem/literature.md)
  * [Adoption](indy-ecosystem/adoption.md)
  * [Sovrin Foundation](indy-ecosystem/sovrin.foundation.md)
    [VON](indy-ecosystem/VON.md)
* [Hyperledger Global Forum](hgf-2018/)
* [Decentralized Identity Foundation—DIF](identity-foundation.md)
* [Ethereum](ethereum/)
* [State Sponsored](state-sponsored.md)
* [IBM](ibm.md)
* [Microsoft](microsoft.md)
* [Humanitarian](humanitarian.md)
* [GDPR](gdpr.md)



## Sources [**^**](#contents)
* [SSI Meetup](http://ssimeetup.org/) [[**V**](https://www.youtube.com/channel/UCSqSTlKdbbCM1muGOhDa3Og)][[**ϟ**](https://www.slideshare.net/SSIMeetup/presentations/)] 
* [IIW-Wiki](https://iiw.idcommons.net/Main_Page)
* [wiki.idcommons.net](http://wiki.idcommons.net/Main_Page)
* [/WebOfTrustInfo](https://github.com/WebOfTrustInfo/)
* [/peacekeeper/blockchain-identity](https://github.com/peacekeeper/blockchain-identity)
* [identitywoman.net](https://identitywoman.net/)
* [windley.com/tags/identity](http://www.windley.com/tags/identity.shtml)
* [/indy-sovrin-evernym](https://github.com/infominer33/awesome-decentralized-id/blob/master/indy-sovrin-evernym/)

