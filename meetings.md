# Secure Design - Community Calls

[![hackmd-github-sync-badge](https://hackmd.io/fATDo4lQTymza-XxPwxG7A/badge)](https://hackmd.io/fATDo4lQTymza-XxPwxG7A)

[Community Calendar](https://lu.ma/securedesign) • [Github Discussions](https://github.com/ChainAgnostic/secure-design/discussions)

## #11 February 21, 9am PST

### In attendance

- Aaliyah
- Ryan

### Agenda & Notes

- Focused on EIP-3074 discussions. Summary here:https://github.com/ChainAgnostic/secure-design/discussions/16
- Reviewed the difference between approve() contract interactions and PERMIT/PERMIT2 messages
- Eth call next week, breakout focused on EOA/AA. We should attend: https://github.com/ethereum/pm/issues/962
- link to Wallet Unsalon in Denver: https://app.unlock-protocol.com/event/wallet-uncon-unsalon-expression-of-interest

## #10 January 17, 9am PST

Zoom link was invalid again. Sent out update via email and will fix for good before the next meeting. Apologies to any for whom this caused confusion.

### In attendance:
- Ryan
- Juan
- Aaliyah 

### Agenda & Notes:
- Proposed EIP-7377, but progess is stalled. Responded in the thread on Eth Magicians to say we're ready to help when or if it boots back up.
- Now let's turn our focus to EIP-3074 (possibly with EIP-5003?) and EIP-7212.
- EIP-3074
    - In what's does this meaningful differ from EIP-7377?
    - Whomever is going to propose this call to your "Wallet Client" / Wallet [needs to be trusted](https://ethereum-magicians.org/t/eip-3074-auth-and-authcall-opcodes/4880/63)
    - There needs to be some awareness about what EOA and Contract Accounts are, using more approachable language for non-experts.
    - We need to figure out recommendations for dApps and Wallets to inform people about these things — expressly not using the term "educate" here.
- Todo: write up an Ethereum Magicians unifying thread about EOA -> Contract Account migrations referencing EIP-7377, 3074, 7212.
- Juan: UX of Standards Process in general
    - what is the role of CASA in the Ethereum standards process?
    - seems like Eth Magicians is less active, because there's maybe a bit more fracturing to L2s/RIPs and less low hanging fruit
    - let's try reviving things and involving more voices

## #9 December 6, 9am PST 

Zoom link comes up "invalid". 
https://us02web.zoom.us/j/6558088617?pwd=MGV4QnA5bmlwWWJ3eWVTUHRqazhEQT09

### In attendance:
- Ryan, Fission
- Antonela, MetaMask
- Doug, PeerPiper
- Aaliyah 

### Agenda & Notes:
- antonela: OffScript debrief - designers feel that AA (4337) has given us everything we need
    - risk that this will actually inhibit users sense of ownership
    - this could cause too much fragmentation in the system as different silos implement their own SCA that aren't interoperable. Safe will ship w/in Safe Network, Family wallet into Lens
    - How are we going to, as a community of designers, connect all of these accounts?
    - How do we make it easier for people to manage their many accounts across many networks
- Ryan: heavy agree - we need to reframe Account Abstraction as a bundle of outcomes, rather than focus on specific flavours of achieving those. Including things like programmability, etc. You may be able to achieve these with a combination of tactics.
- Aalyiah: the best UX for web3 is where are user doesn't have to download anything
- Antonela: let's stop worrying about the next billion until we've addressed the needs of the current 10 million. There are constraints when you have to deal without a central intermediary.
    - We can take patterns from what exists, but we are not building what exists.
    - I *have* to make sure that people are *reading* things
    - Let's apply all of our expertise tangibly to an API. Deconstruct it, and bring user facing mental models to the discussion
- Doug: in most ux you have basic functiolity and then "..." hiding more. Could we apply that here?
- Aaliyah: k-pop collectibles are an example of collaging things together 
- Year in review
    - Legible Authorization / How To Ask Permission
    - Trust Indicators
    - No Defaults
    - Threat Modelling 
- Year to come
    - Educate VS Inform
    - Anatomy of Secure Design
    - Grants
    - EIP-7377 (https://ethereum-magicians.org/t/eip-7377-migration-transaction/15144/23?u=bumblefudge) if this gets to review/last-call stage and they want UX considerations or security mitigations - agenda for a future meeting
    - Norm Hardy Prize: https://foresight.org/norm-hardy-prize/
- WalletUncon highlights
    - aaliyah: moving beyond just asset ownership, towards communication networks 
    - doug: secret sharing and messaging
    - ryan: compelling designers to engage w/ technical standards

## #8 October 17, 8am PST 

### In attendance:
- Ryan, Fission
- doug

### Agenda & Notes:
- Kept the meeting light and discussed backgrounds that brought us to the space

## #7 September 26, 8am PST 

### In attendance:
- Ryan, Fission
- pfc
- doug 
- antonela

### Agenda & Notes:

- Antonela: 
    - how much do we decentralize now, and how much do we decentralize later. But more importantly how do the decisions we make today enable us to still achieve that future vision.
    - as a system designer, the defaults we choose now will condition user behaviour - even for experts
    - how do we achieve fewer defaults?
    - lets apply for grants!
    - security indicators: 
        - lock in the URL bar: this is governed by certificate authorities. what kind of trust process are we outsourcing to other organizations, and to what degree are we aware that is happening?
        - how do pet names fit into a "web of trust" style system that could replace certificate authorities?
    - how does our criticality about these problems concretely impact designs we ship today?
- Doug: how does trust relate to desire paths? "paving the cowpaths"
    - There might be two extremes in terms of trust personas: folks that trust right away and revoke it over time, or awared *zero* trust to start with and dole it out over time as it is earned.
- Pet names:
    - we have systems in the middle of all relationships that mediate and co-construct trust. those are the systems that we are building.
    - those systems are defacto attenuating the flow of trust between the parties in those relationships
    - the entities trusting each other might give each other "pet names" — how those are implemented greatly impacts 
    - Name Name System: https://fission.codes/ecosystem/whocan-and-nns/
- Multiple identities:
    - it's important to support multiple "Ryans" that may or not be labelled "Ryan".
    - Account Metadata Standard: https://docs.google.com/document/d/1baSoCMcd8LHsOcg_KKLJLBqhqBreI2A6KldD9l86jC0/edit#heading=h.mk41nv5erwgt

- Trust indicators in permissionless systems - https://github.com/ChainAgnostic/secure-design/discussions/14
- Threat modelling: https://github.com/ChainAgnostic/secure-design/discussions/13
- - EIP-7377 for turning an existing EOA into a SC Wallet
    - [our group has been asked to give some input](https://ethereum-magicians.org/t/eip-7377-migration-transaction/15144/23?u=bumblefudge) if this gets to review/last-call stage and they want UX considerations or security mitigations - agenda for a future meeting

### Announcements:
- WalletUncon.org - CFP deadline Nov 1
- Norm Hardy Prize - deadline September 30: https://foresight.org/norm-hardy-prize/

## #6 August 22, 8am PST - [RSVP](https://lu.ma/tyyxp3uf)

### In attendance:
- Stefan Magdalinski, Filecoin Foundation
- Nick Thomas (@nichoth), Formulate / [Half Light](https://github.com/ssc-hermes)
- Erin
- Juan 
- Ryan
- Agost

### Agenda & Notes:

- Self-intros
    - Nic: working on e2e social network running on WNFS, and getting to the authz flows now about who can see what
    - Erin: when you post something, selecting groups that control visibility. There's a tension between making it easy and placing a burden on people.
    - Stef: Big interest on UX and security
    - Agost: primary focus on token approvals
- Research notes
    - Ryan: HCI OG Angela Sasse (Bochum, UCL)
        - humans do what they can, often security break downs are insufficient mental models or cognitive tools given to users
        - "functional" versus "structural" mental models
        - [ ] AI: Ryan will add some greatest hits to the biblio thread on GH discussions
    - Definitions of auth terminology is needed. Let's make a glossary.
    - How To Ask Permission Flow: let's take a look at alternatives to, or stricter definitions of, the "Application" bucket. In decentralized systems, it's not so clear what the application boundaries are.
    - Threat modelling: are there simple exercises to get started? Started a thread: https://github.com/ChainAgnostic/secure-design/discussions/13
- F2F in Berlin
    - Sometime between Sep 8-18, organizing a meetup in Berlin

### Announcements:

- DappCon: Legible Authorization workshop
- WalletUncon.org - 
- Minor things moving through EIP processes:
    - EIP-7377 for turning an existing EOA into a SC Wallet
        - i may have low-key [volunteered this group to give some input](https://ethereum-magicians.org/t/eip-7377-migration-transaction/15144/23?u=bumblefudge) if this gets to review/last-call stage and they want UX considerations or security mitigations - agenda for a future meeting
- Norm Hardy Prize: https://foresight.org/norm-hardy-prize/

## #5 July 18, 8am PST - [RSVP](https://lu.ma/haxnzcfm)

### In attendance: 

- Ryan Betts, Fission
- Agost Biro, SealVault
- Eileen Wagner, [Decent Patterns](https://decentpatterns.com/)
- Gabriel 
- Antonela, MetaMask
- Juan Caballero, chainagnostic.org


### Agenda & Notes:
- Ryan presenting: How to Ask Permission: https://github.com/ChainAgnostic/secure-design/discussions/7
    - starting points came from Android team c. 2013
    - market evolution since: install-time warning/consents-in-advance to sidestep the warnings and interactions this mandates
        - other grantees of permission: web platform, identity provider/middleman... proliferating [consents and policies](https://wompampsupport.azureedge.net/fetchimage?siteId=7575&v=2&jpgQuality=100&width=700&url=https%3A%2F%2Fi.kym-cdn.com%2Fentries%2Ficons%2Ffacebook%2F000%2F020%2F852%2Fforgot_to_ask_thumb.jpg)
    - updated with Agost:
        - ryan: going deeper than just severity and reversibility; local-only seems to derail assumptions here (most local-only easily reversed/undone)
    - Q&A/responses
        - antonela - might that consent dialogue be quite late in the process? I can imagine a pre-set policy forking this flow
        - antonela - might the consent dialogue be confirming or varying from a pre-set default (e.g. default in browser/wallet across all sites, but first time visiting a new site/dapp/etc?)
            - backstory: tor research that users were changing global defaults just to visit one site that required a variance from them
        - antonela: another complication: delegations, AccAbs, paymasters, etc - things you want end-user to consent to might need to pass-thru multiple actors or layers... 
        - who checks the defaults? is there a fiduciary/auditor who checks in once a year and walks you through all this?
            - Juan: AccAbs is probably going to involve lots of fiduciaries and middle-men...
            - Antonela: trust signals and reputation/associations can be layered on to these decision points, and trust registries
                - petname layer on top of that
        - antonela: consent has to happen upfront for anything dynamic to come later
            - ryan: scope this work already done to implicit-trust context; think about more complex version for other contexts
        - antonela: local allowlist which parses on top of defaults and policies (e.g. interruptive consent adds counterparty to exception list) was the dominant strategy when i was at Tor
- Spender Approval UX Pattern Guidance: https://github.com/ChainAgnostic/secure-design/discussions/9
    - agost: intro: urgent and crucial for web3 UX today
        - MM swap tab, uniswap, 1inch
            - antonela: sidebar about MM allowance UX: allowance UX has been iterated drastically due to trial-and-hour; it's a major problem for us, even with all the UX research and metrics we're STILL not sure end-users are actually reading what they're allowing, it forced a tradeoff of ethics<>business... very much work in progress still!
        - UX review 
            - uniswap has a separate step to confirm (but onetime/ongoing distinction not exactly explicit in dialogue text...) - "spending"
            - MM swap tab is functionally a "trusted interface", warns you about high "spending caps"
            - coinbase "withdrawal limit"
        - 1inch - "permit" pattern = offchain signature gets bundled with onchain approval
            - MM shows it not as a trusted interface because it's an offchain; 
            - CB wallet displays hideous EIP712 object in prompt :face_with_rolling_eyes: - doesn't love offchain txns
        - Antonela - This is all kind of bespoke... not gonna scale
- Future Topic - permissions are unauditable - protocol definitions needed :sob: 
    - antonela: everyone's optimizing for their own products in a way that neither scales nor gives their user much sovereignty
    - agost: i want to design a library that can parse all the receipts of these events (and combine that with txn simulation and trust signaling)

### Discussed CAIPs
- https://github.com/ChainAgnostic/CAIPs/blob/master/CAIPs/caip-25.md

### Announcements:
- Notes from the DWeb workshop: https://github.com/ChainAgnostic/secure-design/discussions/11
- DappCon: Legible Authorization workshop
- WalletUncon: Friday Nov 17, during DevConnect in Istanbul
- Next call: Aug 22 @ 8am PST • [RSVP](https://lu.ma/519c90f6)

## #4 June 20, 8am PST - [RSVP](https://lu.ma/oal36w87)

### In attendance:

- Ryan Betts, Fission
- Agost Biro, SealVault
- Juan Caballero, CASA/PLN
- Salief Lewis (AFK)
- Randall (Thunderbolt Labs)

### Agenda & Notes:

- **Discussions**: This month's call will focus on review & feedback of permissions & authorization UX prototypes.
    - Agost Biro: Spender Approval UX Pattern Guidance // [PassKey Creation guidelines from FIDO Alliance](https://fidoalliance.org/ux-guidelines-for-passkey-creation-and-sign-ins/) ?
        - interested in fleshing out collab?
        - shared icons inherited from FIDO collab documentation...
        - Discussion with call notes: https://github.com/ChainAgnostic/secure-design/discussions/9
- **Projects**: What can Secure Design do to move things forward this month?
    + DWeb Camp:
        + Ryan's session: Legible AuthZ
        + Jonny & Hester's session: Trust Signals


## Helpful Tools

- High level flow diagram
- Figma UI Kit for iconography?

## Upcoming Events

- Secure Design @ [DWeb Camp - June 21-25](https://dwebcamp.org/)
- [Wallet Uncon](https://github.com/WalletUnCon) - Nov 17 (tentative), Istanbul
  - any volunteers?

## Action items
- Possible project to investigate accessibility concerns when switching between wallet and dapp to sign stuff
- ryan will look into a community/open-source Figma org for sharing drafts and merging PRs
    - might be good to assess penpot as plan B in case we have to ditch figma suddenly for [new mgmt reasons](https://www.reuters.com/markets/deals/adobes-deal-acquire-figma-under-threat-eu-regulators-ft-2023-06-20/) (other shoe may not have dropped yet on that acquisition)

## #3 May 16, 8am PST - [RSVP](https://lu.ma/b2faxjtg)

### In attendance:

- Ryan Betts, Fission ([@depatchedmode](https://twitter.com/depatchedmode) everywhere)
- Agost Biro, SealVault
- Antonela, MetaMask
- Juan Caballero, CASA
- Salief Lewis, Public Assembly
- Sam Gbafa, Spruce
- Charles Cunningham, Spruce
- Johnny Howle

### Agenda & Notes:

- **Announcements:**
    - Bluesky account: [securedesign.bsky.social](https://staging.bsky.app/profile/securedesign.bsky.social) ? (should I get us @chainagnostic.org ??? haven't done it yet but i think it's just a signature in a /.wellknown/ or a TXT rec or something)
- **Discussion:**
    - Quick intro to ReCap (Spruce)
        - [grab link to Sam's presentation](https://docs.google.com/presentation/d/16eLv4z52zMyKVhDl8VAJJjegs8G6rdV_eo90EQRJHNY/edit) 
            - need permissions tho, maybe save as PDF and host somewhere public?
        - extension to SIWE that aims to give users the authority to grant permissions to an app
        - focus is on helping people *understand* what they are saying yes to - informed consent
        - The ReCap payload is a barebones standard that a more optimal UX / grammar could be built atop of
        - Concern: Reads a bit like a ToS right now. Could something like a Metamask ReCap Snap make this more legible? Possibly there could be registry of ReCap namespaces that help to organize this?
        - Salief: does this differ from Stella and Fire wrt interpreting transactions? 
        - Sam: ReCap is mostly about informed consent and communication of the authorization
        - Antonela/Johnny: how does it relate to [Delegatable](https://delegatable.org/docs/feature)?
        - Sam: ReCap is off-chain vs delegatable which is solely on-chain. ReCap is DID focused. 
        - Sam: looking at session keys and AA: how can you delegate a spend limit to a session key? ReCap could offer help here.
        - Antonela: how do you handle expiry / revocation / management session-keys multi-chain?
        - Sam: delegate to browser key / session key and then that could be short lived or expire with the session. If you want something longer lived, management of that key is an open question.
        - Juan: look at chain proofs https://github.com/ChainAgnostic/CAIPs/pull/218/files
        - Antonela: you are providing a way to delegate trust, but there's no way to expose that to users at the moment
        - Sam: revocation may be out of scope of the ReCap spec itself. in the kepler implementation we do it one way. in Ceramic or Fission there might be a more appropriate way. ReCap is about making the granting verifiable and legible.
        - Ryan: two problems
            - where is my history
            - how do I let the world know I've changed my consent
        - Antonela: this is already a problem with messages in general. We cannot show all that history. With Delegatable specifically how to you propogate the revocation at one branch in the tree of delegations, for example.
        - Ryan: what about making permissions piecemeal and progressive? and where does that data live?
        - Antonela: contextual permissions
        - Johnny: do you see atomizing being a path? or do you redefine the whole basket of permissions?
        - Sam: We want to focus on helping developers manage this and right now going the basket route.
        - Johnny: does granting permissions have to happen in the wallet dialogue? Or can it work with session keys?
        - Charles: In web apps we've been trying to minimize trips to metamask. We generate a session key in the browser to do all the things you need with various services. Tradeoff between UX and how you manage session keys. If you want contextual permissions you can create a session key that recieves all the permissions and then delegate from that security scope. You would have to trust the "UI" that contains the session key. 
        - Antonela: some permissions that are unrevocable in Metamask. For example, connection to the browser only revokes the permission to ask again. Exposing the capability in an explicit way in the request.
    - Agost: understanding permissions
        - optimizing vs satisficing
        - thinking about this problem feels very in scope: to enable optimization
        - we have to eliminate permissions pop ups as much as possible
        - when we have to present a permissions request, how do we present it in a way that the user will actually read through
        - Antonela: 
            - > J. Tan, K. Nguyen, M. Theodorides, H. Negron-Arroyo, C. Thompson, S. Egelman, and D. Wagner. The Effect of Developer-Specified Explanations for Permission Re- quests on Smartphone User Behavior. In Proceedings of the SIGCHI Conference on Human Factors in Com- puting Systems, 2014. 3
            - >P. Wijesekera, A. Baokar, A. Hosseini, S. Egelman, D. Wagner, and K. Beznosov. Android Permissions Remystified: A Field Study on Contextual Integrity. In Proc. of USENIX Security, 2015. 3, 4
        - Johnny: rather than telling somebody you're going to disclose address / b-day, you tell the user whether this is increasing or decreasing privacy. how do you show people that this disclosure is deleterious to your privacy / secureness? Gamify it w/ points. We could propose this as a prototype.
        - Charles: Selective disclosure is kind of like data golf
        - Antonela: We are redesigning our allowances screen to discourage unlimited allowances. That friciton works really well. People have been more conscientious about whether to delegate this permission? Number of transaction rejections went way up. Good: less funds exposed. Bad: app communication may be failing more.
        - Juan: I also think there's a metaphorical weight to the yes/no modal-- it's a "take it or leave it". I have always been partial to popups that give at least a crumb of agency, e.g., "would you like to switch your trust level from 'low' to 'medium'? you can always change it later under settings > permissions "
    - Quick summary of permissions problems
        - Signature approval? (Agost?)
        - AA Permissions? (Antonela?)
        - Decentralized Revocation (Ryan)
- **Projects**: What can Secure Design do to move things forward this month?

### Upcoming Events: 
  - Secure Design @ [DWeb Camp - June 21-25](https://dwebcamp.org/)
  - [Wallet Uncon](https://github.com/WalletUnCon) - TBD
  - any volunteers?

### Actions Items:
- Continue discussions about Authorization / Permissions on Github. Let's select some flows to prototype — bluesky (aka no constraints... not the social messaging app) — and see what can be accomplished with today's capabilities.

## #2 April 4, 8am PST - [RSVP](https://lu.ma/iolqdlow)

### Preamble:

Our second ever Secure / Design Working Group community call!

Secure / Design WG aims to produce:
1. A set of **design principles** to guide teams
2. **Heuristics** to evaluate whether those principles are upheld, and 
3. A set of **UX patterns and best practices** to make upholding the principles a bit easier for the protocols, platforms and products that folks rely upon every day.

We're targeting design and product folks but all with a UX bent are welcome.

More background on us can be found here: 
+ [Twitter/@SecureDesignWG](https://twitter.com/securedesignwg)
+ [Secure Design: A draft of 7 principles](https://depatchedmode.mirror.xyz/4t_7BUzz5q3XlPtH7EgtGL61nh9U8plsfH23i7x5_lU)

### In attendance:

+ Ryan Betts (aka [depatchedmode](https://twitter.com/depatchedmode)), Head of Design @ [Fission](fission.codes), [Causal Islands](causalislands.com) & [Webnative](webnative.dev)
   + **I'm here because**: I want to ensure the products and systems I help to design leave folks feeling secure in every sense of the word. And I'm not smart enough to figure that out on my own.
   + **Most pressing secure design problem for me right now is:** Account creation and recovery.
+ Antonela, Lead Designer @ [MetaMask](metamask.io), [Tor Project](torproject.org)'s core contributor, [PITG](https://pitg.gitlab.io/about/) member, [0xche](0xche.org) peer
    + **I’m here** interested in end-users' impact on protocol design, with a focus on usable security.
    + **Most pressing secure design problem for me right now is:** abstracted accounts permissions, MetaMask confirmation screens, permissionless distribution.
+ Ira, Creative Director @ Protocol Labs, and @ DWeb / DWeb Camp (Join the camp! https://dwebcamp.org/what-to-expect/)
    + **I'm here because**: I don't know a lot about secure design, beyond the surface knowledge, I'm here to learn, and contribute as I can. 
    + **Most pressing secure design problem for me right now is:** curating headless brands (not the topic on this WG, though)
+ Jonny Howle, Free Agent (formerly: Co-founder, Head Product and Strategy @ Disco.xyz)
    + **I'm here because**: Identity (and its related concerns in security and privacy) is at the root of most of the problems with online life and our inability to create a decentralized and sufficiently ethical identity system stands between us and the feature we want to create.
    + **Most pressing secure design problem for me right now is**: Account management, recovery, and key delegation
+ Michelle Lai aka ML, Free Agent (Universal Privacy Alliance; formerly: head of BD at Anchorage, Zcash grants board); Twitter @michlai007
    + **I'm here because**: I want to be able to sleep and go on holidays instead of wondering when my next heart attack from crypto will happen
    + **Most pressing secure design problem for me right now is:** multiple-identity management for privacy and security
+ Howard Tam, Senior Protocol Engineer @ Lit Protocol
    + **I'm here because**: _not_ a designer, but interested in providing technical perspective on (end-user) design and feeding back any insights into protocol layer development.
    + **Most pressing secure design problem for me right now is:** secure web2 authentication schemes for onboarding to web3 platforms.
+ [Salief Lewis](https://twitter.com/salieflewis) Core Contributor @ Public Assembly
    + **I’m here because I want to help codify user aligned design practices.**
+ Ligi: https://ligi.de
    + **I'm here because**: Learn from designers and represent CASA
    + **Most pressing secure design problem for me right now is:** how to make sure users know what they are signing
+ Meesh Lin [nf.td/meesh](https://nf.td/meesh): Head of Design @ [Commonwealth](https://www.commonwealth.im/), Design Lead @ [AIFS](https://mirror.xyz/0x7B7aE39D0ffA8d2a5128b251d332E9d0bF22cfa1/dUNKKmbIjhPdD0_UtIZIU-iUX_nR12hSwUm9cRf8-xw) ((Krause House Experiment))
    + **I'm here because**: ...
    + **Most pressing secure design problem for me right now is:** ...
+ Agost Biro: Founder @ [SealVault](https://sealvault.org/)
    + **I'm here because**: I'd like to make Web3 clients secure by default
    + **Most pressing secure design problem for me right now is:** How to simplify signature aproval (automate through [dapp isolation](https://ethereum-magicians.org/t/dapp-isolation-mechanisms/13611) / reduce to sign in or pay type of approval when it cannot be automated)

+ Tamara Adlin, Advisor & Consultant, adlininc.com
    + **I'm here because**: I've been in UX since the 90s and blockchain since 2017. I want to make UX more usable for Web 3 / product teams.
    + **Most pressing secure design problem for me right now is**: deigning UX itself--how it's communicated and modified for Web 3. Relevant article: [Why blockchain and Web3 user interfaces will suck for a while.](https://uxdesign.cc/why-blockchain-and-web-3-user-interfaces-will-suck-for-a-while-7575b7515757). More recent [Wallet UX teardown at EthDenver](https://www.youtube.com/watch?v=oTpuxYj8JWI).
    
+ Bruno Monts: Graphic Designer @ [Fission](fission.codes) & [Causal Islands](causalislands.com)
    + **I'm here because**: Coming from a design visual only, I am completely new to the subject and wanted to learn more a bit about Secure Design, especially to help me understand the aspects and problems that we find in the field.
    + **Most pressing secure design problem for me right now is:** Trying to find out and hear from you!

+ COPY ME: Name, Profession & Links
    + **I'm here because**: ...
    + **Most pressing secure design problem for me right now is:** ...

## #1 March ?, 8am PST

### Agenda:

#### (10 min) Hello & Intros

Please make sure you've added your details to "In Attendance" section.
Ryan'll give a quick pre-amble on why the group was started.

- [antonela] Want to focus on cross-disciplinary approaches to protocol design and development. Need help w/ permissions through abstraction; make sure that people don't inadvertently lose ownership. And don't want to take ownership away from people!
- [meesh] Consumer security at the product level needs to be untangled. Current offerings are scattered and need to be features pulled together into one thing. Specific problem: permissionless-ness vs respecting the boundaries of people's identities
- [ml] Identity is the way to manage privacy and safety. Having a lot of accounts and managing between them is not easy; leads to co-mingling, leaking connections. Separation of identity concerns?
- [johnny] Has been working on Account Abstraction-like things for a while via things like DIDs. Narrow slice right now: delegation of authority.
- [agost] Working on seal vault. Signature approval: how can we automate it? Or at least reduce it.
- [howard] Working on a transaction signing protocol/network to preserve security of wallets. How do we onboard folks from web2 into web3? Secure authentication flows via biometrcis.
- [tamara] We need to focus on the specific problems but also communicating the value of UX and the importance of involving it early.
- [salief] How are tools like account abstraction able to be synthesized into good practices that normal people recognize as trustable?

#### (20 min) Principles & purpose review

Open discussion about the 7 draft principles and the proposed working group outcomes.

- [tamara] we need documents that speak to various different groups including engineers: 
   - EG “how to sell UX effort into your tech team"
   - “Patterns you can use in your wallet"
   - “Landmines to avoid."
- [meesh] need resources that can help us feel confident in speaking to other strong minded folks on our team
- [ml] people who built chainalysis think of it simply as a tool. might be impossible to change their minds.
- [meesh] how do you differentiate from info synthesis tools and give users back a bit of agency
- [antonela] simply secure and decentpatterns is a great place to look. how do we work on proposals from CASA? We could have more impact if we get involved in active PRs.
- [ml] if we're not careful we might make a web3 that's worse than web2

#### (20 min) Choose an async home

Let's choose a public place to host the ongoing async discussion. Leading proposal right now is to roll it into [CASA (Chain Agnostic Standards Alliance)](chainagnostic.org):

- **Consensus:** unanimous agreement. Ryan will coordinate with Ligi/Juan
- **Potential Pros**:
  - **Likeminded folks:** A lot of wallet client teams (Brave, Metamask, etc) and protocols such as Wallet Connect are active there, which means it'd be a good point of leverage for affecting change at those UX touchpoints.
  - **UX is already a key concern:** though it is couched from an engineering / protocol perspective, a lot of what CASA is tackling are building blocks to improve the user experience in the ecosystem.
  - **Lots of momentum:** there's been significant growth in CASA activity over the past year
  - **Visibility / working in the open:** the whole CASA org infra is focused on working out in the open, and as a result it's getting a lot of visibility
  - **Ability to impact emergent dev standards:** lots of new dev patterns are starting or at least routing through CASA, so we'd be in a great position to help build out prototypes, etc.
- **Potential Cons**:
  - **Tying ourselves to blockchains:** The scope of this working group to be broader than just the commonly understood "web3" stack. Being in CASA might turn off anybody who is instinctively anti-web3. That said:
	- despite CASA having "chain" in the name, most members truly are "chain agnostic" in that a good deal of the work they do resides offchain and bumps up against DIDs, VCs, and a whole lot of "web2" tech and standards processes.
  - **Dev heavy culture:** the tooling at present is all Github, markdown, etc. Don't think there'd be resistance to us adding a few more tools to the mix, as long as they don't duplicate. And Github is a lot friendlier to non-devs these days. But, it's something to consider.
  - **IPR Concerns**: [@bumblefudge] "My only warning is to check with the other participants what level of IPR they're comfortable with-- sometimes people here the word "standards" and assume it's recorded, patent-waived, etc.  If people work for the kind of companies that, ahem, "close-source" their design work, we'd have to bump up the IPR policy of that WG, which is currently in #yolo mode because protocol design IP isn't generally as sensitive as UX"


### Action items / Tabled for async:

- Setup Github Discussions
    - Let's gather heuristics resources 
    - Let's start evaluating patterns
    - Let's get involved in existing CAIPs / PRs seeing how best to support the UX concern side of things
- Tweet announcement from SecureDesignWG twitter about forum 
- Organize next call - what other timezones to accomodate and how best to do it?

### Links:

- https://depatchedmode.mirror.xyz/4t_7BUzz5q3XlPtH7EgtGL61nh9U8plsfH23i7x5_lU
- https://decentpatterns.com/
- https://www.ietf.org/archive/id/draft-iab-for-the-users-03.html

## #X TEMPLATE - [RSVP](https://lu.ma/calendar/cal-FOmHnDL7EZJ6P5F)

### In attendance:

- (add your own name)

### Agenda & Notes:

- **Discussions**: Focus(es) of this call
- **Projects**: What can Secure Design do to move things forward this month?
- **Upcoming Events**: Where can members expect to meet up / present under the Secure Design name?
